# frozen_string_literal: true

source "https://rubygems.org"

ruby ">= 3.1"

# 核心
gem "jekyll", "~> 4.3"

# 主题 + 主题依赖的插件（minima 内部模板用到了 seo/feed）
gem "minima", "~> 2.5"
gem "jekyll-feed"
gem "jekyll-seo-tag"
gem "jekyll-sitemap"

# Ruby 4.0 起被移出标准库、必须显式声明的 gem
gem "csv"
gem "webrick", "~> 1.8"
gem "rexml"
gem "bigdecimal"

# 锁死 sass-converter，压掉 minima 2.5 的 Dart Sass 弃用警告（lighten/@import）
gem "jekyll-sass-converter", "~> 2.2"

