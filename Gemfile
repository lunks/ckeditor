source "http://rubygems.org"

gemspec

gem "rails", "4.0.0"

platforms :ruby do
  gem "sqlite3"
  gem 'jquery-rails'

  group :development do
    gem "unicorn", "~> 4.0.1"
  end

  group :development, :test do
    gem "capybara", ">= 0.4.0"
    gem "mynyml-redgreen", "~> 0.7.1", :require => 'redgreen'
  end

  group :active_record do
    gem "paperclip", "> 3.0.3"
    gem "carrierwave", "~> 0.9.0"
    gem "dragonfly"
    gem "mini_magick"
  end

  group :mongoid do
    gem "mongoid", github: 'mongoid/mongoid'
    gem "bson_ext"
    gem 'mongoid-paperclip', :require => 'mongoid_paperclip'
    gem 'carrierwave-mongoid', :require => 'carrierwave/mongoid'
  end
end
