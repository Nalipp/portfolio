## Portfolio

### Github pages deploy workflow
```
// make changes from master, rebase and push in gh-pages
git add .
git commit -m ''
git push origin master
```

```
// do not make any changes or run the compiler when in the gh-pages branch
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

### Things to do / notes

update github readmes

update project descriptions

add project with learn teach code to portfolio (use linkedIn description

seed data for both node projects

update LinkedIn projects

fix favicon

add ajax
