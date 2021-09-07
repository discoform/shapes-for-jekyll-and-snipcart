# Shapes

![Shapes Screenshot](https://repository-images.githubusercontent.com/142916390/3a3e76ba-4974-40e3-99ec-336976270796)

Shapes is a simple e-commerce theme for [Jekyll](https://jekyllrb.com/) and [Snipcart](https://snipcart.com/). Best used for small shops with limited inventory.

## Getting Started

__You'll need a [Snipcart](https://snipcart.com/) account to use this theme.__ All the development is set up to support adding items to your cart from the product page. Simply add your [Snipcart API Key](https://app.snipcart.com/dashboard/account/credentials) to the _config.yml file and create your products.

[VIEW THE DEMO](https://shapes-for-jekyll-and-snipcart.netlify.app)

Issues and enhancements are welcome. [You can find the project board here](https://github.com/discoform/shapes-for-jekyll-and-snipcart/projects/1).

---


## Plugins

### [Jekyll SEO Tag](https://github.com/discoform/shapes-for-jekyll-and-snipcart/projects/1)

A Jekyll plugin to add metadata tags for search engines and social networks to better index and display your site's content.


### [Jekyll Sitemap](https://github.com/jekyll/jekyll-sitemap)
Jekyll plugin to silently generate a sitemaps.org compliant sitemap for your Jekyll site.


### [Jekyll Autoprefixer](https://github.com/vwochnik/jekyll-autoprefixer)
This plugin provides simple autoprefixer support for Jekyll. To ensure compatibility with the latest version of JekyllI've clamped the `execjs` gem to version 2.7.0, [per this issue](https://github.com/ai/autoprefixer-rails/issues/160)

---

## Data files

In the `_data` directory you'll find files to handle the following site components and features:

- `siteNavigation.yml` (header navigation and footer navigation)
- `siteSocial.yml` (Social sharing and Social following options)

---

## Contact Form

A simple HTML contact form with the [Netlify data attribution](https://docs.netlify.com/forms/setup/) is added. This should work out of the box if you're using Netlify for hosting, otherwise you can replace this with your own solution.
