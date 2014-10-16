#imagepreview
***

With this plug creates a preview of an image, from a given resolution. Compatible with [Bootstrat 3](http://getbootstrap.com/getting-started/#download) and [JQuery](http://getbootstrap.com/getting-started/#download).

## Demo

In development.

## Installation

#### HTML HEAD:
```
<link rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/bootstrap/3.2.0/css/bootstrap.min.css">
<link rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/bootstrap/3.2.0/css/bootstrap-theme.min.css">
        
<link href="css/jquery-image-preview.css" rel="stylesheet" type="text/css">

<script src="//code.jquery.com/jquery-1.11.0.min.js"></script>
<script src="https://maxcdn.bootstrapcdn.com/bootstrap/3.2.0/js/bootstrap.min.js"></script>

<script src="js/jquery-image-preview.js"></script>
```

or

```
<link rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/bootstrap/3.2.0/css/bootstrap.min.css">
<link rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/bootstrap/3.2.0/css/bootstrap-theme.min.css">
        
<link href="css/jquery-image-preview.css" rel="stylesheet" type="text/css">

<script src="//ajax.googleapis.com/ajax/libs/jquery/2.1.1/jquery.min.js"></script>
<script src="https://maxcdn.bootstrapcdn.com/bootstrap/3.2.0/js/bootstrap.min.js"></script>

<script src="js/jquery-image-preview.js"></script>
```

#### HTML BODY:
```
<body>
   <div class="image-preview" id="id-image-preview">
      <div class="image-wrap" data-image-width="675" data-image-height="335" data-img-name="img-curso">
         <div class="image-default">
            <img src="images/image-default-preview.png" />
         </div>
      </div>
		    
      <div class="message"></div>
		    
      <div class="action">
         <button type="button" class="btn btn-primary btn-block btn-image-preview">
            <i class="fa fa-cloud-upload"></i> Import Image
         </button>
      </div>
   </div>
</body>
````

#### JAVASCRIPT:
```
<script type="text/javascript">
    $('#id-image-preview').imagepreview();
</script>
```
