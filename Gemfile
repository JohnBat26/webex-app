source 'https://rubygems.org'

gem 'rails', '3.2.2'
#gem 'json'
#gem 'rails_best_practices'

# Gems used only for assets and not required
# in production environments by default.
group :assets do
  gem 'execjs'
  gem "therubyracer" #, "~> 0.8.2.pre" #bleeding edge.
  gem 'sass-rails'
  gem 'coffee-rails'
  gem 'uglifier'
end


gem "jquery-rails"
gem "rspec-rails", ">= 2.8.1", :group => [:development, :test]
gem 'sqlite3',:group => [:development, :test]
gem "annotate",:group => [:development, :test]
gem "spork",:group => [:development, :test]
gem "simplecov",:group => [:development, :test]
gem "machinist", :group => :test
gem "factory_girl_rails", ">= 1.7.0", :group => :test
gem "email_spec", ">= 1.2.1", :group => :test
gem "cucumber-rails", ">= 1.3.0", :group => :test
gem "capybara", ">= 1.1.2", :group => :test
gem "database_cleaner", ">= 0.7.1", :group => :test
gem "launchy", ">= 2.0.5", :group => :test
gem "devise", ">= 2.0.4"
gem "devise-russian"
gem "bootstrap-sass"
gem "simple_form"

# To use Jbuilder templates for JSON
# gem 'jbuilder'

# Use unicorn as the web server
# gem 'unicorn'

# Deploy with Capistrano
# gem 'capistrano'

# To use debugger
# gem 'ruby-debug19', :require => 'ruby-debug'

#gem 'ruby-debug19', :require => 'ruby-debug', :group => :development
# To use debugger
gem 'linecache19', '0.5.13', :path => "~/.rvm/gems/ruby-1.9.3-p125@webex/gems/linecache19-0.5.13/"
gem 'ruby-debug-base19', '0.11.26', :path => "~/.rvm/gems/ruby-1.9.3-p125@webex/gems/ruby-debug-base19-0.11.26/"

gem 'ruby-debug19', :require => 'ruby-debug', :group => :development

group :production do
  gem 'pg'
  gem 'sqlite3'
end