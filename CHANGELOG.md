2.5.0
=====

* [✓] Catch all routes, fixes #1
* [➠] Updated Gems

2.4.4
=====

* [➠] Updated Gems

2.4.3
=====

* [➠] Updated Gems

2.4.2
=====

* [➠] Added metadata to Gemspec

2.4.1
=====

* [➠] Updated Gems

2.4.0
=====

* [➠] Updated RuboCop configuration
* [➠] Updated Sinatra

2.3.2
=====

* [➠] Freeze mutable objects assigned to constants

2.3.1
=====

* [➠] Moved Rake tasks out of library
* [➠] Updated Gems

2.3.0
=====

* [✖] Removed logging out of engine, should be configured via `config.ru`
* [✓] Use `Sinatra::Base` instead of `Sinatra::Application`
* [➠] Improved `debug` view

2.2.0 (Yanked)
==============

* [➠] First release on RubyGems
* [➠] Debug information can be enabled / disabled
* [➠] Formatted debug information

2.1.0
=====

* [➠] Updated README
* [➠] Refactored engine code
* [✚] Added `debug` route
* [✖] Removed `config` gem, `sinatra/config_file` is perfectly adequate

2.0.1
=====

* [➠] Response with 400 when revision is not valid

2.0.0
=====

* [➠] Renamed `index_id` to  `key_prefix`
* [➠] Added `active_content_suffix` and `revision` options
* [➠] Compatibility with the latest version of `ember-cli-deploy-redis`

1.0.1
=====

* [✓] Fixed version require

1.0.0
=====

* [✚] Added specs
* [➠] Configured Travis CI, Code Climate, Test Coverage, RuboCop and Gemnasium
* [❶] First commit (born from Bitaculous Booster)