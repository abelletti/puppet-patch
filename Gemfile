source ENV['GEM_SOURCE'] || "https://rubygems.org"

group :development, :test do
  gem 'rake', :require => false
  gem 'rspec-puppet', :require => false
  gem 'puppetlabs_spec_helper', :require => false
  gem 'puppet-syntax', :require => false
  gem 'puppet-lint', :require => false
end

if puppetversion = ENV['PUPPET_VERSION']
  gem 'puppet', puppetversion, :require => false
else
  gem 'puppet', :require => false
end

# vim:ft=ruby
