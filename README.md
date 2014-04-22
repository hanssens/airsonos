AirSonos
========

Server to add AirPlay support to a Sonos network.

Installation
------------

AirSonos requires [node.js](http://nodejs.org) installed to run.

Install via [npm](https://www.npmjs.org)
```
$ npm install airsonos -g
```

Install latest via source
```
$ git clone https://github.com/stephen/airsonos.git
$ cd airsonos
$ npm install -g
```

Example usage
-------------
```
$ airsonos
Searching for Sonos devices on network...
Setting up AirSonos for Playroom {172.17.105.103:1400}
```

Changelog
---------

##### 0.0.9
- Changed AirPlay display name to reflect Sonos Zone name (see issue #5)

##### 0.0.8
- Upped to [NodeTunes](https://github.com/stephen/nodetunes) version 0.0.10

##### 0.0.7
- Fixed issue where Sonos Bridge shows up as a playable device (see https://github.com/bencevans/node-sonos/issues/29)

##### 0.0.6
- Upped to [NodeTunes](https://github.com/stephen/nodetunes) version 0.0.9 (solves issue #1)

##### 0.0.5
- Added support for global installation

##### 0.0.4
- Fixed EADDRINUSE re-connection bug

##### 0.0.3
- Changed to nodetunes version 0.0.7 callback pattern
