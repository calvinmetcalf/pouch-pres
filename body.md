State of the Pouch

Calvin Metcalf

[@cwmma](https://twitter.com/CWMma)

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

new committees including Nolan Lawson and Ian Goodacre

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

qunit can die in a fire, we're using mocha

use prototype

PouchDB emits events when dbs are created/destroyed

Promises (and better async errors even with callbacks)

bunch of improvements for mobile/websql

did a bunch of work on the levelDB adapter


*2.1.0*

caching queries!

instead of continuous, live! (Which I can spell)

db.events

*future*

streams? (might not be in core)

get tests working with big couch

more efficient replication

your idea?

**lessons**

BROWSERIFY IS AMAZING

I would rather get kicked in the crouch then go back to AMD

Seriously

Safari is the new IE

Except

Old android is even worse

we get bug reports related to only supporting es3

firefox/chrome has es6 stuff now

levelDB rocks

writing code is easy, writing tests are hard

don't use grunt/gulp/jake/cake

just put a scripts object into your package.json

[pouchdb.com](http://pouchdb.com/)