yo-gulp-webapp-poc ansaini$ yo gulp-webapp
? ==========================================================================
We're constantly looking for ways to make yo better! 
May we anonymously report usage statistics to improve the tool over time? 
More info: https://github.com/yeoman/insight & http://yeoman.io
========================================================================== No

     _-----_
    |       |    .--------------------------.
    |--(o)--|    |  'Allo 'allo! Out of the |
   `---------´   |    box I include HTML5   |
    ( _´U`_ )    | Boilerplate, jQuery, and |
    /___A___\    | a gulpfile to build your |
     |  ~  |     |           app.           |
   __'.___.'__   '--------------------------'
 ´   `  |° ´ Y ` 

? What more would you like? Sass, Bootstrap, Modernizr
   create bower.json
   create package.json
   create gulpfile.babel.js
   create .babelrc
   create .gitignore
   create .gitattributes
   create .bowerrc
   create .editorconfig
   create app/favicon.ico
   create app/apple-touch-icon.png
   create app/robots.txt
   create app/styles/main.scss
   create app/scripts/main.js
   create app/index.html
   create test/spec/test.js
   create test/index.html


I'm all done. Running npm install & bower install for you to install the required dependencies. If this fails, try running the command yourself.


npm WARN deprecated graceful-fs@3.0.8: graceful-fs version 3 and before will fail on newer node releases. Please update to graceful-fs@^4.0.0 as soon as possible.
npm WARN deprecated lodash@1.0.2: lodash@<3.0.0 is no longer maintained. Upgrade to lodash@^4.0.0.
npm WARN deprecated graceful-fs@1.2.3: graceful-fs version 3 and before will fail on newer node releases. Please update to graceful-fs@^4.0.0 as soon as possible.
npm WARN deprecated npmconf@2.1.2: this package has been reintegrated into npm and is now out of date with respect to npm
npm WARN deprecated graceful-fs@2.0.3: graceful-fs version 3 and before will fail on newer node releases. Please update to graceful-fs@^4.0.0 as soon as possible.
npm WARN prefer global node-gyp@3.3.0 should be installed with -g

> fsevents@1.0.8 install /Users/ansaini/code/mine/tests/yo-gulp-webapp-poc/node_modules/fsevents
> node-pre-gyp install --fallback-to-build

[fsevents] Success: "/Users/ansaini/code/mine/tests/yo-gulp-webapp-poc/node_modules/fsevents/lib/binding/Release/node-v47-darwin-x64/fse.node" is installed via remote

> bufferutil@1.2.1 install /Users/ansaini/code/mine/tests/yo-gulp-webapp-poc/node_modules/bufferutil
> node-gyp rebuild

  CXX(target) Release/obj.target/bufferutil/src/bufferutil.o
  SOLINK_MODULE(target) Release/bufferutil.node

> utf-8-validate@1.2.1 install /Users/ansaini/code/mine/tests/yo-gulp-webapp-poc/node_modules/utf-8-validate
> node-gyp rebuild

  CXX(target) Release/obj.target/validation/src/validation.o
  SOLINK_MODULE(target) Release/validation.node

> node-sass@3.4.2 install /Users/ansaini/code/mine/tests/yo-gulp-webapp-poc/node_modules/node-sass
> node scripts/install.js

Binary downloaded and installed at /Users/ansaini/code/mine/tests/yo-gulp-webapp-poc/node_modules/node-sass/vendor/darwin-x64-47/binding.node

> spawn-sync@1.0.15 postinstall /Users/ansaini/code/mine/tests/yo-gulp-webapp-poc/node_modules/spawn-sync
> node postinstall


> node-sass@3.4.2 postinstall /Users/ansaini/code/mine/tests/yo-gulp-webapp-poc/node_modules/node-sass
> node scripts/build.js

` /Users/ansaini/code/mine/tests/yo-gulp-webapp-poc/node_modules/node-sass/vendor/darwin-x64-47/binding.node ` exists. 
 testing binary.
Binary is fine; exiting.

> optipng-bin@3.1.0 postinstall /Users/ansaini/code/mine/tests/yo-gulp-webapp-poc/node_modules/optipng-bin
> node lib/install.js

  ✔ optipng pre-build test passed successfully

> jpegtran-bin@3.0.6 postinstall /Users/ansaini/code/mine/tests/yo-gulp-webapp-poc/node_modules/jpegtran-bin
> node lib/install.js

  ✔ jpegtran pre-build test passed successfully

> gifsicle@3.0.3 postinstall /Users/ansaini/code/mine/tests/yo-gulp-webapp-poc/node_modules/gifsicle
> node lib/install.js

  ✔ gifsicle pre-build test passed successfully
