source "https://rubygems.org"

ruby IO.read(File.expand_path("#{File.dirname(__FILE__)}/.ruby-version")).strip

gem "rack"
gem "json"
gem "unicorn"

group :development do
  gem "guard-process"
  gem "travis-lint"
end

group :test do
  gem "minitest"
  gem "rake"
  gem "rack-test"
  gem "simplecov"
end
