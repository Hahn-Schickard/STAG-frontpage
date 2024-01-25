# STAG
## Sensor Technology Adapter Gateway Project Homepage
### Description 

This repository contains all of the files needed to build a static paged with github or gitlab systems. 

To see the latest STAG homepage version, click the link bellow.

[STAG Homepage](https://hahn-schickard.github.io/STAG-frontpage/)

## Dependencies

 * ruby - it`s best to install it with [rbenv](https://github.com/rbenv/rbenv#readme) tool, which allows to manage multiple ruby instances
 * jekyll

## Visual Studio Code Support

### Recommended Plugins:
 
 * [Jekyll Run](https://marketplace.visualstudio.com/items?itemName=Dedsec727.jekyll-run) - provide automatic page builds and execution

## Building and serving the project

On fresh setups, you will first have to install all of the ruby dependencies, you can do this by running the following in the project root directory: 

```bash
bundle install
```

After dependencies have been installed, you will not need to run this command again, unless you are updating the dependencies. 

To generate the static page and serve it on a webpage, run the following command in project root directory: 

```bash
bundle exec jekyll serve
```

If you want to just generate the html files for the static page, you can run the following: 

```bash
bundle exec jekyll build -d public
```

This will put all of the static page files inside `public` directory.
