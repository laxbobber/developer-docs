---
id: overview
title: Overview
custom_edit_url: https://github.com/Yoast/developer-docs/edit/master/docs/features/xml-sitemaps.md
---
This documentation describes how we represent [schema.org](http://schema.org/) integration in [Yoast SEO](https://yoast.com/wordpress/plugins/seo/) , as well as our broader approach to structured data.
## Overview
* Our [specification document](functional-specification.md) explains the high level workings of our schema.org output. It’s not simple, so take your time and read through how pieces are connected to each other.
* Our [pieces documentation](pieces.md) describes the specific logic and output of each node which we construct in our graph. It’s a good place to read up if you have questions about specific parts of our approach.
* All of our output can be changed, managed and extended using our [Schema API](api.md) . Please follow our [integration guide](integration-guidelines.md) when you’re building on that API.

## Output per plugin
Our own plugins use and build upon our API and documentation, as detailed here.

* [Yoast SEO for WordPress](plugins/yoast-seo.md) 
* [Local SEO for WordPress](plugins/local-seo.md) 
* [Yoast WooCommerce SEO](plugins/woocommerce-seo.md) 
* [News SEO for WordPress](plugins/news-seo.md) 
* [Video SEO for WordPress](plugins/video-seo.md) 

## You’re a developer and unsure where to start?
Want to extend, integrate or modify our schema.org output? We recommend reading in this order:

1. [Our Schema specification](functional-specification.md) 
2. [Our integration guide](integration-guidelines.md) 
3. [Our Schema API docs](api.md) 