# README

This README would normally document whatever steps are necessary to get the
application up and running.

Things you may want to cover:

* Ruby version

* System dependencies

* Configuration

* Database creation

* Database initialization

* How to run the test suite

* Services (job queues, cache servers, search engines, etc.)

* Deployment instructions

* ...


Full command	Shortcut
$ rails server	$ rails s
$ rails console	$ rails c
$ rails generate	$ rails g
$ rails test	$ rails t
$ bundle install	$ bundle


- note that we have passed the controller name as CamelCase (so called because it resembles the humps of a Bactrian camel), which leads to the creation of a controller file written in snake case, so that a controller called StaticPages yields a file called static_pages_controller.rb. 
- About page titles have a variable component, we’ll use a special Rails function called provide to set a different title on each page.

