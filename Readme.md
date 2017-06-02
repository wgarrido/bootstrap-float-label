# Floating label for bootstrap 3

![](https://media.giphy.com/media/3oKIPqWzkif1ppxGG4/giphy.gif)

### Prerequisites

What things you need to install the software and how to install them

```
Bootstrap 3
Jquery
```

### Usage

Include plugin's CSS and JS:

```html
<link rel="stylesheet" href="bootstrap-float-label.css">
<script src="bootstrap-float-label.js"></script>
```

Add class "float-label" to your form-group

```html
 <form>
    <div class="form-group float-label">
        <label for="exampleInputEmail1">Email</label>
        <input type="email" class="form-control" id="exampleInputEmail1" >
    </div>
</form>
```

Call the plugin:

```html
$.bootstrapFloatLabel();
```

## Authors

* **William Garrido** - *Initial work* 


