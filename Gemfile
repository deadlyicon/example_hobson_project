source "http://rubygems.org"

gemspec

group :development, :test do
  gem "ruby-debug",   :platform => :ruby_18
  # The next two are needed by ruby-debug when running in 1.9.3
  gem 'linecache19', :git => 'git://github.com/mark-moseley/linecache', :platform => :ruby_19
  gem 'ruby-debug-base19x', '~> 0.11.30.pre4', :platform => :ruby_19
  gem "ruby-debug19", :platform => :ruby_19
end

group :test do
  gem 'rspec'
  gem 'cucumber'
end
