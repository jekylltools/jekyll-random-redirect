# Jekyll Random Redirect

Jekyll page that redirects to a random post using Javascript. Fully compatible with Github Pages.

## Usage

1. Add `random.html` to the site.
2. Rebuild the site, then navigate to the page and you'll be redirected to a random post.

The random page will only redirect to posts by default. You can include pages and documents from collections by adding a setting in `_config.yml`

```
random_redirect:
  include:
  	pages: true
    collections: true
```

## Support

[Open an issue](https://github.com/jekylltools/jekyll-random-redirect/issues) if you have any problems, questions or suggestions for improvement.
