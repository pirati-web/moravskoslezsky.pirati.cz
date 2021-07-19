source "https://rubygems.org"

gem "jekyll", "~> 3.9"
gem "jekyll-theme-pirati", "~>7.7"

group :jekyll_plugins do
  gem "jekyll-feed"
  gem "jekyll-paginate"
  gem "jekyll-redirect-from"
  gem "jekyll-sitemap"
  gem "jekyll-assets"
  gem 'jekyll-environment-variables'
end

group :development, :test do
  gem "html-proofer"
end

gem 'execjs'
gem "json"  # For gem building
gem 'sprockets', '3.7'
gem 'uglifier', '~> 4.0.0'
gem "mini_magick"
gem "image_optim_bin" # Optional
gem "image_optim_pack"
gem "image_optim"
gem "autoprefixer"
gem "kramdown-parser-gfm"

# Windows does not include zoneinfo files, so bundle the tzinfo-data gem
gem 'tzinfo-data', platforms: [:mingw, :mswin, :x64_mingw, :jruby]

# Make sure watch mode works A-OK on Windows too
gem "wdm", "~> 0.1.1" if Gem.win_platform?
