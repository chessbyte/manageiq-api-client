source 'https://rubygems.org'

# Specify your gem's dependencies in manageiq-api-client.gemspec
gemspec

group :test do
  gem "webmock"
  gem "simplecov", :require => false
end

# Load developer specific Gemfile
dev_gemfile = File.expand_path("Gemfile.dev.rb", __dir__)
eval_gemfile(dev_gemfile) if File.exist?(dev_gemfile)
