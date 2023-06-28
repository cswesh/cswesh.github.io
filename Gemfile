# frozen_string_literal: true

source "https://rubygems.org"

# gem "jekyll-theme-chirpy", "~> 5.2", ">= 5.2.1"
gem 'jekyll-theme-chirpy', '~> 6.0', '>= 6.0.1'

# group :test do
  gem 'html-proofer', '~> 5.0', '>= 5.0.7'
# end

# Windows and JRuby does not include zoneinfo files, so bundle the tzinfo-data gem
# and associated library.
install_if -> { RUBY_PLATFORM =~ %r!mingw|mswin|java! } do
  gem "tzinfo", "~> 1.2"
  gem "tzinfo-data"
end

# Performance-booster for watching directories on Windows
gem "wdm", "~> 0.1.1", :install_if => Gem.win_platform?

# Jekyll <= 4.2.0 compatibility with Ruby 3.0
gem 'webrick', '~> 1.8', '>= 1.8.1'
gem 'jekyll-seo-tag', '~> 2.8'
gem 'sass-embedded', '~> 1.63', '>= 1.63.4'