source "https://rubygems.org"

gem "jekyll", "~> 3.9"

# If you have any plugins, put them here!
group :jekyll_plugins do
  gem 'github-pages'
end

# Windows and JRuby does not include zoneinfo files, so bundle the tzinfo-data gem
# and associated library.
platforms :mingw, :x64_mingw, :mswin, :jruby do
  gem "tzinfo", ">= 1", "< 3"
  gem "tzinfo-data"
end

# Performance-booster for watching directories on Windows
gem "wdm", "~> 0.1.1", :platforms => [:mingw, :x64_mingw, :mswin]

# Lock `http_parser.rb` gem to `v0.6.x` on JRuby builds since newer versions of the gem
# do not have a Java counterpart.
gem "http_parser.rb", "~> 0.6.0", :platforms => [:jruby]

# Jekyll theme
gem "bulma-clean-theme", "~> 0.13.3"

gem "webrick", "~> 1.8"
gem "pathutil", github: "sdogruyol/pathutil", ref: '6ab144a7706c2bc5fa0dfdfa498e94ff66e944c6'