/Users/ansaini/code/mine/tests/yo-gulp-webapp-poc
├─┬ babel-core@6.6.0 
│ ├─┬ babel-code-frame@6.6.0 
│ │ ├── esutils@2.0.2 
│ │ ├── js-tokens@1.0.2 
│ │ ├─┬ line-numbers@0.2.0 
│ │ │ └── left-pad@0.0.3 
│ │ └─┬ repeating@1.1.3 
│ │   └── is-finite@1.0.1 
│ ├─┬ babel-generator@6.6.0 
│ │ ├── detect-indent@3.0.1 
│ │ ├── is-integer@1.0.6 
│ │ └── trim-right@1.0.1 
│ ├── babel-helpers@6.6.0 
│ ├── babel-messages@6.6.0 
│ ├─┬ babel-register@6.6.0 
│ │ ├── core-js@2.1.3 
│ │ ├─┬ home-or-tmp@1.0.0 
│ │ │ └── os-tmpdir@1.0.1 
│ │ ├─┬ mkdirp@0.5.1 
│ │ │ └── minimist@0.0.8 
│ │ └─┬ source-map-support@0.2.10 
│ │   └─┬ source-map@0.1.32 
│ │     └── amdefine@1.0.0 
│ ├─┬ babel-runtime@5.8.35 
│ │ └── core-js@1.2.6 
│ ├── babel-template@6.6.0 
│ ├─┬ babel-traverse@6.6.0 
│ │ ├── globals@8.18.0 
│ │ └─┬ invariant@2.2.0 
│ │   └── loose-envify@1.1.0 
│ ├─┬ babel-types@6.6.0 
│ │ └── to-fast-properties@1.0.1 
│ ├── babylon@6.6.0 
│ ├── convert-source-map@1.2.0 
│ ├─┬ debug@2.2.0 
│ │ └── ms@0.7.1 
│ ├── json5@0.4.0 
│ ├── lodash@3.10.1 
│ ├─┬ minimatch@2.0.10 
│ │ └─┬ brace-expansion@1.1.3 
│ │   ├── balanced-match@0.3.0 
│ │   └── concat-map@0.0.1 
│ ├── path-exists@1.0.0 
│ ├── path-is-absolute@1.0.0 
│ ├── private@0.1.6 
│ ├── shebang-regex@1.0.0 
│ ├── slash@1.0.0 
│ └── source-map@0.5.3 
├─┬ babel-preset-es2015@6.6.0 
│ ├── babel-plugin-check-es2015-constants@6.5.0 
│ ├── babel-plugin-transform-es2015-arrow-functions@6.5.2 
│ ├── babel-plugin-transform-es2015-block-scoped-functions@6.5.0 
│ ├── babel-plugin-transform-es2015-block-scoping@6.6.0 
│ ├─┬ babel-plugin-transform-es2015-classes@6.6.0 
│ │ ├── babel-helper-define-map@6.6.0 
│ │ ├── babel-helper-function-name@6.6.0 
│ │ ├── babel-helper-optimise-call-expression@6.6.0 
│ │ └── babel-helper-replace-supers@6.6.0 
│ ├── babel-plugin-transform-es2015-computed-properties@6.5.2 
│ ├── babel-plugin-transform-es2015-destructuring@6.6.0 
│ ├── babel-plugin-transform-es2015-duplicate-keys@6.6.0 
│ ├── babel-plugin-transform-es2015-for-of@6.6.0 
│ ├── babel-plugin-transform-es2015-function-name@6.5.0 
│ ├── babel-plugin-transform-es2015-literals@6.5.0 
│ ├─┬ babel-plugin-transform-es2015-modules-commonjs@6.6.0 
│ │ └── babel-plugin-transform-strict-mode@6.5.2 
│ ├── babel-plugin-transform-es2015-object-super@6.5.0 
│ ├─┬ babel-plugin-transform-es2015-parameters@6.6.0 
│ │ ├─┬ babel-helper-call-delegate@6.6.0 
│ │ │ └── babel-helper-hoist-variables@6.5.0 
│ │ └── babel-helper-get-function-arity@6.5.0 
│ ├── babel-plugin-transform-es2015-shorthand-properties@6.5.0 
│ ├── babel-plugin-transform-es2015-spread@6.5.2 
│ ├─┬ babel-plugin-transform-es2015-sticky-regex@6.5.0 
│ │ └── babel-helper-regex@6.6.0 
│ ├── babel-plugin-transform-es2015-template-literals@6.6.0 
│ ├── babel-plugin-transform-es2015-typeof-symbol@6.6.0 
│ ├─┬ babel-plugin-transform-es2015-unicode-regex@6.5.0 
│ │ └─┬ regexpu-core@1.0.0 
│ │   ├── regenerate@1.2.1 
│ │   ├── regjsgen@0.2.0 
│ │   └─┬ regjsparser@0.1.5 
│ │     └── jsesc@0.5.0 
│ └─┬ babel-plugin-transform-regenerator@6.6.0 
│   └── babel-plugin-syntax-async-functions@6.5.0 
├─┬ browser-sync@2.11.1 
│ ├── async-each-series@0.1.1 
│ ├─┬ browser-sync-client@2.4.1 
│ │ ├── etag@1.7.0 
│ │ └── fresh@0.3.0 
│ ├─┬ browser-sync-ui@0.5.18 
│ │ ├── connect-history-api-fallback@1.1.0 
│ │ ├─┬ stream-throttle@0.1.3 
│ │ │ ├─┬ commander@2.9.0 
│ │ │ │ └── graceful-readlink@1.0.1 
│ │ │ └── limiter@1.1.0 
│ │ └─┬ weinre@2.0.0-pre-I0Z7U9OV 
│ │   ├─┬ express@2.5.11 
│ │   │ ├─┬ connect@1.9.2 
│ │   │ │ └── formidable@1.0.17 
│ │   │ ├── mime@1.2.4 
│ │   │ ├── mkdirp@0.3.0 
│ │   │ └── qs@0.4.2 
│ │   ├─┬ nopt@3.0.6 
│ │   │ └── abbrev@1.0.7 
│ │   └── underscore@1.7.0 
│ ├── bs-recipes@1.1.0 
│ ├─┬ chokidar@1.4.1 
│ │ ├─┬ anymatch@1.3.0 
│ │ │ └── arrify@1.0.1 
│ │ ├── async-each@0.1.6 
│ │ ├─┬ fsevents@1.0.8 
│ │ │ └─┬ node-pre-gyp@0.6.21 
│ │ │   ├─┬ mkdirp@0.5.1 
│ │ │   │ └── minimist@0.0.8 
│ │ │   ├─┬ nopt@3.0.6 
│ │ │   │ └── abbrev@1.0.7 
│ │ │   ├─┬ npmlog@2.0.2 
│ │ │   │ ├── ansi@0.3.1 
│ │ │   │ ├─┬ are-we-there-yet@1.0.6 
│ │ │   │ │ └── delegates@1.0.0 
│ │ │   │ └─┬ gauge@1.2.5 
│ │ │   │   ├── has-unicode@2.0.0 
│ │ │   │   ├─┬ lodash.pad@3.3.0 
│ │ │   │   │ ├── lodash._root@3.0.0 
│ │ │   │   │ └── lodash.repeat@3.2.0 
│ │ │   │   ├─┬ lodash.padleft@3.1.1 
│ │ │   │   │ ├── lodash._basetostring@3.0.1 
│ │ │   │   │ └── lodash._createpadding@3.6.1 
│ │ │   │   └── lodash.padright@3.1.1 
│ │ │   ├─┬ rc@1.1.6 
│ │ │   │ ├── deep-extend@0.4.1 
│ │ │   │ ├── ini@1.3.4 
│ │ │   │ ├── minimist@1.2.0 
│ │ │   │ └── strip-json-comments@1.0.4 
│ │ │   ├─┬ request@2.69.0 
│ │ │   │ ├── aws-sign2@0.6.0 
│ │ │   │ ├─┬ aws4@1.2.1 
│ │ │   │ │ └── lru-cache@2.7.3 
│ │ │   │ ├── bl@1.0.2 
│ │ │   │ ├── caseless@0.11.0 
│ │ │   │ ├─┬ combined-stream@1.0.5 
│ │ │   │ │ └── delayed-stream@1.0.0 
│ │ │   │ ├── extend@3.0.0 
│ │ │   │ ├── forever-agent@0.6.1 
│ │ │   │ ├─┬ form-data@1.0.0-rc3 
│ │ │   │ │ └── async@1.5.2 
│ │ │   │ ├─┬ har-validator@2.0.6 
│ │ │   │ │ ├─┬ chalk@1.1.1 
│ │ │   │ │ │ ├── ansi-styles@2.1.0 
│ │ │   │ │ │ ├── escape-string-regexp@1.0.4 
│ │ │   │ │ │ ├─┬ has-ansi@2.0.0 
│ │ │   │ │ │ │ └── ansi-regex@2.0.0 
│ │ │   │ │ │ ├── strip-ansi@3.0.0 
│ │ │   │ │ │ └── supports-color@2.0.0 
│ │ │   │ │ ├─┬ commander@2.9.0 
│ │ │   │ │ │ └── graceful-readlink@1.0.1 
│ │ │   │ │ ├─┬ is-my-json-valid@2.12.4 
│ │ │   │ │ │ ├── generate-function@2.0.0 
│ │ │   │ │ │ ├─┬ generate-object-property@1.2.0 
│ │ │   │ │ │ │ └── is-property@1.0.2 
│ │ │   │ │ │ ├── jsonpointer@2.0.0 
│ │ │   │ │ │ └── xtend@4.0.1 
│ │ │   │ │ └─┬ pinkie-promise@2.0.0 
│ │ │   │ │   └── pinkie@2.0.4 
│ │ │   │ ├─┬ hawk@3.1.3 
│ │ │   │ │ ├── boom@2.10.1 
│ │ │   │ │ ├── cryptiles@2.0.5 
│ │ │   │ │ ├── hoek@2.16.3 
│ │ │   │ │ └── sntp@1.0.9 
│ │ │   │ ├─┬ http-signature@1.1.1 
│ │ │   │ │ ├── assert-plus@0.2.0 
│ │ │   │ │ ├─┬ jsprim@1.2.2 
│ │ │   │ │ │ ├── extsprintf@1.0.2 
│ │ │   │ │ │ ├── json-schema@0.2.2 
│ │ │   │ │ │ └── verror@1.3.6 
│ │ │   │ │ └─┬ sshpk@1.7.3 
│ │ │   │ │   ├── asn1@0.2.3 
│ │ │   │ │   ├── dashdash@1.12.2 
│ │ │   │ │   ├── ecc-jsbn@0.1.1 
│ │ │   │ │   ├── jodid25519@1.0.2 
│ │ │   │ │   ├── jsbn@0.1.0 
│ │ │   │ │   └── tweetnacl@0.13.3 
│ │ │   │ ├── is-typedarray@1.0.0 
│ │ │   │ ├── isstream@0.1.2 
│ │ │   │ ├── json-stringify-safe@5.0.1 
│ │ │   │ ├─┬ mime-types@2.1.9 
│ │ │   │ │ └── mime-db@1.21.0 
│ │ │   │ ├── node-uuid@1.4.7 
│ │ │   │ ├── oauth-sign@0.8.1 
│ │ │   │ ├── qs@6.0.2 
│ │ │   │ ├── stringstream@0.0.5 
│ │ │   │ ├── tough-cookie@2.2.1 
│ │ │   │ └── tunnel-agent@0.4.2 
│ │ │   ├─┬ rimraf@2.5.1 
│ │ │   │ └─┬ glob@6.0.4 
│ │ │   │   ├─┬ inflight@1.0.4 
│ │ │   │   │ └── wrappy@1.0.1 
│ │ │   │   ├── inherits@2.0.1 
│ │ │   │   ├─┬ minimatch@3.0.0 
│ │ │   │   │ └─┬ brace-expansion@1.1.2 
│ │ │   │   │   ├── balanced-match@0.3.0 
│ │ │   │   │   └── concat-map@0.0.1 
│ │ │   │   ├─┬ once@1.3.3 
│ │ │   │   │ └── wrappy@1.0.1 
│ │ │   │   └── path-is-absolute@1.0.0 
│ │ │   ├── semver@5.1.0 
│ │ │   ├─┬ tar@2.2.1 
│ │ │   │ ├── block-stream@0.0.8 
│ │ │   │ ├─┬ fstream@1.0.8 
│ │ │   │ │ └── graceful-fs@4.1.3 
│ │ │   │ └── inherits@2.0.1 
│ │ │   └─┬ tar-pack@3.1.3 
│ │ │     ├─┬ debug@2.2.0 
│ │ │     │ └── ms@0.7.1 
│ │ │     ├─┬ fstream-ignore@1.0.3 
│ │ │     │ └─┬ minimatch@3.0.0 
│ │ │     │   └─┬ brace-expansion@1.1.2 
│ │ │     │     ├── balanced-match@0.3.0 
│ │ │     │     └── concat-map@0.0.1 
│ │ │     ├─┬ once@1.3.3 
│ │ │     │ └── wrappy@1.0.1 
│ │ │     ├─┬ readable-stream@2.0.5 
│ │ │     │ ├── core-util-is@1.0.2 
│ │ │     │ ├── isarray@0.0.1 
│ │ │     │ ├── process-nextick-args@1.0.6 
│ │ │     │ ├── string_decoder@0.10.31 
│ │ │     │ └── util-deprecate@1.0.2 
│ │ │     └── uid-number@0.0.6 
│ │ ├── glob-parent@2.0.0 
│ │ ├── inherits@2.0.1 
│ │ ├─┬ is-binary-path@1.0.1 
│ │ │ └── binary-extensions@1.4.0 
│ │ ├── is-glob@2.0.1 
│ │ └── readdirp@2.0.0 
│ ├─┬ connect@3.4.1 
│ │ ├─┬ finalhandler@0.4.1 
│ │ │ ├─┬ on-finished@2.3.0 
│ │ │ │ └── ee-first@1.1.1 
│ │ │ └── unpipe@1.0.0 
│ │ ├── parseurl@1.3.1 
│ │ └── utils-merge@1.0.0 
│ ├── dev-ip@1.0.1 
│ ├── easy-extender@2.3.2 
│ ├─┬ eazy-logger@2.1.2 
│ │ ├── opt-merger@1.1.1 
│ │ └─┬ tfunk@3.0.1 
│ │   ├─┬ chalk@0.5.1 
│ │   │ ├── ansi-styles@1.1.0 
│ │   │ ├─┬ has-ansi@0.1.0 
│ │   │ │ └── ansi-regex@0.2.1 
│ │   │ ├── strip-ansi@0.3.0 
│ │   │ └── supports-color@0.2.0 
│ │   └── object-path@0.9.2 
│ ├── emitter-steward@1.0.0 
│ ├─┬ foxy@11.1.4 
│ │ ├─┬ http-proxy@1.13.2 
│ │ │ ├── eventemitter3@1.1.1 
│ │ │ └── requires-port@1.0.0 
│ │ ├─┬ lodash.merge@3.3.2 
│ │ │ ├── lodash._arraycopy@3.0.0 
│ │ │ ├── lodash._arrayeach@3.0.0 
│ │ │ ├─┬ lodash._createassigner@3.1.1 
│ │ │ │ └── lodash._bindcallback@3.0.1 
│ │ │ ├── lodash._getnative@3.9.1 
│ │ │ ├── lodash.isarguments@3.0.7 
│ │ │ ├── lodash.isarray@3.0.4 
│ │ │ ├─┬ lodash.isplainobject@3.2.0 
│ │ │ │ └── lodash._basefor@3.0.3 
│ │ │ ├── lodash.istypedarray@3.0.5 
│ │ │ ├── lodash.keys@3.1.2 
│ │ │ ├── lodash.keysin@3.0.8 
│ │ │ └── lodash.toplainobject@3.0.0 
│ │ └── resp-modifier@4.0.4 
│ ├─┬ fs-extra@0.26.5 
│ │ ├── jsonfile@2.2.3 
│ │ └── klaw@1.1.3 
│ ├── immutable@3.7.6 
│ ├─┬ localtunnel@1.8.1 
│ │ ├── openurl@1.1.0 
│ │ ├─┬ request@2.65.0 
│ │ │ ├── aws-sign2@0.6.0 
│ │ │ ├── bl@1.0.3 
│ │ │ ├── caseless@0.11.0 
│ │ │ ├─┬ combined-stream@1.0.5 
│ │ │ │ └── delayed-stream@1.0.0 
│ │ │ ├── extend@3.0.0 
│ │ │ ├── forever-agent@0.6.1 
│ │ │ ├── form-data@1.0.0-rc3 
│ │ │ ├─┬ har-validator@2.0.6 
│ │ │ │ └─┬ pinkie-promise@2.0.0 
│ │ │ │   └── pinkie@2.0.4 
│ │ │ ├─┬ hawk@3.1.3 
│ │ │ │ ├── boom@2.10.1 
│ │ │ │ ├── cryptiles@2.0.5 
│ │ │ │ ├── hoek@2.16.3 
│ │ │ │ └── sntp@1.0.9 
│ │ │ ├─┬ http-signature@0.11.0 
│ │ │ │ ├── asn1@0.1.11 
│ │ │ │ ├── assert-plus@0.1.5 
│ │ │ │ └── ctype@0.5.3 
│ │ │ ├── isstream@0.1.2 
│ │ │ ├── json-stringify-safe@5.0.1 
│ │ │ ├── node-uuid@1.4.7 
│ │ │ ├── oauth-sign@0.8.1 
│ │ │ ├── qs@5.2.0 
│ │ │ ├── stringstream@0.0.5 
│ │ │ ├── tough-cookie@2.2.1 
│ │ │ └── tunnel-agent@0.4.2 
│ │ └─┬ yargs@3.29.0 
│ │   ├── camelcase@1.2.1 
│ │   ├─┬ cliui@3.1.0 
│ │   │ ├─┬ string-width@1.0.1 
│ │   │ │ ├── code-point-at@1.0.0 
│ │   │ │ └── is-fullwidth-code-point@1.0.0 
│ │   │ └── wrap-ansi@1.0.0 
│ │   ├─┬ os-locale@1.4.0 
│ │   │ └─┬ lcid@1.0.0 
│ │   │   └── invert-kv@1.0.0 
│ │   ├── window-size@0.1.4 
│ │   └── y18n@3.2.0 
│ ├── longest@1.0.1 
│ ├─┬ meow@3.3.0 
│ │ ├─┬ camelcase-keys@1.0.0 
│ │ │ └── map-obj@1.0.1 
│ │ └── indent-string@1.2.2 
│ ├─┬ micromatch@2.3.5 
│ │ ├─┬ arr-diff@2.0.0 
│ │ │ └── arr-flatten@1.0.1 
│ │ ├── array-unique@0.2.1 
│ │ ├─┬ braces@1.8.3 
│ │ │ ├─┬ expand-range@1.8.1 
│ │ │ │ └─┬ fill-range@2.2.3 
│ │ │ │   ├── is-number@2.1.0 
│ │ │ │   ├── randomatic@1.1.5 
│ │ │ │   └── repeat-string@1.5.4 
│ │ │ ├── preserve@0.2.0 
│ │ │ └── repeat-element@1.1.2 
│ │ ├── expand-brackets@0.1.4 
│ │ ├── extglob@0.3.2 
│ │ ├── filename-regex@2.0.0 
│ │ ├── is-extglob@1.0.0 
│ │ ├─┬ kind-of@3.0.2 
│ │ │ └── is-buffer@1.1.2 
│ │ ├── lazy-cache@0.2.7 
│ │ ├── normalize-path@2.0.1 
│ │ ├─┬ object.omit@2.0.0 
│ │ │ └── is-extendable@0.1.1 
│ │ ├─┬ parse-glob@3.0.4 
│ │ │ ├── glob-base@0.3.0 
│ │ │ └── is-dotfile@1.0.2 
│ │ └─┬ regex-cache@0.4.2 
│ │   ├── is-equal-shallow@0.1.3 
│ │   └── is-primitive@2.0.0 
│ ├─┬ opn@3.0.3 
│ │ └── object-assign@4.0.1 
│ ├─┬ portscanner@1.0.0 
│ │ └── async@0.1.15 
│ ├─┬ query-string@2.4.2 
│ │ └── strict-uri-encode@1.1.0 
│ ├── resp-modifier@5.0.2 
│ ├─┬ serve-index@1.7.3 
│ │ ├─┬ accepts@1.2.13 
│ │ │ └── negotiator@0.5.3 
│ │ ├── batch@0.5.3 
│ │ ├── escape-html@1.0.3 
│ │ ├─┬ http-errors@1.3.1 
│ │ │ └── statuses@1.2.1 
│ │ └─┬ mime-types@2.1.10 
│ │   └── mime-db@1.22.0 
│ ├─┬ serve-static@1.10.2 
│ │ └─┬ send@0.13.1 
│ │   ├── depd@1.1.0 
│ │   ├── destroy@1.0.4 
│ │   ├── mime@1.3.4 
│ │   └── range-parser@1.0.3 
│ ├─┬ socket.io@1.3.7 
│ │ ├─┬ debug@2.1.0 
│ │ │ └── ms@0.6.2 
│ │ ├─┬ engine.io@1.5.4 
│ │ │ ├── base64id@0.1.0 
│ │ │ ├─┬ debug@1.0.3 
│ │ │ │ └── ms@0.6.2 
│ │ │ ├─┬ engine.io-parser@1.2.2 
│ │ │ │ ├── after@0.8.1 
│ │ │ │ ├── arraybuffer.slice@0.0.6 
│ │ │ │ ├── base64-arraybuffer@0.1.2 
│ │ │ │ ├── blob@0.0.4 
│ │ │ │ └── utf8@2.1.0 
│ │ │ └─┬ ws@0.8.0 
│ │ │   ├─┬ bufferutil@1.2.1 
│ │ │   │ └── bindings@1.2.1 
│ │ │   ├── options@0.0.6 
│ │ │   ├── ultron@1.0.2 
│ │ │   └── utf-8-validate@1.2.1 
│ │ ├── has-binary-data@0.1.3 
│ │ ├─┬ socket.io-adapter@0.3.1 
│ │ │ ├─┬ debug@1.0.2 
│ │ │ │ └── ms@0.6.2 
│ │ │ ├── object-keys@1.0.1 
│ │ │ └─┬ socket.io-parser@2.2.2 
│ │ │   └── debug@0.7.4 
│ │ ├─┬ socket.io-client@1.3.7 
│ │ │ ├── backo2@1.0.2 
│ │ │ ├── component-bind@1.0.0 
│ │ │ ├── component-emitter@1.1.2 
│ │ │ ├── debug@0.7.4 
│ │ │ ├─┬ engine.io-client@1.5.4 
│ │ │ │ ├── component-inherit@0.0.3 
│ │ │ │ ├─┬ debug@1.0.4 
│ │ │ │ │ └── ms@0.6.2 
│ │ │ │ ├─┬ has-cors@1.0.3 
│ │ │ │ │ └── global@2.0.1 
│ │ │ │ ├── parsejson@0.0.1 
│ │ │ │ ├── parseqs@0.0.2 
│ │ │ │ ├── parseuri@0.0.4 
│ │ │ │ └── xmlhttprequest@1.5.0 
│ │ │ ├── has-binary@0.1.6 
│ │ │ ├── indexof@0.0.1 
│ │ │ ├── object-component@0.0.3 
│ │ │ ├─┬ parseuri@0.0.2 
│ │ │ │ └─┬ better-assert@1.0.2 
│ │ │ │   └── callsite@1.0.0 
│ │ │ └── to-array@0.1.3 
│ │ └─┬ socket.io-parser@2.2.4 
│ │   ├── benchmark@1.0.0 
│ │   ├── debug@0.7.4 
│ │   └── json3@3.2.6 
│ ├── ua-parser-js@0.7.10 
│ └── ucfirst@1.0.0 
├─┬ del@1.2.1 
│ ├─┬ each-async@1.1.1 
│ │ ├── onetime@1.1.0 
│ │ └── set-immediate-shim@1.0.1 
│ ├─┬ globby@2.1.0 
│ │ ├── array-union@1.0.1 
│ │ ├── async@1.5.2 
│ │ └── glob@5.0.15 
│ ├── is-path-cwd@1.0.0 
│ ├─┬ is-path-in-cwd@1.0.0 
│ │ └─┬ is-path-inside@1.0.0 
│ │   └── path-is-inside@1.0.1 
│ ├── object-assign@3.0.0 
│ └─┬ rimraf@2.5.2 
│   └── glob@7.0.0 
├─┬ gulp@3.9.1 
│ ├── archy@1.0.0 
│ ├─┬ chalk@1.1.1 
│ │ ├─┬ ansi-styles@2.2.0 
│ │ │ └── color-convert@1.0.0 
│ │ ├── escape-string-regexp@1.0.5 
│ │ ├─┬ has-ansi@2.0.0 
│ │ │ └── ansi-regex@2.0.0 
│ │ ├── strip-ansi@3.0.1 
│ │ └── supports-color@2.0.0 
│ ├── deprecated@0.0.1 
│ ├─┬ gulp-util@3.0.7 
│ │ ├── array-differ@1.0.0 
│ │ ├── array-uniq@1.0.2 
│ │ ├── beeper@1.1.0 
│ │ ├── dateformat@1.0.12 
│ │ ├─┬ gulplog@1.0.0 
│ │ │ └── glogg@1.0.0 
│ │ ├─┬ has-gulplog@0.1.0 
│ │ │ └── sparkles@1.0.0 
│ │ ├── lodash._reescape@3.0.0 
│ │ ├── lodash._reevaluate@3.0.0 
│ │ ├── lodash._reinterpolate@3.0.0 
│ │ ├─┬ lodash.template@3.6.2 
│ │ │ ├── lodash._basecopy@3.0.1 
│ │ │ ├── lodash._basetostring@3.0.1 
│ │ │ ├── lodash._basevalues@3.0.0 
│ │ │ ├── lodash._isiterateecall@3.0.9 
│ │ │ ├── lodash.escape@3.2.0 
│ │ │ ├── lodash.restparam@3.6.1 
│ │ │ └── lodash.templatesettings@3.1.1 
│ │ └── multipipe@0.1.2 
│ ├── interpret@1.0.0 
│ ├─┬ liftoff@2.2.0 
│ │ ├── extend@2.0.1 
│ │ ├─┬ findup-sync@0.3.0 
│ │ │ └── glob@5.0.15 
│ │ ├── flagged-respawn@0.3.1 
│ │ ├── rechoir@0.6.2 
│ │ └── resolve@1.1.7 
│ ├── minimist@1.2.0 
│ ├─┬ orchestrator@0.3.7 
│ │ ├── end-of-stream@0.1.5 
│ │ ├── sequencify@0.0.7 
│ │ └── stream-consume@0.1.0 
│ ├── pretty-hrtime@1.0.2 
│ ├── semver@4.3.6 
│ ├─┬ tildify@1.1.2 
│ │ └── os-homedir@1.0.1 
│ ├─┬ v8flags@2.0.11 
│ │ └── user-home@1.1.1 
│ └─┬ vinyl-fs@0.3.14 
│   ├── defaults@1.0.3 
│   ├─┬ glob-stream@3.1.18 
│   │ ├── glob@4.5.3 
│   │ ├─┬ glob2base@0.0.12 
│   │ │ └── find-index@0.1.1 
│   │ ├── ordered-read-streams@0.1.0 
│   │ ├─┬ through2@0.6.5 
│   │ │ └── readable-stream@1.0.33 
│   │ └── unique-stream@1.0.0 
│   ├── glob-watcher@0.0.6 
│   ├── graceful-fs@3.0.8 
│   ├─┬ strip-bom@1.0.0 
│   │ └── first-chunk-stream@1.0.0 
│   ├─┬ through2@0.6.5 
│   │ └── readable-stream@1.0.33 
│   └─┬ vinyl@0.4.6 
│     └── clone@0.2.0 
├─┬ gulp-autoprefixer@3.1.0 
│ ├─┬ autoprefixer@6.3.3 
│ │ ├── browserslist@1.1.3 
│ │ ├── caniuse-db@1.0.30000414 
│ │ ├── normalize-range@0.1.2 
│ │ ├── num2fraction@1.2.2 
│ │ └── postcss-value-parser@3.3.0 
│ ├─┬ postcss@5.0.18 
│ │ ├── js-base64@2.1.9 
│ │ └─┬ supports-color@3.1.2 
│ │   └── has-flag@1.0.0 
│ ├─┬ through2@2.0.1 
│ │ └── xtend@4.0.1 
│ └── vinyl-sourcemaps-apply@0.2.1 
├─┬ gulp-babel@6.1.2 
│ ├── object-assign@4.0.1 
│ └── replace-ext@0.0.1 
├─┬ gulp-cache@0.2.10 
│ ├── bluebird@2.10.2 
│ ├─┬ cache-swap@0.2.3 
│ │ └── object-assign@4.0.1 
│ ├─┬ object.omit@1.1.0 
│ │ ├─┬ for-own@0.1.3 
│ │ │ └── for-in@0.1.4 
│ │ └── isobject@1.0.2 
│ ├── object.pick@1.1.1 
│ ├─┬ through2@0.6.5 
│ │ └── readable-stream@1.0.33 
│ ├── try-json-parse@0.1.1 
│ └─┬ vinyl@0.5.3 
│   ├── clone@1.0.2 
│   └── clone-stats@0.0.1 
├─┬ gulp-cssnano@2.1.1 
│ ├─┬ cssnano@3.5.2 
│ │ ├── decamelize@1.1.2 
│ │ ├── defined@1.0.0 
│ │ ├── indexes-of@1.0.1 
│ │ ├── object-assign@4.0.1 
│ │ ├─┬ postcss-calc@5.2.0 
│ │ │ ├── postcss-message-helpers@2.0.0 
│ │ │ └─┬ reduce-css-calc@1.2.1 
│ │ │   ├── balanced-match@0.1.0 
│ │ │   └─┬ reduce-function-call@1.0.1 
│ │ │     └── balanced-match@0.1.0 
│ │ ├─┬ postcss-colormin@2.1.8 
│ │ │ └─┬ colormin@1.0.7 
│ │ │   ├─┬ color@0.11.1 
│ │ │   │ ├── color-convert@0.5.3 
│ │ │   │ └─┬ color-string@0.3.0 
│ │ │   │   └── color-name@1.1.1 
│ │ │   └── css-color-names@0.0.3 
│ │ ├── postcss-convert-values@2.3.4 
│ │ ├── postcss-discard-comments@2.0.4 
│ │ ├── postcss-discard-duplicates@2.0.1 
│ │ ├── postcss-discard-empty@2.0.1 
│ │ ├─┬ postcss-discard-unused@2.2.1 
│ │ │ ├── flatten@1.0.2 
│ │ │ └── uniqs@2.0.0 
│ │ ├─┬ postcss-filter-plugins@2.0.0 
│ │ │ └── uniqid@1.0.0 
│ │ ├─┬ postcss-merge-idents@2.1.5 
│ │ │ └── has-own@1.0.0 
│ │ ├── postcss-merge-longhand@2.0.1 
│ │ ├── postcss-merge-rules@2.0.6 
│ │ ├─┬ postcss-minify-font-values@1.0.3 
│ │ │ └── object-assign@4.0.1 
│ │ ├── postcss-minify-gradients@1.0.1 
│ │ ├─┬ postcss-minify-params@1.0.4 
│ │ │ └── alphanum-sort@1.0.2 
│ │ ├─┬ postcss-minify-selectors@2.0.4 
│ │ │ └─┬ postcss-selector-parser@1.3.2 
│ │ │   └── uniq@1.0.1 
│ │ ├── postcss-normalize-charset@1.1.0 
│ │ ├─┬ postcss-normalize-url@3.0.7 
│ │ │ ├── is-absolute-url@2.0.0 
│ │ │ └─┬ normalize-url@1.4.1 
│ │ │   ├── object-assign@4.0.1 
│ │ │   ├── prepend-http@1.0.3 
│ │ │   ├── query-string@3.0.1 
│ │ │   └─┬ sort-keys@1.1.1 
│ │ │     └── is-plain-obj@1.1.0 
│ │ ├── postcss-ordered-values@2.1.0 
│ │ ├── postcss-reduce-idents@2.3.0 
│ │ ├── postcss-reduce-transforms@1.0.3 
│ │ ├─┬ postcss-svgo@2.1.2 
│ │ │ ├── is-svg@1.1.1 
│ │ │ └─┬ svgo@0.6.1 
│ │ │   ├─┬ coa@1.0.1 
│ │ │   │ └── q@1.4.1 
│ │ │   ├── colors@1.1.2 
│ │ │   ├─┬ csso@1.4.4 
│ │ │   │ └── clap@1.0.10 
│ │ │   ├── sax@1.1.5 
│ │ │   └── whet.extend@0.9.9 
│ │ ├── postcss-unique-selectors@2.0.2 
│ │ └── postcss-zindex@2.0.1 
│ └── object-assign@4.0.1 
├─┬ gulp-eslint@0.13.2 
│ ├─┬ bufferstreams@1.0.1 
│ │ └── readable-stream@1.1.13 
│ └─┬ eslint@0.22.1 
│   ├─┬ concat-stream@1.5.1 
│   │ └── typedarray@0.0.6 
│   ├─┬ doctrine@0.6.4 
│   │ └── esutils@1.1.6 
│   ├─┬ escope@3.5.0 
│   │ ├─┬ es6-map@0.1.3 
│   │ │ ├── d@0.1.1 
│   │ │ ├── es5-ext@0.10.11 
│   │ │ ├── es6-iterator@2.0.0 
│   │ │ ├── es6-set@0.1.4 
│   │ │ ├── es6-symbol@3.0.2 
│   │ │ └── event-emitter@0.3.4 
│   │ ├── es6-weak-map@2.0.1 
│   │ ├─┬ esrecurse@4.0.0 
│   │ │ ├── estraverse@4.1.1 
│   │ │ └── object-assign@4.0.1 
│   │ └── estraverse@4.1.1 
│   ├── espree@2.2.5 
│   ├── estraverse@2.0.0 
│   ├── estraverse-fb@1.3.1 
│   ├── globals@6.4.1 
│   ├─┬ inquirer@0.8.5 
│   │ ├── ansi-regex@1.1.1 
│   │ ├── cli-width@1.1.1 
│   │ ├── figures@1.4.0 
│   │ ├─┬ readline2@0.1.1 
│   │ │ ├── mute-stream@0.0.4 
│   │ │ └─┬ strip-ansi@2.0.1 
│   │ │   └── ansi-regex@1.1.1 
│   │ └── rx@2.5.3 
│   ├─┬ is-my-json-valid@2.13.1 
│   │ ├── generate-function@2.0.0 
│   │ ├─┬ generate-object-property@1.2.0 
│   │ │ └── is-property@1.0.2 
│   │ └── jsonpointer@2.0.0 
│   ├─┬ js-yaml@3.4.6 
│   │ ├─┬ argparse@1.0.6 
│   │ │ └── sprintf-js@1.0.3 
│   │ ├── esprima@2.7.2 
│   │ └── inherit@2.2.3 
│   ├── object-assign@2.1.1 
│   ├─┬ optionator@0.5.0 
│   │ ├── deep-is@0.1.3 
│   │ ├── fast-levenshtein@1.0.7 
│   │ ├── levn@0.2.5 
│   │ ├── prelude-ls@1.1.2 
│   │ ├── type-check@0.3.2 
│   │ └── wordwrap@0.0.3 
│   ├── text-table@0.2.0 
│   └── xml-escape@1.0.0 
├─┬ gulp-htmlmin@1.3.0 
│ ├── bufferstreams@1.1.0 
│ ├─┬ html-minifier@1.2.0 
│ │ ├─┬ change-case@2.3.1 
│ │ │ ├── camel-case@1.2.2 
│ │ │ ├── constant-case@1.1.2 
│ │ │ ├── dot-case@1.1.2 
│ │ │ ├── is-lower-case@1.1.3 
│ │ │ ├── is-upper-case@1.1.2 
│ │ │ ├── lower-case@1.1.3 
│ │ │ ├── lower-case-first@1.0.2 
│ │ │ ├── param-case@1.1.2 
│ │ │ ├── pascal-case@1.1.2 
│ │ │ ├── path-case@1.1.2 
│ │ │ ├── sentence-case@1.1.3 
│ │ │ ├── snake-case@1.1.2 
│ │ │ ├── swap-case@1.1.2 
│ │ │ ├── title-case@1.1.2 
│ │ │ ├── upper-case@1.1.3 
│ │ │ └── upper-case-first@1.1.2 
│ │ ├─┬ clean-css@3.4.10 
│ │ │ ├── commander@2.8.1 
│ │ │ └── source-map@0.4.4 
│ │ ├─┬ cli@0.11.1 
│ │ │ ├── exit@0.1.2 
│ │ │ └── glob@5.0.15 
│ │ └── relateurl@0.2.6 
│ ├── object-assign@4.0.1 
│ ├─┬ readable-stream@2.0.5 
│ │ ├── core-util-is@1.0.2 
│ │ ├── isarray@0.0.1 
│ │ ├── process-nextick-args@1.0.6 
│ │ ├── string_decoder@0.10.31 
│ │ └── util-deprecate@1.0.2 
│ └── tryit@1.0.2 
├─┬ gulp-if@1.2.5 
│ ├─┬ gulp-match@0.2.1 
│ │ └─┬ minimatch@1.0.0 
│ │   ├── lru-cache@2.7.3 
│ │   └── sigmund@1.0.1 
│ ├─┬ ternary-stream@1.2.3 
│ │ ├─┬ duplexer2@0.0.2 
│ │ │ └── readable-stream@1.1.13 
│ │ ├── fork-stream@0.0.4 
│ │ ├─┬ merge-stream@0.1.8 
│ │ │ └─┬ through2@0.6.5 
│ │ │   └── readable-stream@1.0.33 
│ │ └─┬ through2@0.6.5 
│ │   └── readable-stream@1.0.33 
│ └─┬ through2@0.6.5 
│   └── readable-stream@1.0.33 
├─┬ gulp-imagemin@2.4.0 
│ ├─┬ imagemin@4.0.0 
│ │ ├─┬ buffer-to-vinyl@1.1.0 
│ │ │ ├── file-type@3.8.0 
│ │ │ ├── uuid@2.0.1 
│ │ │ └── vinyl@1.1.1 
│ │ ├─┬ imagemin-gifsicle@4.2.0 
│ │ │ ├─┬ gifsicle@3.0.3 
│ │ │ │ ├─┬ bin-build@2.2.0 
│ │ │ │ │ ├── archive-type@3.2.0 
│ │ │ │ │ ├─┬ decompress@3.0.0 
│ │ │ │ │ │ ├─┬ decompress-tar@3.1.0 
│ │ │ │ │ │ │ ├── is-tar@1.0.0 
│ │ │ │ │ │ │ ├── object-assign@2.1.1 
│ │ │ │ │ │ │ ├─┬ strip-dirs@1.1.1 
│ │ │ │ │ │ │ │ ├── is-natural-number@2.0.0 
│ │ │ │ │ │ │ │ └── sum-up@1.0.2 
│ │ │ │ │ │ │ ├─┬ tar-stream@1.3.2 
│ │ │ │ │ │ │ │ └── end-of-stream@1.1.0 
│ │ │ │ │ │ │ ├─┬ through2@0.6.5 
│ │ │ │ │ │ │ │ └── readable-stream@1.0.33 
│ │ │ │ │ │ │ └─┬ vinyl@0.4.6 
│ │ │ │ │ │ │   └── clone@0.2.0 
│ │ │ │ │ │ ├─┬ decompress-tarbz2@3.1.0 
│ │ │ │ │ │ │ ├── is-bzip2@1.0.0 
│ │ │ │ │ │ │ ├── object-assign@2.1.1 
│ │ │ │ │ │ │ ├─┬ seek-bzip@1.0.5 
│ │ │ │ │ │ │ │ └── commander@2.8.1 
│ │ │ │ │ │ │ ├─┬ through2@0.6.5 
│ │ │ │ │ │ │ │ └── readable-stream@1.0.33 
│ │ │ │ │ │ │ └─┬ vinyl@0.4.6 
│ │ │ │ │ │ │   └── clone@0.2.0 
│ │ │ │ │ │ ├─┬ decompress-targz@3.1.0 
│ │ │ │ │ │ │ ├── is-gzip@1.0.0 
│ │ │ │ │ │ │ ├── object-assign@2.1.1 
│ │ │ │ │ │ │ ├─┬ through2@0.6.5 
│ │ │ │ │ │ │ │ └── readable-stream@1.0.33 
│ │ │ │ │ │ │ └─┬ vinyl@0.4.6 
│ │ │ │ │ │ │   └── clone@0.2.0 
│ │ │ │ │ │ ├─┬ decompress-unzip@3.4.0 
│ │ │ │ │ │ │ ├── is-zip@1.0.0 
│ │ │ │ │ │ │ ├── stat-mode@0.2.1 
│ │ │ │ │ │ │ ├── vinyl@1.1.1 
│ │ │ │ │ │ │ └─┬ yauzl@2.4.1 
│ │ │ │ │ │ │   └─┬ fd-slicer@1.0.1 
│ │ │ │ │ │ │     └── pend@1.2.0 
│ │ │ │ │ │ ├─┬ vinyl-assign@1.2.1 
│ │ │ │ │ │ │ └── object-assign@4.0.1 
│ │ │ │ │ │ └─┬ vinyl-fs@2.3.4 
│ │ │ │ │ │   ├─┬ glob-stream@5.3.1 
│ │ │ │ │ │   │ ├── glob@5.0.15 
│ │ │ │ │ │   │ ├── micromatch@2.3.7 
│ │ │ │ │ │   │ ├── ordered-read-streams@0.3.0 
│ │ │ │ │ │   │ ├─┬ through2@0.6.5 
│ │ │ │ │ │   │ │ └── readable-stream@1.0.33 
│ │ │ │ │ │   │ └── unique-stream@2.2.1 
│ │ │ │ │ │   ├── merge-stream@1.0.0 
│ │ │ │ │ │   ├── object-assign@4.0.1 
│ │ │ │ │ │   ├── strip-bom@2.0.0 
│ │ │ │ │ │   └── vinyl@1.1.1 
│ │ │ │ │ ├─┬ download@4.4.3 
│ │ │ │ │ │ ├─┬ caw@1.2.0 
│ │ │ │ │ │ │ ├─┬ get-proxy@1.0.1 
│ │ │ │ │ │ │ │ └─┬ rc@0.5.5 
│ │ │ │ │ │ │ │   ├── deep-extend@0.2.11 
│ │ │ │ │ │ │ │   ├── minimist@0.0.10 
│ │ │ │ │ │ │ │   └── strip-json-comments@0.1.3 
│ │ │ │ │ │ │ └── is-obj@1.0.0 
│ │ │ │ │ │ ├─┬ filenamify@1.2.0 
│ │ │ │ │ │ │ ├── filename-reserved-regex@1.0.0 
│ │ │ │ │ │ │ ├── strip-outer@1.0.0 
│ │ │ │ │ │ │ └── trim-repeated@1.0.0 
│ │ │ │ │ │ ├─┬ got@5.4.2 
│ │ │ │ │ │ │ ├─┬ create-error-class@2.0.1 
│ │ │ │ │ │ │ │ └── capture-stack-trace@1.0.0 
│ │ │ │ │ │ │ ├── duplexer2@0.1.4 
│ │ │ │ │ │ │ ├── is-redirect@1.0.0 
│ │ │ │ │ │ │ ├── is-retry-allowed@1.0.0 
│ │ │ │ │ │ │ ├── lowercase-keys@1.0.0 
│ │ │ │ │ │ │ ├── node-status-codes@1.0.0 
│ │ │ │ │ │ │ ├── object-assign@4.0.1 
│ │ │ │ │ │ │ ├─┬ parse-json@2.2.0 
│ │ │ │ │ │ │ │ └─┬ error-ex@1.3.0 
│ │ │ │ │ │ │ │   └── is-arrayish@0.2.1 
│ │ │ │ │ │ │ ├── timed-out@2.0.0 
│ │ │ │ │ │ │ ├── unzip-response@1.0.0 
│ │ │ │ │ │ │ └── url-parse-lax@1.0.0 
│ │ │ │ │ │ ├── gulp-decompress@1.2.0 
│ │ │ │ │ │ ├── gulp-rename@1.2.2 
│ │ │ │ │ │ ├── is-url@1.2.1 
│ │ │ │ │ │ ├── object-assign@4.0.1 
│ │ │ │ │ │ ├── read-all-stream@3.1.0 
│ │ │ │ │ │ ├── vinyl@1.1.1 
│ │ │ │ │ │ ├─┬ vinyl-fs@2.3.4 
│ │ │ │ │ │ │ ├─┬ glob-stream@5.3.1 
│ │ │ │ │ │ │ │ ├── glob@5.0.15 
│ │ │ │ │ │ │ │ ├── micromatch@2.3.7 
│ │ │ │ │ │ │ │ ├── ordered-read-streams@0.3.0 
│ │ │ │ │ │ │ │ ├─┬ through2@0.6.5 
│ │ │ │ │ │ │ │ │ └── readable-stream@1.0.33 
│ │ │ │ │ │ │ │ └── unique-stream@2.2.1 
│ │ │ │ │ │ │ ├── merge-stream@1.0.0 
│ │ │ │ │ │ │ └── strip-bom@2.0.0 
│ │ │ │ │ │ └─┬ ware@1.3.0 
│ │ │ │ │ │   └─┬ wrap-fn@0.1.5 
│ │ │ │ │ │     └── co@3.1.0 
│ │ │ │ │ ├─┬ exec-series@1.0.2 
│ │ │ │ │ │ └── async-each-series@1.1.0 
│ │ │ │ │ └─┬ url-regex@3.1.0 
│ │ │ │ │   └── ip-regex@1.0.3 
│ │ │ │ ├─┬ bin-wrapper@3.0.2 
│ │ │ │ │ ├─┬ bin-check@2.0.0 
│ │ │ │ │ │ └── executable@1.1.0 
│ │ │ │ │ ├─┬ bin-version-check@2.1.0 
│ │ │ │ │ │ ├─┬ bin-version@1.0.4 
│ │ │ │ │ │ │ └─┬ find-versions@1.2.1 
│ │ │ │ │ │ │   ├─┬ meow@3.7.0 
│ │ │ │ │ │ │   │ ├─┬ camelcase-keys@2.0.0 
│ │ │ │ │ │ │   │ │ └── camelcase@2.1.0 
│ │ │ │ │ │ │   │ ├─┬ loud-rejection@1.3.0 
│ │ │ │ │ │ │   │ │ ├── array-find-index@1.0.1 
│ │ │ │ │ │ │   │ │ └── signal-exit@2.1.2 
│ │ │ │ │ │ │   │ ├─┬ normalize-package-data@2.3.5 
│ │ │ │ │ │ │   │ │ ├── hosted-git-info@2.1.4 
│ │ │ │ │ │ │   │ │ ├─┬ is-builtin-module@1.0.0 
│ │ │ │ │ │ │   │ │ │ └── builtin-modules@1.1.1 
│ │ │ │ │ │ │   │ │ └─┬ validate-npm-package-license@3.0.1 
│ │ │ │ │ │ │   │ │   ├─┬ spdx-correct@1.0.2 
│ │ │ │ │ │ │   │ │   │ └── spdx-license-ids@1.2.0 
│ │ │ │ │ │ │   │ │   └─┬ spdx-expression-parse@1.0.2 
│ │ │ │ │ │ │   │ │     └── spdx-exceptions@1.0.4 
│ │ │ │ │ │ │   │ ├── object-assign@4.0.1 
│ │ │ │ │ │ │   │ ├─┬ read-pkg-up@1.0.1 
│ │ │ │ │ │ │   │ │ ├─┬ find-up@1.1.0 
│ │ │ │ │ │ │   │ │ │ └── path-exists@2.1.0 
│ │ │ │ │ │ │   │ │ └─┬ read-pkg@1.1.0 
│ │ │ │ │ │ │   │ │   ├─┬ load-json-file@1.1.0 
│ │ │ │ │ │ │   │ │   │ ├── pify@2.3.0 
│ │ │ │ │ │ │   │ │   │ └── strip-bom@2.0.0 
│ │ │ │ │ │ │   │ │   └── path-type@1.1.0 
│ │ │ │ │ │ │   │ ├─┬ redent@1.0.0 
│ │ │ │ │ │ │   │ │ ├─┬ indent-string@2.1.0 
│ │ │ │ │ │ │   │ │ │ └── repeating@2.0.0 
│ │ │ │ │ │ │   │ │ └── strip-indent@1.0.1 
│ │ │ │ │ │ │   │ └── trim-newlines@1.0.0 
│ │ │ │ │ │ │   └── semver-regex@1.0.0 
│ │ │ │ │ │ └─┬ semver-truncate@1.1.0 
│ │ │ │ │ │   └── semver@5.1.0 
│ │ │ │ │ ├── lazy-req@1.1.0 
│ │ │ │ │ └── os-filter-obj@1.0.3 
│ │ │ │ └─┬ logalot@2.1.0 
│ │ │ │   └─┬ squeak@1.3.0 
│ │ │ │     ├── console-stream@0.1.1 
│ │ │ │     └─┬ lpad-align@1.1.0 
│ │ │ │       └── lpad@2.0.1 
│ │ │ ├── is-gif@1.0.0 
│ │ │ └─┬ through2@0.6.5 
│ │ │   └── readable-stream@1.0.33 
│ │ ├─┬ imagemin-jpegtran@4.3.2 
│ │ │ ├── is-jpg@1.0.0 
│ │ │ └── jpegtran-bin@3.0.6 
│ │ ├─┬ imagemin-optipng@4.3.0 
│ │ │ ├─┬ exec-buffer@2.0.1 
│ │ │ │ └── tempfile@1.1.1 
│ │ │ ├── is-png@1.0.0 
│ │ │ ├── optipng-bin@3.1.0 
│ │ │ └─┬ through2@0.6.5 
│ │ │   └── readable-stream@1.0.33 
│ │ ├── imagemin-svgo@4.2.1 
│ │ ├── optional@0.1.3 
│ │ ├─┬ stream-combiner2@1.1.1 
│ │ │ └── duplexer2@0.1.4 
│ │ └─┬ vinyl-fs@2.3.4 
│ │   ├─┬ glob-stream@5.3.1 
│ │   │ ├── glob@5.0.15 
│ │   │ ├── micromatch@2.3.7 
│ │   │ ├── ordered-read-streams@0.3.0 
│ │   │ ├─┬ through2@0.6.5 
│ │   │ │ └── readable-stream@1.0.33 
│ │   │ └── unique-stream@2.2.1 
│ │   ├── merge-stream@1.0.0 
│ │   ├── object-assign@4.0.1 
│ │   ├── strip-bom@2.0.0 
│ │   └── vinyl@1.1.1 
│ ├── object-assign@4.0.1 
│ ├─┬ plur@2.1.2 
│ │ └── irregular-plurals@1.1.0 
│ ├─┬ pretty-bytes@2.0.1 
│ │ ├── get-stdin@4.0.1 
│ │ └── number-is-nan@1.0.0 
│ └── through2-concurrent@1.1.0 
├─┬ gulp-load-plugins@0.10.0 
│ ├─┬ findup-sync@0.2.1 
│ │ └── glob@4.3.5 
│ └── multimatch@2.0.0 
├── gulp-plumber@1.1.0 
├─┬ gulp-sass@2.2.0 
│ ├─┬ node-sass@3.4.2 
│ │ ├── async-foreach@0.1.3 
│ │ ├─┬ cross-spawn@2.1.5 
│ │ │ ├─┬ cross-spawn-async@2.1.9 
│ │ │ │ └─┬ lru-cache@4.0.0 
│ │ │ │   ├── pseudomap@1.0.2 
│ │ │ │   └── yallist@2.0.0 
│ │ │ └─┬ spawn-sync@1.0.15 
│ │ │   └── os-shim@0.1.3 
│ │ ├─┬ gaze@0.5.2 
│ │ │ └─┬ globule@0.1.0 
│ │ │   ├─┬ glob@3.1.21 
│ │ │   │ ├── graceful-fs@1.2.3 
│ │ │   │ └── inherits@1.0.2 
│ │ │   ├── lodash@1.0.2 
│ │ │   └── minimatch@0.2.14 
│ │ ├── glob@5.0.15 
│ │ ├── nan@2.2.0 
│ │ ├─┬ node-gyp@3.3.0 
│ │ │ ├── fstream@1.0.8 
│ │ │ ├─┬ glob@4.5.3 
│ │ │ │ └── minimatch@2.0.10 
│ │ │ ├── minimatch@1.0.0 
│ │ │ ├─┬ npmlog@2.0.2 
│ │ │ │ ├── ansi@0.3.1 
│ │ │ │ ├─┬ are-we-there-yet@1.0.6 
│ │ │ │ │ └── delegates@1.0.0 
│ │ │ │ └─┬ gauge@1.2.7 
│ │ │ │   ├── has-unicode@2.0.0 
│ │ │ │   ├─┬ lodash.pad@4.1.0 
│ │ │ │   │ ├── lodash.repeat@4.0.0 
│ │ │ │   │ └── lodash.tostring@4.1.1 
│ │ │ │   ├── lodash.padend@4.2.0 
│ │ │ │   └── lodash.padstart@4.2.0 
│ │ │ ├── osenv@0.1.3 
│ │ │ ├─┬ path-array@1.0.1 
│ │ │ │ └── array-index@1.0.0 
│ │ │ ├─┬ tar@2.2.1 
│ │ │ │ └── block-stream@0.0.8 
│ │ │ └─┬ which@1.2.4 
│ │ │   ├─┬ is-absolute@0.1.7 
│ │ │   │ └── is-relative@0.1.3 
│ │ │   └── isexe@1.1.2 
│ │ ├─┬ npmconf@2.1.2 
│ │ │ ├─┬ config-chain@1.1.10 
│ │ │ │ └── proto-list@1.2.4 
│ │ │ ├── ini@1.3.4 
│ │ │ └── uid-number@0.0.5 
│ │ └─┬ sass-graph@2.1.1 
│ │   ├── glob@6.0.4 
│ │   └── lodash@4.5.1 
│ └── object-assign@4.0.1 
├─┬ gulp-size@1.3.0 
│ └─┬ gzip-size@1.0.0 
│   └─┬ browserify-zlib@0.1.4 
│     └── pako@0.2.8 
├─┬ gulp-sourcemaps@1.6.0 
│ ├── graceful-fs@4.1.3 
│ ├─┬ strip-bom@2.0.0 
│ │ └── is-utf8@0.2.1 
│ └── vinyl@1.1.1 
├─┬ gulp-uglify@1.5.3 
│ ├── deap@1.0.0 
│ ├─┬ fancy-log@1.2.0 
│ │ └── time-stamp@1.0.0 
│ ├── isobject@2.0.0 
│ ├─┬ uglify-js@2.6.2 
│ │ ├── async@0.2.10 
│ │ ├── uglify-to-browserify@1.0.2 
│ │ └─┬ yargs@3.10.0 
│ │   ├─┬ cliui@2.1.0 
│ │   │ ├─┬ center-align@0.1.3 
│ │   │ │ ├── align-text@0.1.4 
│ │   │ │ └── lazy-cache@1.0.3 
│ │   │ ├── right-align@0.1.3 
│ │   │ └── wordwrap@0.0.2 
│ │   └── window-size@0.1.0 
│ └── uglify-save-license@0.4.1 
├─┬ gulp-useref@3.0.7 
│ ├─┬ event-stream@3.3.2 
│ │ ├── duplexer@0.1.1 
│ │ ├── from@0.1.3 
│ │ ├── map-stream@0.1.0 
│ │ ├── pause-stream@0.0.11 
│ │ ├── split@0.3.3 
│ │ ├── stream-combiner@0.0.4 
│ │ └── through@2.3.8 
│ ├─┬ glob@6.0.4 
│ │ ├─┬ inflight@1.0.4 
│ │ │ └── wrappy@1.0.1 
│ │ └── once@1.3.3 
│ ├─┬ gulp-concat@2.6.0 
│ │ ├── concat-with-sourcemaps@1.0.4 
│ │ └─┬ through2@0.6.5 
│ │   └── readable-stream@1.0.33 
│ ├─┬ gulp-if@2.0.0 
│ │ ├─┬ gulp-match@1.0.0 
│ │ │ └── minimatch@3.0.0 
│ │ ├─┬ ternary-stream@2.0.0 
│ │ │ └── through2@2.0.1 
│ │ └── through2@2.0.1 
│ ├─┬ is-relative-url@1.0.0 
│ │ └── is-absolute-url@1.0.0 
│ ├─┬ through2@0.6.5 
│ │ └── readable-stream@1.0.33 
│ ├── useref@1.1.2 
│ └─┬ vinyl-fs@2.3.4 
│   ├─┬ duplexify@3.4.3 
│   │ └── end-of-stream@1.0.0 
│   ├─┬ glob-stream@5.3.1 
│   │ ├── glob@5.0.15 
│   │ ├── micromatch@2.3.7 
│   │ ├─┬ ordered-read-streams@0.3.0 
│   │ │ └── is-stream@1.0.1 
│   │ ├─┬ to-absolute-glob@0.1.1 
│   │ │ └── extend-shallow@2.0.1 
│   │ └─┬ unique-stream@2.2.1 
│   │   └─┬ json-stable-stringify@1.0.1 
│   │     └── jsonify@0.0.0 
│   ├── is-valid-glob@0.3.0 
│   ├── lazystream@1.0.0 
│   ├─┬ lodash.isequal@4.1.0 
│   │ ├── lodash._root@3.0.1 
│   │ ├── lodash._stack@4.1.0 
│   │ └── lodash.keys@4.0.4 
│   ├── merge-stream@1.0.0 
│   ├── object-assign@4.0.1 
│   ├── strip-bom@2.0.0 
│   ├─┬ strip-bom-stream@1.0.0 
│   │ └── strip-bom@2.0.0 
│   ├── through2@2.0.1 
│   ├── through2-filter@2.0.0 
│   ├── vali-date@1.0.0 
│   └── vinyl@1.1.1 
├─┬ main-bower-files@2.11.1 
│ ├── extend@2.0.1 
│ ├── strip-json-comments@1.0.4 
│ └─┬ vinyl-fs@1.0.0 
│   ├─┬ glob-stream@4.1.1 
│   │ ├── glob@4.5.3 
│   │ └── unique-stream@2.2.1 
│   ├── glob-watcher@0.0.8 
│   ├── graceful-fs@3.0.8 
│   ├── object-assign@2.1.1 
│   ├─┬ through2@0.6.5 
│   │ └── readable-stream@1.0.33 
│   └─┬ vinyl@0.4.6 
│     └── clone@0.2.0 
└─┬ wiredep@2.2.2 
  ├─┬ bower-config@0.5.2 
  │ ├── graceful-fs@2.0.3 
  │ ├── mout@0.9.1 
  │ ├─┬ optimist@0.6.1 
  │ │ └── minimist@0.0.10 
  │ └── osenv@0.0.3 
  ├─┬ chalk@0.5.1 
  │ ├── ansi-styles@1.1.0 
  │ ├─┬ has-ansi@0.1.0 
  │ │ └── ansi-regex@0.2.1 
  │ ├── strip-ansi@0.3.0 
  │ └── supports-color@0.2.0 
  ├── glob@4.5.3 
  ├── lodash@2.4.2 
  ├── propprop@0.3.0 
  └─┬ through2@0.6.5 
    └── readable-stream@1.0.33 

