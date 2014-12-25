
[![Build Status](https://travis-ci.org/kwgch/sample_app.png)](https://travis-ci.org/kwgch/sample_app)
[![Coverage Status](https://coveralls.io/repos/kwgch/sample_app/badge.png)](https://coveralls.io/r/kwgch/sample_app)
[![Dependency Status](https://gemnasium.com/kwgch/sample_app.png)](https://gemnasium.com/kwgch/sample_app)
[![Stories in Ready](https://badge.waffle.io/kwgch/sample_app.png?label=ready&title=Ready)](https://waffle.io/kwgch/sample_app)

## Ruby on Rails チュートリアル：サンプルアプリケーション

[![Gitter](https://badges.gitter.im/Join%20Chat.svg)](https://gitter.im/ducky19999/sample_app?utm_source=badge&utm_medium=badge&utm_campaign=pr-badge&utm_content=badge)

これは、以下のためのサンプルアプリケーションです。
[*Ruby on Rails Tutorial*](http://railstutorial.jp/)
by [Michael Hartl](http://michaelhartl.com/).


新しい開発環境からHEROKUに上げるとき
```
$ heroku git:remote --app kwgch-sample-app
$ heroku keys:add
$ heroku push heroku
$ heroku pg:reset DATABASE
$ heroku run rake db:migrate
$ heroku run rake db:populate
```
