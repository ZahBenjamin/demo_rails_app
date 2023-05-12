source "https://rubygems.org"
git_source(:github) { |repo| "https://github.com/#{repo}.git" }

ruby "3.1.2"

gem "rails", "~> 7.0.4"
gem "bootstrap-sass", "3.4.1"
gem "sassc-rails", "2.1.2"
gem "sprockets-rails", "3.4.2"
gem "importmap-rails", "1.1.0"
gem "turbo-rails", "1.1.1"
gem "stimulus-rails", "1.0.4"
gem "jbuilder"
gem "puma", "5.6.4"
# gem "tzinfo-data", platforms: %i[ mingw mswin x64_mingw jruby ]  uncomment line if on a native Windows system
gem "bootsnap", require: false


group :development, :test do
  gem "debug", platforms: %i[ mri mingw x64_mingw ]
  gem "sqlite3", "~> 1.4"

end

group :development do
  gem "web-console", "4.2.0"

end

group :test do
  gem "capybara",                 "3.37.1"
  gem "selenium-webdriver",       "4.2.0"
  gem "webdrivers",               "5.0.0"
  gem "rails-controller-testing", "1.0.5"
  gem "minitest",                 "5.15.0"
  gem "minitest-reporters",       "1.5.0"
  gem "guard",                    "2.18.0"
  gem "guard-minitest",           "2.4.6"
end

group :production do
  gem "pg", "1.3.5"
end