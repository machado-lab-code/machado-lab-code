# Machado Lab Website

This is the website for our lab in the Department of
Neuroscience at the University of Pennsylvania.

This website is built with [Jekyll](https://jekyllrb.com/).
It is derived from the great template provided by the
[Allan Lab](https://www.allanlab.org/aboutwebsite.html), at Leiden University,
and the fork written by
[Eric Daoud](https://github.com/ericdaat/research-lab-website).

## Setup

If you want to build the website locally do the following:

``` bash
brew install ruby
gem install bundler jekyll
```

Clone this repository, then install the dependencies:

``` bash
bundle install
```

Run the local webserver with:

``` bash
bundle exec jekyll serve
```

Otherwise, committing to this repository will automatically rebuild
the website and push it to our [subdomain](lab.timmachado.com).

## Contribute

Add new lab members by modifying `team_members.yml`.

Add new publications by modifying `publist.yml`.

Add new news items by modifying `news.yml`.

Make sure to copy the format used for the existing items.

### Edit template

We used [Bootstrap](https://getbootstrap.com/) for designing the website.
Feel free to modify either the [_pages](_pages/) or the
[_layouts](_layouts/) components.



