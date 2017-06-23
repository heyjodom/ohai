source "https://rubygems.org"

gemspec

if Gem::Version.new(RUBY_VERSION) < Gem::Version.new("1.9.3")
  gem "mixlib-shellout", "~> 1.4.0"
end

group :development do

  gem "sigar", :platform => "ruby"
  gem 'plist'

  # gem 'pry-debugger'
  # gem 'pry-stack_explorer'
end


