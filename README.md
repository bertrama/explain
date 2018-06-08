# Explain parser

Parses a solr xml select response with explainDebug turned on.  Optionally, explainOther may be used, too. Read README.txt for more info.

## Status

* Fixed some asset configuration.
* Fixed some gem dependencies.
* Fixed problem with ids containing non-alphanumeric characters.  Implementation for ids is not ideal.
* Fixed some parsing. There may be more parsing issues.
* Added a route for an xml file upload:  /explains/new-from-file

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
