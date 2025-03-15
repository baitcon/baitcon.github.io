source "https://rubygems.org"

# Use github pages as a metadependancy to get all the jekyll things
gem 'github-pages'

# Any extra plugins go here
group :jekyll_plugins do
  gem "jekyll-feed", "~> 0.6"
end

# Windows and JRuby does not include zoneinfo files, so bundle the tzinfo-data gem
# and associated library.
platforms :mingw, :x64_mingw, :mswin, :jruby do
  gem "tzinfo", ">= 1", "< 3"
  gem "tzinfo-data"
end
