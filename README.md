# Medic Mobile Documentation

This is a separate app because of its size, since we don't need to increase the
build and replication time of the main app by weighing it down with media
files.

This site was created using the [Garden Baseline
App](https://github.com/garden20/baseline-garden-app/) as a starting point.

## Editing

Documentation lives in `md` directory and should be editable locally, so links
should be relative and allow for use of a Markdown tool like
[Mou](http://mouapp.com/) or [MarkdownPad](http://markdownpad.com/).

All the links within the documetnation should be relative.  So you can start by
opening [md/index.md](md/index.md) and go from there. Each section should have a directory
and corresponding `img` directory for images.

You can also edit the files directly in Github, assuming you have privileges.

## Deploy

Requires [CouchDB](http://couchdb.apache.org/), [NodeJS](http://nodejs.org/)
and [Kanso](http://kan.so/). Then:

* `git clone`
* `kanso push http://localhost:5984/medic-docs`

