source "https://rubygems.org"

gem "jekyll", "~> 3.7.0"
gem 'github-pages', group: :jekyll_plugins
gem "jekyll-theme-clean-blog"

group :jekyll_plugins do
  gem "jekyll-feed", "~> 0.6"
  gem "jekyll-paginate", "~> 1.1.0"
end

require 'rbconfig'
  if RbConfig::CONFIG['target_os'] =~ /darwin(1[0-3])/i
    gem 'rb-fsevent', '<= 0.9.4'
  end
