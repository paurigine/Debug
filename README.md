# Debug

## JS

### Ajax

empty response
> 
```js
$.ajax({},
error: function(jqXHR, textStatus, errorThrown){
    alert(errorThrown);
});
```

## PHP

### Laravel


> empty querry

> ```Argument 1 passed to Symfony\\Component\\HttpFoundation\\Response::setContent() must be of the type string or null, object given, called in
> C:\\laragon\\www\\Ginepop\\vendor\\laravel\\framework\\src\\Illuminate\\Http\\Response.php on line 72"```
```php
return categories::where('state', '0');
```
```php
return categories::where('state', '0')->get();
```