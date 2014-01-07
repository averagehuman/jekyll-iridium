# jekyll-iridium

A basic functional [Jekyll][jekyll] theme using Zurb Foundation 5

See the Jekyll documentation for details about building a static site.

## Python build harness

There is an optional and non-standard build harness that uses Python
and [Buildout][buildout].

### Usage

Install the Jekyll gem with the command

    make configure

And if that went well, build the static site with

    make build

Or combine these two with

    make all

Once built, view the site by launching a local webserver

    make serve

and visiting http://127.0.0.1:4000

### Requirements

Tested on Ubuntu 12.04 with Ruby 1.8.7 and Python 2.7.

Jekyll requires certain extensions to be built and this requires

    apt-get ruby-dev


[jekyll]: http://jekyllrb.com
[buildout]: https://pypi.python.org/pypi/zc.buildout/2.2.1

