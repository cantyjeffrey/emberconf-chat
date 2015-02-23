# EmberConf Chat

This is a demonstration application to accompany my talk entitled "Building Real-time Applications in Ember", which I will be giving on March 4, 2015 at [EmberConf][] in Portland, Oregon.

[EmberConf]: http://emberconf.com/ "EmberConf 2015"

## Getting up and running

* Clone [stevekinney/socketry-server][server]
	* Install the dependencies with `npm install`
	* Fire up the server with `npm start`
* Clone [stevekinney/emberconf-chat][cc] (this repository) and checkout the `websocket-server` branch
	* Install the dependencies with `npm install && bower install`
	* Fire up the server with `ember server`

[cc]: https://github.com/stevekinney/emberconf-chat/tree/websocket-service

This project relies on [stevekinney/socketry-server][server] and is loosely based on [stevekinney/socketry-client][client], which I used in an earlier version of this talk given at [Denver Ember.js in November of 2014][denver].

[server]: https://github.com/stevekinney/socketry-server
[client]: https://github.com/stevekinney/socketry-client
[denver]: http://www.meetup.com/Ember-js-Denver/events/215907412/
