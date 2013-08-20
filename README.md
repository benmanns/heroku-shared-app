# SharedApp

This is an example app that demonstrates using Postgres schemas to host two environments on the same Heroku Postgres database instance. See the [StackOverflow answer](http://stackoverflow.com/a/18345480/234944) for more information.

This app is particularly boring, as there was really no modifications necessary to get an app running on a separate schema.

The apps are currently running on Heroku.

* Production: http://test-shared-app.herokuapp.com/posts
* Staging: http://test-shared-app-staging.herokuapp.com/posts
