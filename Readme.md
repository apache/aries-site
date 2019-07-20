# Apache Aries Website

This project contains the Apache Aries website.

## Contribute

The concrete repository is on the Apache gitbox but if you want to contribute, you have to clone the Github repository which is a mirror and provide a pull request with your changes. You can find more informations about how to contribute on the community page of the project (http://aries.apache.org/community/gettinginvolved.html).

Clone:

```
git clone https://github.com/apache/aries-site.git
```

## Prerequisites

The website generator used is [Jekyyl](https://jekyllrb.com).

* Install a fully Ruby environment: https://jekyllrb.com/docs/installation/
* Install Jekyyl:

```
gem install jekyll bundler
```

The website theme used is [Bulma](http://www.csrhymes.com/bulma-clean-theme/).

The first time, you have to install Bulma theme files. 
Go into the project root directory and execute:
```
bundle install
```

## Build

Clean up the project:
```
bundle exec jekyll clean
```

Start a local server in development mode:
```
bundle exec jekyll serve
```

Build for deployment production:
```
bundle exec jekyll build
```

