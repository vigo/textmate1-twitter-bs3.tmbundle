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

## `lead`
Creates `<p>` with class `lead` or just a class name.

    <p class="lead">...</p>
    
    # just a class name
    class="lead"
    

## `h1` to `h6`

    <h1>...<smal>...</small></h1>
    <h2>...<smal>...</small></h2>
    <h3>...<smal>...</small></h3>
    <h4>...<smal>...</small></h4>
    <h5>...<smal>...</small></h5>
    <h6>...<smal>...</small></h6>

## `list`
4 different list style:

    # unstyled
    <ul class="list-unstyled">
        <li>...</li>
    </ul>

    # unordered
    <ul>
        <li>...</li>
    </ul>

    # inline
    <ul class="list-inline">
        <li>...</li>
    </ul>

    # ordered
    <ol>
        <li>...</li>
    </ol>

## `dl`
Definition lists.

    # description
    <dl>
        <dt>Title</dt>
        <dd>Text</dd>
    </dl>

    # description - horizontal
    <dl class="dl-horizontal">
        <dt>Title</dt>
        <dd>Text</dd>
    </dl>

## `label`
Creates html or just class names.

    <span class="label label-default">Default</span>
    <span class="label label-primary">Primary</span>
    <span class="label label-success">Success</span>
    <span class="label label-info">Info</span>
    <span class="label label-warning">Warning</span>
    <span class="label label-danger">Danger</span>
    
    # class names only
    label-default
    label-primary
    label-success
    label-info
    label-warning
    label-danger

## Typography (Inline Elements)

### `mark`

    <mark>Text</mark>

### `del`

    <del>Text</del>

### `str`
Strikethrough element.

    <s>Text</s>

### `ins`
Inserted text.

    <ins>Text</ins>

### `und`
Underlined text.

    <u>Text</u>

### `sml`
Small text.

    <small>Text</small>

### `aln`
Align to **left**, **center**, **right**, **justify** or **nowrap** via `<p>`
or just class names.

    <p class="text-left">Text</p>
    <p class="text-center">Text</p>
    <p class="text-right">Text</p>
    <p class="text-justify">Text</p>
    <p class="text-nowrap">Text</p>
    
    # class names only
    text-left
    text-center
    text-right
    text-justify
    text-nowrap

### `tra`
Transform to **uppercase**, **lowercase** or **capitalize** or just class names.

    <p class="text-uppercase">Text</p>
    <p class="text-lowercase">Text</p>
    <p class="text-capitalize">Text</p>
    
    # class names only
    text-uppercase
    text-lowercase
    text-capitalize

### `abr`
Abbreviation in 3 different styles:

    <abbr title="attribute">attr</abbr>
    <abbr title="HyperText Markup Language" class="initialism">HTML</abbr>
    <abbr title="Phone Number">P:</abbr>

### `adr`
Addresses tag.

    <address>
        <strong>Company Name</strong><br>
        Line 1<br/>
        Line 2<br/>
        <abbr title="Phone Title">P:</abbr> Phone
    </address>
    <address>
        <strong>Full Name</strong><br>
        <a href="mailto:first.last@gmail.com">first.last@gmail.com</a>
    </address>

### `quo`
Blockquote in 2 different styles.

    <blockquote>
        <p>Text</p>
        <footer>Who/Quote From <cite title="Source Title">Source Title</cite></footer>
    </blockquote>
    
    # reverse
    <blockquote class="blockquote-reverse">
        <p>Text</p>
        <footer>Who/Quote From <cite title="Source Title">Source Title</cite></footer>
    </blockquote>

## Grid

* `con` : Container
* `blo` : Block
* `row` : Row
* `col` : Column (*xs-sm-md-lg*)
* `cel` : Cell (*xs-sm-md-lg*)
* `off` : Offset (*xs-sm-md-lg*)

## Form Elements

* `form` : Creates form and form elements.

## Other

* `code` : 6 different styles (*basic, scrollable, variable, sample out etc...*)
* `img` : Class for responsive image.
* `table` : Table code supports 5 different style.
* `cla` : Contextual classes such as `active`, `success`, `info`, `warning`, `danger`


# Contribute

If you are still using **TextMate1** like me, please do not hesitate to contribute
this mini bundle :)

1. `fork` (https://github.com/vigo/textmate1-twitter-bs3.tmbundle/fork)
2. Create your `branch` (`git checkout -b my-features`)
3. `commit` yours (`git commit -am 'added killer options'`)
4. `push` your `branch` (`git push origin my-features`)
5. Than create a new **Pull Request**!

# Change Log

**2015-07-29**

* Bundle groupings done!

**2015-07-27**

* Form elements added. Buttons are not done yet!

**2015-07-25**

* Contextual classes added.

**2015-07-24**

* `table` added.

**2015-07-23**

* `code` added.

**2015-07-22**

* Description added. `dl`, `dd`, `dt`

**2015-07-19**

* Alignment tags added.
* Text transforms added.
* Address and Blockquote tags added.

**2015-07-13**

* Initial commit