bower bootstrap-sass#~3.3.5 not-cached git://github.com/twbs/bootstrap-sass.git#~3.3.5
bower bootstrap-sass#~3.3.5    resolve git://github.com/twbs/bootstrap-sass.git#~3.3.5
bower modernizr#~2.8.1      not-cached git://github.com/Modernizr/Modernizr.git#~2.8.1
bower modernizr#~2.8.1         resolve git://github.com/Modernizr/Modernizr.git#~2.8.1
bower modernizr#~2.8.1        download https://github.com/Modernizr/Modernizr/archive/v2.8.3.tar.gz
bower bootstrap-sass#~3.3.5   download https://github.com/twbs/bootstrap-sass/archive/v3.3.6.tar.gz
bower bootstrap-sass#~3.3.5    extract archive.tar.gz
bower bootstrap-sass#~3.3.5   resolved git://github.com/twbs/bootstrap-sass.git#3.3.6
bower jquery#>= 1.9.0           cached git://github.com/jquery/jquery-dist.git#2.2.1
bower jquery#>= 1.9.0         validate 2.2.1 against git://github.com/jquery/jquery-dist.git#>= 1.9.0
bower modernizr#~2.8.1         extract archive.tar.gz
bower modernizr#~2.8.1    invalid-meta modernizr is missing "main" entry in bower.json
bower modernizr#~2.8.1    invalid-meta modernizr is missing "ignore" entry in bower.json
bower modernizr#~2.8.1        resolved git://github.com/Modernizr/Modernizr.git#2.8.3
bower bootstrap-sass#~3.3.5    install bootstrap-sass#3.3.6
bower jquery#>= 1.9.0          install jquery#2.2.1
bower modernizr#~2.8.1         install modernizr#2.8.3

bootstrap-sass#3.3.6 bower_components/bootstrap-sass
└── jquery#2.2.1

jquery#2.2.1 bower_components/jquery

modernizr#2.8.3 bower_components/modernizr
bower chai#*                not-cached git://github.com/chaijs/chai.git#*
bower chai#*                   resolve git://github.com/chaijs/chai.git#*
bower mocha#*               not-cached git://github.com/mochajs/mocha.git#*
bower mocha#*                  resolve git://github.com/mochajs/mocha.git#*
bower chai#*                  download https://github.com/chaijs/chai/archive/3.5.0.tar.gz
bower mocha#*                 download https://github.com/mochajs/mocha/archive/v2.4.5.tar.gz
bower chai#*                   extract archive.tar.gz
bower chai#*                  resolved git://github.com/chaijs/chai.git#3.5.0
bower mocha#*                  extract archive.tar.gz
bower mocha#*                 resolved git://github.com/mochajs/mocha.git#2.4.5
bower chai#^3.5.0              install chai#3.5.0
bower mocha#^2.4.5             install mocha#2.4.5

chai#3.5.0 bower_components/chai

mocha#2.4.5 bower_components/mocha
