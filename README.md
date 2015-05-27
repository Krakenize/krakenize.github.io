# Krakenize

Krakenize is a multipurpose mobile Backend as a service for providing mobile app developers with a way to link their applications to cloud storage and RESTful API while also providing features such as user management, push notifications, and integration with social networking services.

  - user management
  - push notifications
  - integration with social networking services


### Version
0.3.7

### Tech

Krakenize uses a number of open source projects to work properly:

* [AngularJS] - HTML enhanced for web apps!
* [MongoDB] - awesome NoSQL database
* [Twitter Bootstrap] - great UI boilerplate for modern web apps
* [node.js] - evented I/O for the backend
* [Express] - fast node.js network app framework
* [Gulp] - the streaming build system
* [jQuery] - duh

### Installation

```sh
$ git clone [git-repo-url] Krakenize
$ cd Krakenize
$ npm i -d
$ mkdir -p public/files/{md,html,pdf}
$ gulp build --prod
$ NODE_ENV=production node app
```

### Libraries

Krakenize is currently working with following languages

* Javascript
* Ruby
* Python
* Java
* Obj-c
* CoffeeScript


### Development

Want to contribute? Great!

Krakenize uses Gulp + Webpack for fast developing.
Make a change in your file and instantanously see your updates!

Open your favorite Terminal and run these commands.

First Tab:
```sh
$ node app
```

Second Tab:
```sh
$ gulp watch
```

(optional) Third:
```sh
$ karma start
```

### Todo's

Write Tests
Code Commenting
WebSockets

License
----

MIT


**Free Software, Hell Yeah!**

[node.js]:http://nodejs.org
[Twitter Bootstrap]:http://twitter.github.com/bootstrap/
[jQuery]:http://jquery.com
[express]:http://expressjs.com
[AngularJS]:http://angularjs.org
[Gulp]:http://gulpjs.com
[MongoDB]:http://mongodb.com
