# Annotator PouchDB Storage Plugin

[PouchDB](http://pouchdb.com/) provides a fabulous offline-first storage option
with the power to replicate between [Apache CouchDB](http://couchdb.apache.org)
, [IBM Cloudant](http://cloudant.com/), and others.

## [Annotator](http://annotatorjs.org/) + PouchDB

Annotations are often personal things that you *may* want to share later. This
plugin allows you to add offline-first storage into your Annotator-based
extension, app, or UI.

## Usage

```
$ npm install
$ npm run anno # builds annotator.js
$ npm run dev # builds annotator-pouchdb.js
```

You can then open the included `index.html` file and annotate it, or run it
inside a local web server (try `python -m SimpleHTTPServer` if you have python
handy and are in a hurry).

Use `index.html` as a reference for your project.

## Replication

Obviously, there comes a time where you might want these annotations to live
in at least one other place. PouchDB supports the Apache CouchDB Replication
Protocol and you can use the [`.sync()`](http://pouchdb.com/api.html#sync)
method to keep your offline-first copy in sync with a remote Apache CouchDB
or IBM Cloudant database.

## License
Apache 2.0