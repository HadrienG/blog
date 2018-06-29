# blog

this the repo for my blog

## dev

```r
blogdown:::serve_site()
```

## deploy

```r
blogdown::hugo_build()
git add public
git commit -m "new blog post"
git subtree push --prefix public origin gh-pages
```

## licensing

*todo*
