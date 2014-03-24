State of the Pouch

*what is PouchDB*

CouchDB compatable DB in JavaScript

Browser AND Node

LevelDB in node

IndexedDB and WebSQL in Browser

in cordova, it can use the sqlite plugin

replicates to and from couchdb

including long polling

*status*

vary large push since couchdb conf

new committers including Nolan Lawson and Ian Goodacre

Highlights include

*1.0.0*

goodby grunt

hello package.json scripts object

Use Browserify

*1.1.0*

plugins live in other repos

works in a web worker

massive internal reorg

*2.0.0*

no more allDbs

qunit can die in a fire, we're using mocha

use prototype

PouchDB emits events when dbs are created/destroyed

Promises (and better async errors even with callbacks)

total_rows is now correct in all docs

bunch of improvements for mobile

*2.1.0*

caching queries!

live instead of continuous

db.events

*future*

streams? (might not be in core)

get tests working with big couch