source 'https://rubygems.org'

ruby '2.2.2', :engine => 'jruby', :engine_version => '9.0.0.0'

gem 'rails', '4.2.5'
gem 'activerecord-jdbcsqlite3-adapter'
gem 'sass-rails', '~> 5.0'
gem 'uglifier', '>= 1.3.0'
gem 'coffee-rails', '~> 4.1.0'
gem 'therubyrhino'
gem 'jquery-rails'
gem 'turbolinks'
gem 'jbuilder', '~> 2.0'
gem 'sdoc', '~> 0.4.0', group: :doc
gem 'sprockets-rails', '2.3.3' 
gem "puma"
gem "paperclip-ffmpeg", "~> 1.0.1"
gem "paperclip"
gem 'devise'
gem 'friendly_id', '~> 5.1.0' 
gem "omniauth-twitter"
gem "omniauth-facebook"
gem 'aws-sdk', '< 2.0'


group :production do
	gem "rails_12factor"
	gem 'activerecord-jdbcpostgresql-adapter'
end

group :development do
	gem "better_errors"
	gem "meta_request"
end

gem 'tzinfo-data', platforms: [:mingw, :mswin, :x64_mingw, :jruby]
