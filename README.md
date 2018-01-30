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

link top technologies to code repos
1. find and open code repos in tabs
2. update html

check all links

spell check

update resume 

fix favicon

update github favorite repos

seed data for both node projects

update LinkedIn projects
