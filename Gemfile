source "https://rubygems.org"

# Hello! This is where you manage which Jekyll version is used to run.
# When you want to use a different version, change it below, save the
# file and run `bundle install`. Run Jekyll with `bundle exec`, like so:
#
#     bundle exec jekyll serve
#
# This will help ensure the proper Jekyll version is running.
# Happy Jekylling!

# Use GitHub Actions for deployment (not native GitHub Pages).
# Native Pages build would require github-pages gem + Jekyll 3.x,
# but this site uses Jekyll 4.x + remote_theme.
# gem "github-pages", group: :jekyll_plugins

gem "jekyll", "~> 4.3.0"

gem "wdm", "~> 0.1.0" if Gem.win_platform?

# If you have any plugins, put them here!
group :jekyll_plugins do
  gem "jekyll-remote-theme"
  # gem "jekyll-archives"
  gem "jekyll-feed"
  gem 'jekyll-sitemap'
  gem 'jekyll-paginate'
  gem 'jekyll-gist'
  gem 'jemoji'
  gem 'jekyll-redirect-from'
  gem "webrick", "~> 1.8"
end

# Site uses remote_theme, so no local theme gem needed.
# gem "minimal-mistakes-jekyll"
