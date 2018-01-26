## Portfolio

### Github pages deploy workflow
```
// make changes from master and rebase and push in gh-pages
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
### Scss
compile scss to css
```
  // compile main.scss to main.css
$ sass stylesheets/main.scss stylesheets/main.css         

  // continuous watch and and compile
$ sass --watch stylesheets/main.scss:stylesheets/main.css 
```
import files without http request required in a css @import
```
// _reset.scss 
  (the '_' signals the file is a partial)

// base.scss
@import 'reset';
```

### Things to do

clean data for d3 graphic

add tooltips hovers to d3 graphic

update resume and create downloadable pdf
