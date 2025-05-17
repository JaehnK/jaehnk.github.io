source "https://rubygems.org"

# Jekyll 버전을 지정합니다 (GitHub Pages와 호환되는 버전)
gem "jekyll", "~> 3.9.3"

# GitHub Pages와 함께 사용할 플러그인들
group :jekyll_plugins do
  gem "github-pages", "~> 231"
  gem "jekyll-feed", "~> 0.15.1"
  gem "jekyll-seo-tag", "~> 2.8.0"
  gem "jekyll-sitemap", "~> 1.4.0"
end

# Windows와 JRuby는 zeitwerk 2.0에서 이슈가 있어 이를 해결하기 위한 gem
platforms :mingw, :x64_mingw, :mswin, :jruby do
  gem "tzinfo", ">= 1", "< 3"
  gem "tzinfo-data"
end

# 성능 향상을 위한 gem, 선택사항
gem "wdm", "~> 0.1.1", :platforms => [:mingw, :x64_mingw, :mswin]
gem "http_parser.rb", "~> 0.6.0", :platforms => [:jruby]
gem "webrick", "~> 1.8"
