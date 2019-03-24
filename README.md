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
- Ruby won’t interpolate into single-quoted strings
- Everything in Ruby, including strings and even nil, is an object.
- Note the question mark at the end of the empty? method. This is a Ruby convention indicating that the return value is boolean: true or false.
- the nil object is special, in that it is the only Ruby object that is false in a boolean context
- `a = [42, 8, 17]`
  `a << "foo" << "bar" `
  `(0..9).to_a`
  `a[0..2]`
- `(1..5).each do |number|` ; `3.times { puts "Betelgeuse!" } ` ; `(1..5).map { |i| i**2 }` ; `%w[A B C].map(&:downcase)`
- `user = { :name => "Michael Hartl", :email => "michael@example.com" }`
- `attr_accessor :name, :email`, creates “getter” and “setter” methods that allow us to retrieve (get) and assign (set) @name and @email instance variables
- 

app/assets: assets specific to the present application
lib/assets: assets for libraries written by your dev team
vendor/assets: assets from third-party vendors





