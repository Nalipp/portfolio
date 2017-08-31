## Portfolio

### Github pages deploy workflow
```
git add .
git commit -m ''
git push origin master
```

```
git checkout gh-pages
git rebase master
git push origin gh-pages
git checkout master
```
### Comple scss to css
```
$ sass stylesheets/main.scss stylesheets/main.css
$ sass --watch stylesheets/main.scss:stylesheets/main.css // continuous wach
```

### Things to do

clean data for d3 graphic

add tooltips hovers to d3 graphic

update resume and create downloadable pdf
