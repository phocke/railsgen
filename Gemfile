# Edit this Gemfile to bundle your application's dependencies.
source 'http://rubygems.org'

gem "rails", :git => "git://github.com/rails/rails.git"

gem "haml"
gem "compass", ">= 0.10.0.rc1"

gem "better_partials", ">= 1.0.1"
gem "viewfu", ">= 1.0.1"

gem "mongoid", :git => "git://github.com/durran/mongoid.git"
gem "bson_ext", ">= 1.0"

gem "devise", :git => "git://github.com/plataformatec/devise.git" #:path => "~/Gems/devise"

gem "jammit", :git => "http://github.com/documentcloud/jammit.git"

group :production, :staging do
  # required for getting sass to work with heroku
  gem "hassle", :git => "git://github.com/railsjedi/hassle.git"
end

group :development, :test do
  gem "ruby-debug"
  gem "mongrel"
end

group :test do
  gem "rspec-rails", ">= 2.0.0.beta"
  gem 'capybara'
  gem 'database_cleaner'
  gem 'cucumber-rails'
  gem "factory_girl", :require => nil
end
