source "https://rubygems.org"
# Hello! This is where you manage which Jekyll version is used to run.
# When you want to use a different version, change it below, save the
# file and run `bundle install`. Run Jekyll with `bundle exec`, like so:
#
#     bundle exec jekyll serve
#
# This will help ensure the proper Jekyll version is running.
# Happy Jekylling!
gem "jekyll", "~> 4.3.2"
# This is the default theme for new Jekyll sites. You may change this to anything you like.
# gem "minima", "~> 2.5"
# If you want to use GitHub Pages, remove the "gem "jekyll"" above and
# uncomment the line below. To upgrade, run `bundle update github-pages`.
# gem "github-pages", group: :jekyll_plugins
# If you have any plugins, put them here!
group :jekyll_plugins do
  gem "jekyll-feed", "~> 0.12"
  gem "jekyll-tidy"
  gem "jekyll-sitemap"
  gem "jekyll-redirect-from"
  gem "kramdown-math-katex"
end

# Required for running Jekyll on Ruby 3.x
gem "webrick", "~> 1.7"

# Windows and JRuby support
install_if -> { RUBY_PLATFORM =~ /mingw|mswin|java/ } do
  gem "tzinfo", "~> 1.2"
  gem "tzinfo-data"
  gem "wdm", "~> 0.1.1"
end

# Standard library gems (for Ruby 3.0+ compatibility)
gem "base64"
gem "bigdecimal"
gem "csv"
gem "drb"
gem "net-http"
gem "matrix"
gem "mutex_m"
gem "prime"
gem "securerandom"
gem "strscan"