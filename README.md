# laravel_5.1-angularjs-Todo-project

OVERVIEW

This is a starter project that gives you an out of the box configuration Laravel 5.1 and AngularJS (folder by feature architecture). Here are the goodies that you'll get:

Laravel 5.1
Angular
Angular Material
Blazing fast Elixir 3.0 configuration with custom tasks
artisan generators for angular (artisan ng:feature name, artisan ng:dialog name, etc..)
check out the full list of features

Installation

Heads up for Windows + Vagrant users: Start by applying the fix in issue #61

composer create-project jadjoubran/laravel5-angular-material-starter --prefer-dist
cd laravel5-angular-material-starter
#fix database credentials in .env
npm install -g gulp bower
npm install
bower install
gulp && gulp watch
php -S localhost:8080 public
You're ready to go! http://localhost:8000
