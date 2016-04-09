Arlin App with Nova by Michi
============================

Introduction
------------

> Full stack application for Arlin, with [Telescope Nova](https://github.com/TelescopeJS/Telescope/tree/nova).

This application is using Node.js and npm. Please follow the getting started guide first. This particular app is using Meteor and its internal MongoDB.

The broader Technical Documentation that isn't concretely about only the application either the backend or frontend itself, is in the [parent repo (asde-michi)](https://github.com/gunadarma-academy/asde-michi#technical-documentation).

*  *  *  *  *  *  *  *  *  *  *  *  *  *  *  *  *  *  *  *

Getting Started
---------------

### Requirements

+ Terminal and shell (bash or [zsh](http://www.zsh.org))
+ [Git](http://git-scm.com) v2.x
+ Modern code editor ([Vim](http://vim.org), [Atom](https://atom.io), [Sublime](https://sublimetext.com))
+ Modern web browser (Google Chrome or Firefox)
+ HTTP client app like [cURL](https://curl.haxx.se) or [Postman](https://getpostman.com)
+ [Node.js](http://nodejs.org) and [Meteor](http://meteor.com): JavaScript platform and a full stack framework, currently Node `v0.10.x` and Meteor `v1.3`.
+ [React.js](https://facebook.github.io/react) knowledge, a UI library.
+ No CSS framework here. Choose your own in the frontend you build.

### Installation

+ Install Node.js from your prefered way, or from <http://nodejs.org>
  + It's also recommended to [use Node Version Manager (nvm)](https://github.com/creationix/nvm)
+ Install required npm packages/modules with `npm install` within this repo
+ Install pm2 globally (`npm install -g pm2`)
+ Install mupX globally (`npm install -g mupx`)

### Development

+ Fork the repository
+ Create your feature branch (`git checkout -b feature-name`)
+ Make your changes with your editor (`vim` or `atom` or `sublime`)
+ Commit your changes (`git commit -a`)
+ Push to the branch (`git push origin feature-name`)
+ Create new Pull Request

### Usage and Deployment

Use `meteor --settings settings.json` to run the app. Access `http://{host}:{port}/{api_route}` or that already shown in the prompt to view.

For smooth deployment, notice that you should have a proper access to the server. It's recommended to use SSH key that is already added/registered there. You might want to use `ssh-copy-id username@xx.xx.xx.xx` first.

*  *  *  *  *  *  *  *  *  *  *  *  *  *  *  *  *  *  *  *

License
-------

Arlin App by Michi is Copyright (c) 2016 Michi Team and licenced under the MIT licence. All rights not explicitly granted in the MIT license are reserved. See the parent [LICENSE.markdown](https://github.com/gunadarma-academy/asde-michi/blob/master/LICENSE.markdown) file for more details.
