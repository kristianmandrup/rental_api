source 'https://rubygems.org'

gem 'rails', '~> 4.0.0.beta1'
gem 'rails-api'

# main engines
gem 'rent_property',         github: 'kristianmandrup/property'
gem 'rent_account',          github: 'kristianmandrup/rent_account'

gemspec

gem "rspec-rails", :group => [:test, :development]

group :test do  
  # time travel
  gem 'delorean',   '>= 1.1'

  gem 'cutter',     '>= 0.8.2'

  # data store
  gem 'database_cleaner',   '>= 0.8'

  # Fake data
  gem 'ffaker', '>= 1.14.1'
  gem 'fakeweb'

  gem 'shoulda'         
  gem 'shoulda-matchers'

  gem 'factory_girl_rails', :require => false
end
