source "https://rubygems.org"

# Use GitHub Pages gem to align all dependencies
# See https://pages.github.com/versions/
gem "github-pages", group: :jekyll_plugins

gem "jekyll-theme-architect"

# If you have any plugins, put them here!
group :jekyll_plugins do
  gem "jekyll-feed"
end

# Windows and JRuby does not include zoneinfo files, so bundle the tzinfo-data gem
# and associated library.
platforms :mingw, :x64_mingw, :mswin, :jruby do
  gem "tzinfo", ">= 1", "< 3"
  gem "tzinfo-data"
end

gem "wdm", "~> 0.1", :platforms => [:mingw, :x64_mingw, :mswin]
gem "http_parser.rb", "~> 0.6.0", :platforms => [:jruby]

gem 'jekyll'
gem 'jekyll-paginate'
gem 'kramdown'
gem 'webrick', '~> 1.9'
