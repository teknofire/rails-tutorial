# Quick and Dirty Rails Tutorial

This is an example repo that we will use to quickly cover how to create rails applications.  This tutorial will is going to cover the latest Rails version at the time (4.2.0)

## Things you will need

* Working knowledge of ruby
* Ruby (2.x)
* Bundler and Rails (4.2+) gems

## Handy Resources

* Rails Guides
* ApiDock.com
* CodeSchool (Rails for Zombies)

## Tutorial Outline

* Overview of Rails
  * MVC
  * Configuration vs. Convention
  * Databases and ORMs
    * Choosing a database - mysql, postgresql, sqlite, etc...
    * ActiveRecord - singular models, plural db tables, reserved words, etc...
    * Other ORMS (mongodb, datamapper, etc..)
  * Environments (development, test, production)
  * Resources
    * Creating, Reading, Updating and Deleting (CRUD)
  * Testing
* Installing
  * Ruby
  * Bundler
  * Rails gem
* Starting a new rails application
  * Structure of a rails application
    * app
      * controller
      * models
      * views
      * assets
      * concerns
    * config
    * lib
  * cmdline tools
    * bundle
    * rails console
    * rails generate
    * rake
  * Creating a resource (model, views and controllers)
    * Examine the database migrations
    * Examine the tests
    * Examine the controller
    * Examine the views
    * Examine the model
  * Improving the resource!
    * Use some view helpers
    * Handling errors
    * Pagination
    * Assets (images, scss, coffeescript)
  * Advanced topics as time permits
    * Additional libraries (haml, guard, etc...)
    * SCSS, CoffeeScript
    * Asset pipeline (precompiling)
    * Transactions
    * Caching
    * Uploading files
    * Deploying
