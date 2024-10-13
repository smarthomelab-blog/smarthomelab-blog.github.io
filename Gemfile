# frozen_string_literal: true

source "https://rubygems.org"

gem "jekyll-theme-chirpy", "~> 7.1", ">= 7.1.1"

gem "html-proofer", "~> 5.0", group: :test

git_source(:github) { |repo_name| "https://github.com/smarthomelab-blog/smarthomelab-blog.github.io" }

gem "github-pages", group: :jekyll_plugins

platforms :mingw, :x64_mingw, :mswin, :jruby do
  gem "tzinfo", ">= 1", "< 3"
  gem "tzinfo-data"
end

gem "wdm", "~> 0.1.1", :platforms => [:mingw, :x64_mingw, :mswin]
