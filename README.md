# manojmallick.github.io

The GitHub Pages site at <https://manojmallick.github.io/>. It is a one-page redirect to the GitHub profile, [github.com/manojmallick](https://github.com/manojmallick), with a short "Redirecting..." screen for browsers that do not follow the redirect immediately.

## Files

| File | Purpose |
|---|---|
| `index.html` | The redirect page (meta refresh to the GitHub profile, with a styled fallback link) |
| `sitemap.xml` | Sitemap listing the site root, referenced from `robots.txt` |
| `robots.txt` | Allows all crawlers and points to the sitemap |
| `google82f83a2e65d36782.html` | Google Search Console ownership verification. Keep it, or Search Console loses verification |

## Preview locally

```bash
python3 -m http.server 8000     # then open http://localhost:8000
```

Note that opening `index.html` immediately redirects to GitHub because of the meta refresh.

## Deploying

This is a user site: anything pushed to the default branch is published automatically by GitHub Pages (Settings, Pages, deploy from branch). There is no build step.
