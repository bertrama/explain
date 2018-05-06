# Explain parser

Parses a solr xml select response with explainDebug turned on.  Optionally, explainOther may be used, too. Read README.txt for more info.

## Status

* Fixed some asset configuration.
* Fixed some gem dependency.
* Fixed some parsing.
* Fixed problem with ids containing non-alphanumeric characters.

* There may be more parsing issues.
* Still on an ancient and unsupported version of rails.
* Some asset issues need to be reversed for later versions or rails.
* Fix with ids is not ideal.

## Installing and running

The rails app is in `explainapp`.

```bash
git clone this repo
cd explainapp
bundle install --path .bundle
bundle exec rake db:migrate
bundle exec rackup -o 127.0.0.1
```

The default /admin account is `admin@example.com` / `password`

Read INSTALL.txt for more info.
