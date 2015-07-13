# Un-Official Twitter Bootstrap 3 Bundle for TextMate1

This bundle supports `v3.3.5` of [Twitter Bootstrap 3](http://getbootstrap.com/getting-started/).

# Available Snippets

Type the snippet shortcut and press `TAB` key!

## Html Template: `html5`

Creates html scaffold (*which is given at BS3 home page.*)

```html
<!DOCTYPE html>
<html lang="en">
    <head>
        <meta charset="utf-8">
        <meta http-equiv="X-UA-Compatible" content="IE=edge">
        <meta name="viewport" content="width=device-width, initial-scale=1">
        <title>Hello World</title>
        <link rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/bootstrap/3.3.5/css/bootstrap.min.css">
        <!-- HTML5 shim and Respond.js for IE8 support of HTML5 elements and media queries -->
        <!-- WARNING: Respond.js doesn't work if you view the page via file:// -->
        <!--[if lt IE 9]>
            <script src="https://oss.maxcdn.com/html5shiv/3.7.2/html5shiv.min.js"></script>
            <script src="https://oss.maxcdn.com/respond/1.4.2/respond.min.js"></script>
        <![endif]-->
    </head>
    <body>
        <div class="container">
            <div class="row">
                <div class="col-xs-12">
                    <h1>Hello <small>world</small></h1>
                </div>
            </div>
        </div>
        <script src="https://ajax.googleapis.com/ajax/libs/jquery/1.11.3/jquery.min.js"></script>
        <script src="https://maxcdn.bootstrapcdn.com/bootstrap/3.3.5/js/bootstrap.min.js"></script>
    </body>
</html>
```

## Typography

* `lead` : `<p>` tag with class `lead`
* `h1` to `h6` : Heading tags + `<small>` tag.
* `list` : Un-styled list.
* `label`

## Typography (Inline Elements)

* `mark` : `<mark>`
* `del` : `<del>`
* `strk` : Strikethrough `<s>`
* `ins` : Inserted `<ins>`
* `und` : Underlined `<u>`
* `sml` : Small `<small>`


## Grid

* `con` : Container
* `blo` : Block
* `row` : Row
* `col` : Column (*xs-sm-md-lg*)
* `cel` : Cell (*xs-sm-md-lg*)
* `off` : Offset (*xs-sm-md-lg*)

## Other

* `img` : Class for responsive image.

# Contribute

If you are still using **TextMate1** like me, please do not hesitate to contribute
this mini bundle :)

1. `fork` (https://github.com/vigo/textmate1-twitter-bs3.tmbundle/fork)
2. Create your `branch` (`git checkout -b my-features`)
3. `commit` yours (`git commit -am 'added killer options'`)
4. `push` your `branch` (`git push origin my-features`)
5. Than create a new **Pull Request**!

# Change Log

**2015-07-13**

* Initial commit