source "https://rubygems.org"

# Use the GitHub Pages supported stack (recommended for deployment on Pages)
gem "github-pages", group: :jekyll_plugins

# Keep webrick for local serve on Ruby 3+
gem "webrick"

group :jekyll_plugins do
  gem "jekyll-feed"
end

# Windows and JRuby does not include zoneinfo files, so bundle the tzinfo-data gem
# and associated library.
install_if -> { RUBY_PLATFORM =~ %r!mingw|mswin|java! } do
  gem "tzinfo", "~> 1.2"
  gem "tzinfo-data"
end

# Performance-booster for watching directories on Windows
gem "wdm", :install_if => Gem.win_platform?