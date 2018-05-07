# awesome-live-reloading [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)

A curated collection of `live-reloading` tools and libraries associated with different languages and frameworks.

"Live reloading" refers to tools that run your compile/build step as you write code. This makes it faster for you test your work as you write code. This is especially helpful for web development.

## C
  - [**cr.h**](https://github.com/fungos/cr)
    - [Blog](https://fungos.github.io/blog/2017/11/20/cr.h-a-simple-c-hot-reload-header-only-library/)

## C++
  - [**RuntimeCompiledCPlusPlus**](https://github.com/RuntimeCompiledCPlusPlus/RuntimeCompiledCPlusPlus)
    - [Blog](https://github.com/RuntimeCompiledCPlusPlus/RuntimeCompiledCPlusPlus/wiki)
    - [openFrameworks binding](https://github.com/ofnode/ofLiveApp)
  - [**JUCE Projucer**](https://juce.com/discover/projucer)
  - [**RCRL - Read-Compile-Run-Loop**](https://github.com/onqtam/rcrl) - tiny and powerful interactive C++ compiler (REPL)

## ClojureScript
  - [**shadow-cljs**](http://shadow-cljs.org/)
  - [**Figwheel**](https://github.com/bhauman/lein-figwheel)
  - [**boot-reload**](https://github.com/adzerk-oss/boot-reload)

## Go
  - [**Gin**](https://github.com/codegangsta/gin)
    - [Readme](https://github.com/codegangsta/gin/blob/master/README.md)
  - [**Realize**](https://github.com/oxequa/realize)
    - [Readme](https://github.com/oxequa/realize/blob/master/README.md)

## Haskell
  - `stack build --file-watch` flag
    - [Documentation](https://docs.haskellstack.org/en/stable/build_command/#flags)

## Java and other JVM languages (Kotlin, Scala, Groovy etc.)
  - [**DCEVM**](https://github.com/dcevm/dcevm)
    - [Beta for Java9](https://github.com/HotswapProjects/openjdk-jdk9)
  - [**HotSwapAgent**](https://github.com/HotswapProjects/HotswapAgent)
    - [In Docker](https://github.com/HotswapProjects/hotswap-docklands)
    - [Blog](https://blog.payara.fish/using-hotswapagent-to-speed-up-development)

## JavaScript
  - NodeJS
    - [**nodemon**](https://github.com/remy/nodemon)
      - [Blog](https://hackernoon.com/nodemon-example-tutorial-npm-start-script-auto-watch-47cd702fe442)
  - ReactJS
    - [**React Hot Reload**](https://github.com/gaearon/react-hot-loader)
      - [Blog](http://gaearon.github.io/react-hot-loader/getstarted/)
  - AngularJS
    - [**Webpack**](https://github.com/webpack/webpack)
      - [Blog](https://damienbod.com/2017/02/01/hot-module-replacement-with-angular-2-and-webpack/)
  - VueJS
    - [**Vue Loader**](https://github.com/vuejs/vue-loader)
      - [Blog](https://vue-loader.vuejs.org/guide/hot-reload.html)
  - EmberJS
    - [**Ember-CLI**](https://ember-cli.com/)
      - [Docs](https://github.com/ember-cli/ember-cli-inject-live-reload)
  - QuokkaJS
    - [**Quokka.js**](https://quokkajs.com/docs/configuration.html)
  - VanillaJS
    - [**Hot-Server**](https://github.com/1wheel/hot-server)
      - [Blog](https://roadtolarissa.com/hot-reload/)
    - [**Live-Server**](https://github.com/tapio/live-server)
      - [Web](http://tapiov.net/live-server/)

## Julia
  - [**Revise.jl**](https://github.com/timholy/Revise.jl)
    - [Readme](https://github.com/timholy/Revise.jl/blob/master/README.md)

## Lua
  - [**info-beamer (pi)**](https://info-beamer.com/pi)
     - [Documentation](https://info-beamer.com/doc/info-beamer)

## Python
  - Gunicorn
    - [Docs](http://docs.gunicorn.org/en/stable/settings.html#debugging)
  - Flask
    - [Docs](http://flask.pocoo.org/docs/0.12/quickstart/#debug-mode)
  - Django
    - [**django-webpack-loader**](https://github.com/owais/django-webpack-loader)
      - [Blog](https://owais.lone.pw/blog/webpack-plus-reactjs-and-django/)
  - Hupper
    - Just use `hupper -m script` instead of `python -m script`.
    - [Docs](https://docs.pylonsproject.org/projects/hupper/en/latest/)
  - Pyramid
    - [Docs](https://docs.pylonsproject.org/projects/pyramid/en/1.9-branch/pscripts/pserve.html)
      - [Blog](https://owais.lone.pw/blog/webpack-plus-reactjs-and-django/)
  - [Watchdog](https://github.com/gorakhargosh/watchdog)

## PureScript
  - [**Parcel**](https://github.com/parcel-bundler/parcel)
    - [Blog](https://qiita.com/kimagure/items/a870d250f75a6822759b)

## Qt QML
  - [**QML Live Reloading**](https://doc.qt.io/QtQmlLive/index.html)
  - [**Terrarium**](https://github.com/penk/terrarium-app)
  - [**V-Play**](https://v-play.net/)
    - [Blog](https://v-play.net/updates/release-2-14-0-live-code-reloading-for-desktop-ios-android)

## Ruby
  - Sinatra
    - [**rerun**](https://github.com/alexch/rerun)
      - [Instructions](http://sinatrarb.com/faq.html#reloading)
  - Rails
    - [**Webpack**](https://github.com/webpack/webpack)
      - [Blog](https://medium.com/@hpux/rails-5-1-loves-javascript-a1d84d5318b)

## .NET
  - [**dotnet watch**](https://github.com/aspnet/DotNetTools/blob/dev/src/dotnet-watch/README.md)
    - [Blog](https://docs.microsoft.com/en-us/aspnet/core/tutorials/dotnet-watch?view=aspnetcore-2.1)

## Mobile

  - iOS
    - [**injectionforxcode**](https://github.com/johnno1962/injectionforxcode)
  - Cross Platform
    - Flutter
      - [**Hot Reload**](https://flutter.io/hot-reload/)
    - React Native
      - [Blog](https://facebook.github.io/react-native/blog/2016/03/24/introducing-hot-reloading.html)
<br>
<br>
<sup>Made with ♡♡love♡♡ by [Hasura](https://hasura.io)</sup>
<br>
<sup>This list originated when we were creating documentation for live-reloading your local code changes, to your cloud dev/staging environment directly. There are a lot of new tools coming out that make this trend popular ([Hasura](https://hasura.io), [ksync](https://github.com/vapor-ware/ksync), [Skaffold](https://github.com/GoogleContainerTools/skaffold) ). We then realised that there was no central repo of "live-reloading" tools for different languages/frameworks and decided to curate this. </sup>
