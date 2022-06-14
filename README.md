# Startup Open Space Zaragoza 

Prerequisites:
- gem install bundler jekyll
- bundle install

Launch locally:
- bundle exec jekyll serve

Other year sites:
[http://sosz15.cachirulovalley.com/](http://sosz15.cachirulovalley.com/)
[http://sosz16.cachirulovalley.com/](http://sosz16.cachirulovalley.com/)
[http://sosz17.cachirulovalley.com/](http://sosz17.cachirulovalley.com/)
[http://sosz18.cachirulovalley.com/](http://sosz18.cachirulovalley.com/)

Known issues in MacOS X:
- `mkmf.rb can’t find header files for ruby at...` --> Install xcode tools: `xcode-select --install`
- `autoreconf: not found` --> Install automake and deps: `brew install automake && brew install libtool && brew install gettext`
