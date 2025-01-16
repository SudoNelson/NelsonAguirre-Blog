# Hello! This is where you manage which Jekyll version is used to run.
# When you want to use a different version, change it below, save the
# file and run `bundle install`. Run Jekyll with `bundle exec`, like so:
#
#     bundle exec jekyll serve
#

source "https://rubygems.org"

gem 'jekyll', '~> 4.3.4'  # Específica la versión de Jekyll para evitar incompatibilidades

# Gemas estándar que podrías necesitar explícitamente debido a advertencias
gem 'erb', require: false
gem 'ostruct', require: false
gem 'csv', require: false
gem 'base64', require: false
gem 'json', require: false

group :jekyll_plugins do
    gem 'jekyll-feed'
    gem 'jekyll-sitemap'
    gem 'jekyll-paginate'
    gem 'jekyll-seo-tag'
    gem 'jekyll-archives'
    gem 'kramdown'
    gem 'rouge'
end

# Solo necesario en plataformas Windows
gem 'wdm', '>= 0.1.0' if Gem.win_platform?
