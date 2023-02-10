# mvrl.github.io

Currently this is used to provide stable URLs for datasets and projects shared by the [Multimodal Vision Research Lab](https://mvrl.cse.wustl.edu/).  For example, the [RasterNet](http://mvrl.github.io/RasterNet) project.

## Adding a Redirect

If you would like to add a new stable URL, just add the corresponding file in _redirect.

## Required software

The site generator is implemented in [Ruby](https://www.ruby-lang.org/en/). We use [Bundler](https://bundler.io/) to manage library dependencies. The       following
commands may be useful:

- `gem install --user-install  bundler`: installs Bundler if needed
- `bundle install`: installs packages defined in Gemfile (should be run from root directory)
- `bundle update`: updates packages

You may need to install a ruby environment since Apple doesn't keep the default install updated:
https://utpalkumar.medium.com/how-to-install-jekyll-on-apple-m1-macbook-c87894b7fc70.

## Contact

Maintained by [Nathan Jacobs](http://jacobsn.github.io).
