# SciRuby meta gem [![Build Status](https://travis-ci.org/SciRuby/sciruby.svg?branch=master)](https://travis-ci.org/SciRuby/sciruby)

Tools for Scientific Computing in Ruby

* [Website](http://sciruby.com)
* [NMatrix](http://github.com/SciRuby/nmatrix)
* [List of scientific gems](http://gems.sciruby.com)
* [Travis CI](https://travis-ci.org/SciRuby/sciruby)

## Description

This gem acts as a meta gem which collects and provides multiple [scientific gems](http://gems.sciruby.com), including numeric and visualization libraries.

## Getting started

Installation:

~~~
gem install sciruby
gem install sciruby-full
~~~

If you want to have a full-blown installation, install `sciruby-full`.

Start a notebook server:

~~~
iruby notebook
~~~

Enter commands:

~~~ ruby
require 'sciruby'
# Scientific gems are auto loaded, you can use them directly!
plot = Nyaplot::Plot.new
sc = plot.add(:scatter, [0,1,2,3,4], [-1,2,-3,4,-5])
plot.show
~~~

Take a look at [gems.yml](gems.yml) or the [list of gems](http://gems.sciruby.com) for interesting gems which are included in `sciruby-full`.

## License

Copyright (c) 2010 onward, The Ruby Science Foundation.

All rights reserved.

SciRuby is licensed under the BSD 3-clause license. See [LICENSE](LICENSE) for details.

## Donations

Support a SciRuby Fellow via [![Pledgie](http://pledgie.com/campaigns/15783.png?skin_name=chrome)](http://www.pledgie.com/campaigns/15783).
