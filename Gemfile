source "https://rubygems.org"

# Jekyll 및 기본 의존성
gem "jekyll", "~> 4.3.0"
gem "jekyll-sass-converter", "~> 2.0"
gem "kramdown-parser-gfm"

# 플러그인들
group :jekyll_plugins do
  gem "jekyll-archives"
  gem "jekyll-email-protect"
  gem "jekyll-feed"
  gem "jekyll-get-json"
  gem "jekyll-imagemagick"
  # gem "jekyll-jupyter-notebook"  # Jupyter 비활성화
  gem "jekyll-link-attributes"
  gem "jekyll-minifier"
  gem "jekyll-paginate-v2"
  gem "jekyll-regex-replace"
  gem "jekyll-scholar"
  gem "jekyll-sitemap"
  gem "jekyll-seo-tag"
  gem "jekyll-tabs"
  gem "jekyll-toc"
  gem "jekyll-twitter-plugin"
  gem "jemoji"
  gem "unicode_utils"
  gem "webrick"
end

# Windows 및 JRuby 플랫폼 지원
platforms :mingw, :x64_mingw, :mswin, :jruby do
  gem "tzinfo", ">= 1", "< 3"
  gem "tzinfo-data"
end

# Windows 성능 향상
gem "wdm", "~> 0.1.1", :platforms => [:mingw, :x64_mingw, :mswin]

# JRuby 지원
gem "http_parser.rb", "~> 0.6.0", :platforms => [:jruby]