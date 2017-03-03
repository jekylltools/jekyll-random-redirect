# Jekyll Random Redirect

Jekyll page that redirects to a random post using Javascript. Fully compatible with Github Pages.

View a [live demo running on Github Pages](https://jekylltools.github.io/jekyll-random-redirect/random/). The code and configuration for the demo is in the [gh-pages branch](https://github.com/jekylltools/jekyll-random-redirect/tree/gh-pages).

## Usage

1. Add `random.html` to the site.
2. Rebuild the site, then go to the page and you'll be redirected to a random post.

By default, the page will redirect only to posts. You can include pages and documents in collections by adding a setting in `_config.yml`

```
random_redirect:
  include:
  	pages: true
    collections: true
```

## Support

[Open an issue](https://github.com/jekylltools/jekyll-random-redirect/issues) if you have any problems, questions or suggestions for improvement.
