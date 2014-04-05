source 'https://rubygems.org'
ruby '2.0.0'


gem 'rails', '4.0.0'
gem 'sass-rails', '~> 4.0.0'
gem 'uglifier', '>= 1.3.0'
gem 'coffee-rails', '~> 4.0.0'
gem 'jquery-rails'
gem 'turbolinks'
gem 'jquery-turbolinks'
gem 'jbuilder', '~> 1.2'
gem 'bootstrap-sass', '~> 3.1.1'
gem 'devise', '~> 3.2.4'
gem 'paperclip', '~> 3.0'
gem 'aws-sdk', '~> 1.38.0'
gem 'masonry-rails', '~> 0.2.1'

group :development, :test do
# Use sqlite3 as the database for Active Record
	gem 'sqlite3'
end

group :production do
# use postgres for heroku
	gem 'pg'
	gem 'rails_12factor'
end


group :doc do
  # bundle exec rake doc:rails generates the API under doc/api.
  gem 'sdoc', require: false
end
