source "https://rubygems.org"

# Jekyll core
gem "jekyll", "~> 4.3.0"

# Essential Jekyll plugins
group :jekyll_plugins do
  gem "jekyll-archives"
  gem "jekyll-email-protect"
  gem "jekyll-feed"
  gem "jekyll-get-json"
  gem "jekyll-imagemagick"
  gem "jekyll-jupyter-notebook"
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

# Dependencies for _plugins/ custom plugins
group :other_plugins do
  gem "css_parser"           # download-3rd-party.rb
  gem "feedjira"            # external-posts.rb  
  gem "httparty"            # external-posts.rb, download-3rd-party.rb
  gem "nokogiri"            # google-scholar-citations.rb, external-posts.rb
  gem "classifier-reborn"
  gem "observer"
  gem "ostruct"
  gem "activesupport"       # google-scholar-citations.rb, inspirehep-citations.rb
  gem "i18n"                # remove-accents.rb
end

# Additional al-folio dependencies
gem "jekyll-terser", git: "https://github.com/RobertoJBeltran/jekyll-terser.git"
gem "jekyll-archives-v2"

# Windows and JRuby compatibility
platforms :mingw, :x64_mingw, :mswin, :jruby do
  gem "tzinfo", ">= 1", "< 3"
  gem "tzinfo-data"
end

gem "wdm", "~> 0.1.1", :platforms => [:mingw, :x64_mingw, :mswin]
gem "http_parser.rb", "~> 0.6.0", :platforms => [:jruby]

if RUBY_PLATFORM =~ /linux-musl/
  gem "jekyll-sass-converter", "~> 2.0"
end