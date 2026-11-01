# frozen_string_literal: true

source 'https://rubygems.org'

# needed for Jekyll
gem 'jekyll'
gem 'webrick'
gem 'logger'
gem 'base64'
gem 'ostruct'

# needed for Rake tasks
gem 'rake'
gem 'csv'
gem 'fileutils'
gem 'mini_magick'
unless Gem.win_platform?
  gem 'image_optim'
  gem 'image_optim_pack'
end

group :jekyll_plugins do
  # static IIIF: info.json and the item manifests at build time (see static_iiif: in _config.yml)
  gem 'static_iiif', git: 'https://github.com/nakamura196/static_iiif.git', ref: 'f67712315a6a3a928b141511f4a457b5576a8d8b', require: 'static_iiif/jekyll'
end
