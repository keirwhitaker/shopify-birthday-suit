# Shopify Birthday Suit

Shopify Birthday Suit is an exceedingly bare bones Shopify theme intended for use by theme developers as a basis for their own theme development. It is not intended to be used "as is", rather as a building block. Feel free to modify and use for your own means.

## Install

To install the theme download the ZIP file and upload the same ZIP file to your Shopify store. Full details on uploading a theme can be found in the official [Shopify docs](http://docs.shopify.com/themes/the-basics/build-your-theme/upload-theme).

## What's included?

### Assets Folder

The theme layout file references a <code>shop.js</code> and <code>style.css</code> file. Both of these are empty - intentionally. Consequently the theme is rendered with default browser styling and zero JS interactions.

### Config Folder

I have included a very basic <code>settings_schema.json</code> file. This includes a checkbox to indicate the use of a custom logo along with a file upload to add in a custom logo. Feel free to build on this and add in your own settings. Full info on theme settings can be found in the [Shopify Docs](https://docs.shopify.com/themes/theme-development/storefront-editor/settings-schema).

### Layout Folder

The default layout file <code>theme.layout</code> is included. It includes a reference to the latest release of jQuery and adds some useful classes based on page titles and templates to the body element.

A basic header element is included that includes Liquid code to output the current cart item count along with a link to the checkout.

Finally I have included code to output a simple navigation list using the default link-list titled <code>main-menu</code>.

### Templates

The following are included with basic boilerplate code. For example <code>product.liquid</code> will output the product title and description along with a form detailing all product variants and price. Appropriate HTML is used for headings, paragraphs and lists but are easily customisable.

All of the following templates are intentionally very basic and designed as starting points:

* <code>404.liquid</code>
* <code>article.liquid</code>
* <code>blog.liquid</code>
* <code>cart.liquid</code>
* <code>collection.liquid</code>
* <code>index.liquid</code>
* <code>list-collections.liquid</code>
* <code>page.liquid</code>
* <code>password.liquid</code>
* <code>product.liquid</code>
* <code>search.liquid</code>

## Shopify Resources

* [Shopify Docs](http://docs.shopify.com/) &mdash; Official documentation site
* [Shopify Partner Program](http://shopify.com/partners) &mdash; Sign up to the free Partner program and open as many development stores as you need
* [Shopify Partner Blog](http://shopify.com/partners) &mdash; Regular articles covering ecommerce, design, Shopify themes, freelancing and more

## Acknowledgements

Shopify Birthday Suit was created and is maintained by Keir Whitaker with inspiration from the hundreds of talented Shopify theme developers out there sharing their code and ideas.

* [keirwhitaker.com](http://keirwhitaker.com) &mdash; Links to ecommerce related projects
* [Byte Size Bites](http://keirwhitaker.com/#subscribe) &mdash; - Email newsletter covering tech and culture
* [@keirwhitaker](http://keirwhitaker.com/twitter) &mdash; - Twitter
