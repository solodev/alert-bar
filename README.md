# alert-bar
In some cases, websites require an alert box at the top of the page if there is something urgent website visitors must know. If there is an outage in a company's services, a natural disaster, or a very important message, perhaps regarding website maintenance, an alert box is the way to go. In this article, [Solodev](https://www.solodev.com/) provides you with a tutorial on adding an alert box to your website.

## Tutorial

For detailed instructions, view Solodev's [Adding an Alert Bar to your Website](https://www.solodev.com/blog/web-design/adding-an-alert-bar-to-your-website.stml) article.

## Demo

Try out a working example on [JSFiddle](https://jsfiddle.net/solodev/5ryb1g0e/).

## HTML

The alert bar has the following basic HTML markup.

```
<div class="alert alert-info alert-dismissible" role="alert">
   <button aria-label="Close" class="close" data-dismiss="alert" type="button"><span aria-hidden="true">×</span></button>
   <p>
      To learn more about lorem ipsum. Click lorem ipsum <a href="/">here</a>
   </p>
</div>
<section class="container ct-isotope-gallery__container">
<div class="row">
   <div class="col-md-10 col-md-offset-1">
      <h2 class="ct-section-header">
         WELCOME<span class="ct-section-header__separator" role="separator"><img alt="Separator" src="https://www.solodev.com/assets/design/separator.png"></span>
      </h2>
      <p class="text-center">
         Programming not required. WebCorpCo enables marketers to manage their entire stack in one place without needing the ability to program as all code is automatically written by webcorpco.
      </p>
   </div>
</div>
```

## CSS

All required CSS is in the file alert-bar.css

## External Includes

This tutorial contains the following third party resources.

```
<link href="https://maxcdn.bootstrapcdn.com/bootstrap/3.3.6/css/bootstrap.min.css" rel="stylesheet">
<link rel="stylesheet" href="alert-bar.css">
<script src="https://code.jquery.com/jquery-2.2.0.min.js" type="text/javascript"></script>
<script src="https://maxcdn.bootstrapcdn.com/bootstrap/3.3.6/js/bootstrap.min.js"></script>
```
