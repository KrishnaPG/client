Hypothesis client
=================

[![Build status](https://img.shields.io/travis/hypothesis/client/master.svg)][travis]
[![npm version](https://img.shields.io/npm/v/hypothesis.svg)][npm]
[![#hypothes.is IRC channel](https://img.shields.io/badge/IRC-%23hypothes.is-blue.svg)][irc]
[![BSD licensed](https://img.shields.io/badge/license-BSD-blue.svg)][license]

[travis]: https://travis-ci.org/hypothesis/client
[npm]: https://www.npmjs.com/package/hypothesis
[irc]: https://www.irccloud.com/invite?channel=%23hypothes.is&amp;hostname=irc.freenode.net&amp;port=6667&amp;ssl=1
[license]: https://github.com/hypothesis/client/blob/master/LICENSE

The Hypothesis client is a browser-based tool for making annotations on web
pages. It’s a client for the [Hypothesis web annotation service][service].
It’s used by the [Hypothesis browser extension][ext], and can also be
[embedded directly into web pages][embed].

![Screenshot of Hypothesis client](/images/screenshot.png?raw=true)

[service]: https://github.com/hypothesis/h
[ext]: https://chrome.google.com/webstore/detail/hypothesis-web-pdf-annota/bjfhmglciegochdpefhhlphglcehbmek
[embed]: https://h.readthedocs.io/projects/client/en/latest/publishers/embedding/

Development
-----------

To build, 

````
npm run build

````

To develop / debug, in the root folder run
````
gulp watch
````
then in the test folder, run any web-server and browse to the `index.html` in that folder. For example
````
ws
````
