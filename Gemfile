source 'https://rubygems.org'
require 'json'
require 'open-uri'
versions = JSON.parse(open('https://pages.github.com/versions.json').read)
gem 'jekyll'
gem 's3_website'
gem 'jekyll-assets'
gem 'yui-compressor'
gem 'psych'
gem 'github-pages', versions['github-pages']
