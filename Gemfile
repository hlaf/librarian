source "https://rubygems.org"

# Specify your gem's dependencies in librarian.gemspec
gemspec

group :release, optional: true do
  gem 'github_changelog_generator', '>= 1.16.4',  :require => false if RUBY_VERSION >= '2.5.0'
end
