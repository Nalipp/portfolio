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
### Scss
compile scss to css
```
$ sass stylesheets/main.scss stylesheets/main.css         
  // compile main.scss to main.css

$ sass --watch stylesheets/main.scss:stylesheets/main.css 
  // continuous watch and and compile
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
