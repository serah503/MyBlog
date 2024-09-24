# Ruby 버전 지정
ruby '~> 3.1'

# Gem 의존성
source "https://rubygems.org"

gemspec

# html-proofer는 4.0 버전 사용
gem 'html-proofer', '~> 4.0', group: :test

platforms :mingw, :x64_mingw, :mswin, :jruby do
  gem "tzinfo", ">= 1", "< 3"
  gem "tzinfo-data"
end

gem "wdm", "~> 0.1.1", :platforms => [:mingw, :x64_mingw, :mswin]

