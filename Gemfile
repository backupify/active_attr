source "https://rubygems.org"

gemspec :development_group => :test

if RUBY_VERSION < "1.9.2"
  gem "factory_girl", "< 3.0", :group => :test
end

gem "activemodel",   "~> 3.2.0"
gem "activesupport", "~> 3.2.0"
gem "strong_parameters", ">= 0.2.0", :group => :test

group :development do
  gem "debugger",  :platforms => :mri_19
  gem "growl"
  gem "guard"
  gem "guard-bundler"
  gem "guard-rspec"
  gem "rb-fsevent"
  gem "rdiscount"
  gem "rdoc"
  gem "ruby-debug", :platforms => :mri_18
  gem "spec_coverage", :platforms => :mri_19
  gem "travis-lint"
  gem "yard"
end
