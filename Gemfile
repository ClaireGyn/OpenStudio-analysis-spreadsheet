source "http://rubygems.org"

gem "rake", "~> 10.1.0"
gem "rubyzip", "~> 1.1.0"

# uncomment if you need to update the bcl measures
#gem "bcl", "~> 0.3.7"

gem "openstudio-aws", "~> 0.1.13" 
#gem "openstudio-aws", :git => "git@github.com:NREL/OpenStudio-aws-gem.git"
#gem "openstudio-aws", :path => "../OpenStudio-aws-gem"

gem "openstudio-analysis", "~> 0.1.8"
#gem "openstudio-analysis", :path => "../OpenStudio-analysis-gem"

gem "colored", "~> 1.2"

if RUBY_PLATFORM =~ /win32/
  gem "win32console", "~> 1.3.2", :platform => [:mswin, :mingw]
end

group :test do
  gem "rspec", "~> 2.12"
  gem "ci_reporter", "~> 1.9.0"
end

