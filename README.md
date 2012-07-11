# Lokka Theme Bootstrap

This is a theme for [Lokka](http://lokka.org) based on [Twitter Bootstrap](http://twitter.github.com/bootstrap/).

## Install

    $ cd public/theme
    $ git clone git://github.com/tkawa/lokka-theme-bootstrap.git bootstrap

or

    $ git submodule add git://github.com/tkawa/lokka-theme-bootstrap.git public/theme/bootstrap

## Apply Bootswatch flavor

You can easily add [Bootswatch](http://bootswatch.com/) flavor.

Describe to style.scss (keeping the order):

    @import "stylesheets/bootswatch/{flavor}-variables";
    @import "stylesheets/bootstrap";
    @import "stylesheets/responsive";
    @import "stylesheets/bootswatch/{flavor}";


## Screenshot

(This is old one)

![screenshot](https://github.com/tkawa/lokka-theme-bootstrap/raw/master/screenshot.png)
