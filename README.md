# Render Deploy Example

This is a deploy following the example in https://render.com/docs/deploy-rails

This is using Rails 7, so to have bootstrap work, I needed to create the app with the following flags

``` 
rails new mysite --database=postgresql -j esbuild --css bootstrap 
```


