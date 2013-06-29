Extract rubygems into `./rubygems/` and install into `vendor/ruby` with choice of ruby:

    make RUBY=/usr/bin/ruby

Then use `bin/gem` to install bundler:

    bin/gem install bundler
    
Then bundle your project with `bin/bundle`:

    bin/bundle --path vendor/bundle
