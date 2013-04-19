source "https://rubygems.org"

gemspec :name => ""

gem 'rdf', :git => 'http://github.com/ruby-rdf/rdf', :branch => '1.1'
gem 'rdf-spec', :git => 'http://github.com/ruby-rdf/rdf-spec', :branch => '1.1'

group :development do
  gem 'simplecov', :platforms => [:mri_19, :jruby]
end

group :debug do
  gem 'debugger', :platform => :ruby_19
  gem 'ruby-debug', :platform => :ruby_18
end

gem 'ffi', '~> 1.3.1', :platforms => [:rbx]