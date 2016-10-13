source 'https://rubygems.org'

require 'json'
require 'open-uri'
versions = JSON.parse(open('https://pages.github.com/versions.json').read)

gem 'pygments.rb'
gem 'classifier-reborn'
gem 'jekyll'
gem 'github-pages', versions['github-pages']
