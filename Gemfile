source :rubygems

# add in all the runtime dependencies

gem 'rails', '>= 3.0.7'

gem 'warden'
gem 'devise', '= 1.1.3'

gem 'mongoid', '~> 2.0.1'
gem 'bson_ext', '~> 1.3.0'
gem 'locomotive_mongoid_acts_as_tree', '0.1.5.5', :require => 'mongoid_acts_as_tree'
gem 'will_paginate'

gem 'haml', '3.0.25'
gem 'locomotive_liquid', '2.2.2', :require => 'liquid'
gem 'formtastic', '~> 1.2.3'
gem 'inherited_resources', '~> 1.1.2'

gem 'rmagick', '2.13.2'
gem 'locomotive_carrierwave', '0.5.0.1.beta3', :require => 'carrierwave'

gem 'custom_fields', '1.0.0.beta.12'
gem 'fog', '0.3.7'
gem 'mimetype-fu'
gem 'actionmailer-with-request', :require => 'actionmailer_with_request'
gem 'heroku', '1.19.1'
gem 'bushido'
gem 'httparty', '>= 0.6.1'
gem 'RedCloth', '4.2.9'
gem 'delayed_job', '2.1.4'
gem 'delayed_job_mongoid', '1.0.2'
gem 'rubyzip'
gem 'locomotive_jammit-s3', :require => 'jammit-s3'
gem 'SystemTimer', :platforms => :ruby_18

# The rest of the dependencies are for use when in the locomotive dev environment

group :development do
  # Using unicorn_rails instead of webrick (default server)
  gem 'unicorn'
end

group :test, :development do
  gem "ruby-debug", :platforms => :mri_18
  gem "ruby-debug19", :platforms => :mri_19
end

group :test do
  gem 'autotest'
  gem 'ZenTest'
  gem 'growl-glue'
  gem 'rspec-rails', '2.3.1'
  gem 'factory_girl_rails'
  gem 'pickle'
  gem 'xpath',            :git => 'https://github.com/wunderbread/xpath.git'
  gem 'capybara'

  gem 'database_cleaner'
  gem 'cucumber', '0.8.5'
  gem 'cucumber-rails'
  gem 'spork'
  gem 'launchy'
  gem 'mocha', :git => 'git://github.com/floehopper/mocha.git'
end
