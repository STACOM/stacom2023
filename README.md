# STACOM 2023

This is source code repository for the STACOM 2023 Workshop. If you want to see the website, please go to https://stacom.github.io/stacom2023/.

## Webmaster

To maintain the website, please follow these steps:

1. Make sure you have installed Jekyll on your local system; see: https://jekyllrb.com/

2. Clone the gh-pages branch: 
```
$ git clone -b gh-pages git@github.com:STACOM/stacom2023.git
```

3. Follow Jekyll guidelines to build static pages: https://jekyllrb.com/docs/

4. Commit & push to gh-pages; wait a couple of minutes before GitHub build the page.

## Tips for development

* To run local Jekyll with live update

```
$ jekyll serve -l
```

* For macos, you may need to prepend with

```
$ bundle exec jekyll server -l
```
