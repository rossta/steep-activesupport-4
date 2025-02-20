source 'https://rubygems.org'

# Specify your gem's dependencies in steep.gemspec
gemspec

gem "rake"
gem "minitest", "~> 5.25"
gem "minitest-hooks"
gem 'minitest-slow_test'

# Stdgem dependencies omitted from gemspec for compatibility with legacy
# environments
gem "securerandom", ">= 0.1"
gem "json", ">= 2.1.0"
gem "logger", ">= 1.3.0"
gem "fileutils", ">= 1.1.0"
gem "strscan", ">= 1.0.0"
gem "csv", ">= 3.0.9"

group :development, optional: true do
  gem "stackprof"
  gem "debug", require: false, platform: :mri
  gem "vernier", "~> 1.4", require: false, platform: :mri
  gem "memory_profiler"
  gem "majo"
end

# gem "rbs", path: "../rbs"
# gem "rbs", git: "https://github.com/ruby/rbs.git", branch: "master"
