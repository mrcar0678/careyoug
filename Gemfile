source 'https://rubygems.org'
ruby '3.3.1'

# --- 核心套件 ---
gem 'rails', '~> 7.0.4'
gem 'puma', '~> 3.11'
gem 'sass-rails', '~> 5.0.2'
gem 'uglifier', '>= 1.3.0'
gem 'duktape' # JS runtime，免安裝 Node.js
gem 'turbolinks', '~> 5'
gem 'jbuilder', '~> 2.5'

# --- 資料庫（開發用 SQLite、部署用 PostgreSQL）---
gem 'sqlite3', group: [:development, :test]
gem 'pg', group: [:production]

# --- LINE Bot ---
gem 'line-bot-api', '~> 1.9'

# --- 前端資源 ---
gem 'coffee-rails', '~> 4.2'

# --- 安全與 HTML 處理 ---
gem 'rails-html-sanitizer', '~> 1.0', '>= 1.0.4'
gem 'loofah', '~> 2.2', '>= 2.2.3'
gem 'crass', '~> 1.0', '>= 1.0.4'

# --- Rack 與測試 ---
gem 'rack', '~> 2.0', '>= 2.0.7'
gem 'rack-test', '~> 1.1'

# --- 執行環境優化 ---
gem 'bootsnap', '>= 1.1.0', require: false
gem 'dotenv-rails', '~> 2.7'

# --- 開發工具 ---
group :development do
  gem 'web-console', '>= 3.3.0'
  gem 'byebug', platforms: [:mri, :mingw, :x64_mingw]
end

# --- 測試工具 ---
group :test do
  gem 'capybara', '>= 2.15'
  gem 'selenium-webdriver'
  gem 'chromedriver-helper'
end

# --- 特殊平台支援（Windows）---
gem 'tzinfo-data', platforms: [:mingw, :mswin, :x64_mingw, :jruby]
