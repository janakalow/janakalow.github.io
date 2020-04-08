source 'https://rubygems.org'

gem 'jekyll', '3.8.4'

group :jekyll_plugins do
  gem 'jekyll-feed', '0.11.0'
  gem 'jekyll-seo-tag', '2.5.0'
  gem 'jekyll-sitemap', '1.2.0'
  gem 'jekyll-paginate', '1.1.0'
end

# Windows and JRuby does not include zoneinfo files, so bundle the tzinfo-data gem
# and associated library.
install_if -> { RUBY_PLATFORM =~ %r!mingw|mswin|java! } do
  gem "tzinfo", "~> 1.2"
  gem "tzinfo-data"
end

git_source(:github) {|repo_name| "https://github.com/#{repo_name}" }
