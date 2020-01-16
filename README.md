# netlify notes

## netlify cms
Put the netlify CMS single page app in the route `/admin`. It allows you to save content to your repository via github.

After logging in, the app will redirect you to the base page `/public/index.html` but it will add some query parameters. This is why you need a `netlify identity` widget on your home page. It will parse the query params that were set.

