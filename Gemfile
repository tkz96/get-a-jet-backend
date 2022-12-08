source 'https://rubygems.org'
git_source(:github) { |repo| "https://github.com/#{repo}.git" }

ruby '3.1.2'

gem 'bootsnap', require: false
gem 'cancancan', '~> 3.4'
gem 'devise', '~> 4.8'
gem 'pg', '~> 1.1'
gem 'puma', '~> 5.0'
gem 'rack-cors'
gem 'rails', '~> 7.0.4'
gem 'rubocop', '~> 1.39'
gem 'tzinfo-data', platforms: %i[mingw mswin x64_mingw jruby]
# use Json Web Token for authentication
gem 'jwt'
# use ActiveModel has_secure_password
gem 'bcrypt', '~> 3.1.7'

group :development, :test do
  gem 'capybara', '~> 3.38'
  gem 'debug', platforms: %i[mri mingw x64_mingw]
  gem 'rspec', '~> 3.12'
end
