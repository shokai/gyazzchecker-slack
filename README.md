GyazzChecker-Slack
==================
https://github.com/shokai/gyazzchecker-slack

* check Gyazz.com
* notify [Slack.com](https://slack.com)

Requirements
------------

* Ruby 2.0+
* MongoDB 2.0+


Install Dependencies
--------------------

    % gem install bundler
    % bundle install


Setup
-----

edit config.yml

    % cp sample.config.yml config.yml


Run
---

    % ruby bin/gyazzchecker.rb --help
    % ruby bin/gyazzchecker.rb --silent
    % ruby bin/gyazzchecker.rb --limit 30 --interval 5



Contributing
------------
1. Fork it
2. Create your feature branch (`git checkout -b my-new-feature`)
3. Commit your changes (`git commit -am 'Add some feature'`)
4. Push to the branch (`git push origin my-new-feature`)
5. Create new Pull Request