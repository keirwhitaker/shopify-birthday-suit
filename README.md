# Shopify Birthday Suit

Shopify Birthday Suit is an exceedingly bare bones [Shopify](http://shopify.com/) theme intended for use by theme developers as a basis for their own theme development. It is not intended to be used "as is", rather as a building block. Feel free to modify and use for your own means.

## Install

To install the theme download the ZIP file and upload the same ZIP file to your Shopify store. Full details on uploading a theme can be found in the official [Shopify docs](http://docs.shopify.com/themes/the-basics/build-your-theme/upload-theme).

## What's included?

### Assets Folder

The theme layout file references a <code>shop.js</code> and <code>style.css</code> file. Both of these are empty - intentionally. Consequently the theme is rendered with default browser styling and zero JS interactions.

### Config Folder

An empty <code>settings_schema.json</code> file is included. Build on this and add in your own settings. Full info on theme settings can be found in the [Shopify Docs](https://docs.shopify.com/themes/theme-development/storefront-editor/settings-schema).

### Layout Folder

The default layout file <code>theme.layout</code> is included. It includes a reference to the latest release of jQuery and adds some useful classes based on page titles and templates to the body element.

A basic header element is included that includes Liquid code to output the current cart item count along with a link to the checkout.

Finally I have included code to output a simple navigation list using the default link-list titled <code>main-menu</code>.

### Templates

The following are included with a reference to a "main" section each, following the Dawn example. For example <code>product.json</code> contains a reference to <code>main-product.liquid</code> section. Each main section contains just some very basic boilerplate code for you to start developing from.

All of the following templates are intentionally very basic and designed as starting points:

-   <code>404.json</code>
-   <code>article.json</code>
-   <code>blog.json</code>
-   <code>cart.json</code>
-   <code>collection.json</code>
-   <code>index.json</code>
-   <code>list-collections.json</code>
-   <code>page.json</code>
-   <code>password.json</code>
-   <code>product.json</code>
-   <code>search.json</code>

### Locales

There is a basic default English locale included with this theme, but no translation strings.

## Acknowledgements

Shopify Birthday Suit was created by Keir Whitaker with inspiration from the hundreds of talented Shopify theme developers out there sharing their code and ideas. It was updated to Shopify OS2 by Craig Cooper.

-   [keirwhitaker.com](https://keirwhitaker.com)
-   [@keirwhitaker](https://keirwhitaker.com/twitter)
-   [craigcooper.xyz](https://craigcooper.xyz)
