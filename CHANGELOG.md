<a name="0.4.3"></a>
# 0.4.3 (2016-08-23)

### Bug Fixes

* Fix leaflet maps styles
* Fix license
* Remove tracing of typings (thanks to @GRoguelon)
* Update baContentTop to work with routerLink (thanks to @Kaizeras)
* Fix Chartist to handle data update dynamically (thanks to @bnayalivne)

### Features

* Finally get rid of bower (thanks to @GRoguelon)
* New component [ng2-smart-table](https://akveo.github.io/ng2-smart-table/) - [demo](http://akveo.com/ng2-admin/#/pages/tables/smarttables)


### How to update

* Pull sources from git
* run `npm install`

<a name="0.4.2"></a>
# 0.4.2 (2016-07-28)

### Bug Fixes

* Fix menu and router configuration
* Fix broken dependencies

### Features

* Dependencies updated
* Use @types instead of typings

### BREAKING CHANGES

* Typings were removed, now we use @types instead, more details [here](https://github.com/AngularClass/angular2-webpack-starter#types)

### How to update

* Remove node_modules folder
* Remove typings folder and move all custom typings to package.json
* run `npm install`


<a name="0.4.0"></a>
# 0.4.0 (2016-07-12)

### Bug Fixes

* Make source files generated correctly (thanks to @AlbertXingZhang)
* Fix docker configuration (thanks to @gavinzhou)

### Features

* Angular updated to rc.4
* Dependencies updated accordingly
* Angular Component Router instead or Router Deprecated (thanks to @RonnyRoos)
* New Angular Forms
* Sidebar rewritten, menu merged with routes configuration
* New CKEditor component
* New Image Uploader component
* New Tree view component
* New Rating component
* New Checkbox and multi-checkbox component

### BREAKING CHANGES

* Router is updated to Angular Router Component. Old beta router is removed.
That means that all the routes are moved to the `src/app/app.routes.ts` file. `src/app/app.menu.ts` is also merged into the routes configuration.
More details on how to configure a new route you can find [here](https://akveo.github.io/ng2-admin/articles/015-sidebar/).

* Forms are updated as well. Thus you need to reconfigure all your forms to use new Angular Forms. Checkout the `src/app/pages/login/login.component.ts`component for more details and example.

### How to update

* run `npm install`


<a name="0.3.0"></a>
# 0.3.0 (2016-06-29)

### Bug Fixes

* Sidebar menu angle fixed
* Sidebar menu selected item fixed

### Features

* Angular updated to rc.3
* Dependencies updated accordingly

### How to update

* Remove `node_modules` and `typings` folders 
* run `npm install`

<a name="0.2.1"></a>
# 0.2.1 (2016-06-21)


### Bug Fixes

* Multiple bugfixes

### Features

* Angular updated to rc.2
* Dependencies updated accordingly
* Login page component [Demo](http://akveo.com/ng2-admin/#/login)
* Sign up page component [Demo](http://akveo.com/ng2-admin/#/register)

### BREAKING CHANGES
* `$` renamed to `jQuery` because of name resolution conflicts

### How to update

* Remove `node_modules` and `typings` folders 
* run `npm install`
