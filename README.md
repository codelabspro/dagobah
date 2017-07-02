# dagobah

## Links

http://rubyonrails.org/

https://cloud.google.com/ruby/rails/using-cloudsql

## Steps
==> ruby --version ruby 2.4.0p0 (2016-12-24 revision 57164) [x86_64-darwin16]


==> rails --version Rails 5.1.2


Create app using
rails new opendatamatic


Run local server using
bin/rails server

bundle exec rails generate controller WelcomeMain index

Add the following to config/routes.rb before end

root 'welcome_main#index' 
