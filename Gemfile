source 'https://rubygems.org'

gem 'rails', '~> 5.0.0', '>= 5.0.0.1'

gem 'puma', '~> 3.0'
# Use SCSS for stylesheets
gem 'sass-rails', '~> 5.0'
gem 'uglifier', '>= 1.3.0'
gem 'coffee-rails', '~> 4.2'
gem 'execjs', '~> 2.6'
gem 'jquery-rails'
gem 'turbolinks', '~> 5'
# Build JSON APIs with ease. Read more: https://github.com/rails/jbuilder
gem 'jbuilder', '~> 2.5'
gem 'bcrypt', '~> 3.1', '>= 3.1.11'
group :development, :test do
  gem 'mysql2', '>= 0.3.18', '< 0.5'
  gem 'byebug', platform: :mri
  gem 'ffaker', :git => 'https://github.com/EmmanuelOga/ffaker.git'
  gem 'byebug', platform: :mri
  gem 'factory_girl_rails'
  gem 'rspec-rails'
  gem 'shoulda-matchers'
  gem 'rubocop', '~> 0.42.0' , require: false
end
platforms :ruby do # linux
 # gem 'unicorn'
  gem 'sitemap_generator'
end
group :development do
  # Access an IRB console on exception pages or by using <%= console %> anywhere in the code.
  gem 'web-console'
end
group :production do
  gem 'rails_12factor'
  gem 'pg'
end

# Windows does not include zoneinfo files, so bundle the tzinfo-data gem
gem 'tzinfo-data', platforms: [:mingw, :mswin, :x64_mingw, :jruby]
