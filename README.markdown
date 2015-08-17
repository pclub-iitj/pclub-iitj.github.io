Some important links before starting off

1. [Octopress.org](http://octopress.org/docs)
2. [Octopress 3.0](https://github.com/octopress/octopress)
3. [Jekyll](https://github.com/mojombo/jekyll)

For documentation of Octopress please visit the above links.

There are a few additions to the basic octopress code.
There are a few collections that have been added and associated rake tasks are also in place.
See below for more information on these additions.

##News

A collection named "news" has been added so as to be displayed on the homepage of the site.

####How to add news?

A rake task exists for you to create a new news item. It will be created under directory "_news" in the source directory.
```shell
$ rake new_news["News Title"]
```

##Words of wisdom

A collection named "wow" has been added to show some words from our alumni on the WoW page.

####How to add these?

A rake task exists for you to add these. It will be created under directory "_wow" in the source directory.
```shell
$ rake new_wow["Author name"]
```