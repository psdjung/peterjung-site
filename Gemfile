# frozen_string_literal: true
# Gemfile
ruby "3.4.5"
source "https://rubygems.org"

gem "jekyll",              "~> 4.3"
gem "jekyll-theme-chirpy", "~> 7.3"
gem "html-proofer",        "~> 5.0", group: :test

gemspec

platforms :mingw, :x64_mingw, :mswin, :jruby do
  gem "tzinfo", ">= 1", "< 3"
  gem "tzinfo-data"
end

gem "wdm", "~> 0.2.0", :platforms => [:mingw, :x64_mingw, :mswin]
