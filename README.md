# Shopify Birthday Suit

Shopify Birthday Suit is an exceedingly bare bones Shopify theme intended for use by theme developers as a basis for their own theme development. It is not intended to be used "as is", rather as a building block. Feel free to modify and use for your own means.

## Install

To install the theme download the ZIP file and upload the same ZIP file to your Shopify store. Full details on uploading a theme can be found in the official Shopify docs: http://docs.shopify.com/themes/the-basics/build-your-theme/upload-theme.

## What's included?

### Assets Folder

The theme references a shop.js and style.css file but these are empty, consequently the theme is rendered with default browser styling. This is intentional.

### Config Folder

I have included a very basic settings.html file. This includes a checkbox to indicate the use of a custom logo along with a file upload to add in a custom logo. Feel free to build on this and add in your own settings. Full info on theme settings can be found in the [Shopify Docs](http://docs.shopify.com/themes/liquid-variables/theme-settings).

### Layout Folder

The default layout file theme.layout is included. It includes a reference to the latest release of jQuery and adds some useful classes based on page titles and templates to the body element.

A basic header element is included that includes Liquid code to output the current cart item count along with a link to the checkout.

Finally I have included code to output a simple navigation list using the default main-menu.

### Templates

The following "micro templates" are included with basic boilerplate code. For example product.liquid will output the product title and description along with a form detailing all product variants and price.

All of the following templates are intentionally very basic and designed as starting points.

* 404.liquid	
* article.liquid	
* blog.liquid	
* cart.liquid	
* collection.liquid	
* index.liquid	
* list-collections.liquid	
* page.liquid	
* product.liquid	
* search.liquid

## Shopify Resources

* [Shopify Docs](http://docs.shopify.com/) 
* [Shopify for Designers](http://shopify.com/fordesigners)

## Acknowledgements

Shopify Birthday Suit was created and is maintained by Keir Whitaker with inspiration from the hundreds of taltented Shopify theme developers sharing code.

[keirwhitaker.com](http://keirwhitaker.com) | [@keirwhitaker](http://keirwhitaker.com)