source 'https://rubygems.org'

RAILS_VERSION = '~> 3.2.12'
DM_VERSION    = '~> 1.2.0'

gem 'activesupport',  RAILS_VERSION, :require => 'active_support'
gem 'actionpack',     RAILS_VERSION, :require => 'action_pack'
gem 'actionmailer',   RAILS_VERSION, :require => 'action_mailer'
gem 'activeresource', RAILS_VERSION, :require => 'active_resource'
gem 'railties',       RAILS_VERSION, :require => 'rails'
gem 'tzinfo',         '~> 0.3.32'
gem 'dm-rails',               '~> 1.2.1'

gem 'execjs'
gem 'therubyracer'
gem 'thin'

gem 'dm-mysql-adapter',     DM_VERSION
gem 'dm-migrations',   DM_VERSION
gem 'dm-types',        DM_VERSION
gem 'dm-validations',  DM_VERSION
gem 'dm-constraints',  DM_VERSION
gem 'dm-transactions', DM_VERSION
gem 'dm-aggregates',   DM_VERSION
gem 'dm-timestamps',   DM_VERSION
gem 'dm-observer',     DM_VERSION

# Gems used only for assets and not required
# in production environments by default.
group :assets do
  gem 'uglifier',     '~> 1.2.4'
  gem 'haml-rails'
  gem 'rspec-rails', '~> 2.0'
end

gem 'jquery-rails', '~> 2.0.1'

group :development do
  gem 'debugger'
  gem 'rspec-rails', '~> 2.0'
  gem 'factory_girl_rails'
end

group :test do
  gem 'turn', '~> 0.9.4', :require => false
  gem 'rspec-rails', '~> 2.0'
  gem 'factory_girl_rails'
end

# for devise
gem 'dm-core',           '~> 1.2.0'
gem 'dm-serializer',     '~> 1.2.0'
gem 'dm-timestamps',     '~> 1.2.0'
gem 'dm-validations',    '~> 1.2.0' # Do not include if using data_mapper_active_model
gem 'dm-devise',         '~> 2.1.0'

# for abilities
gem "cancan"
gem 'pry-rails'
