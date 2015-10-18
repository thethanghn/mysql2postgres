ruby '2.1.6'
source 'https://rubygems.org'

gem 'rake'
gem 'mysql-pr', '~> 2.9'
gem 'postgres-pr', '~> 0.6'

platforms :jruby do
  gem 'activerecord'
  gem 'jdbc-postgres'
  gem 'activerecord-jdbc-adapter'
  gem 'activerecord-jdbcpostgresql-adapter'
end

platforms :mri do
  gem 'pg', '~> 0.17'
end

gem 'test-unit'

group :test do
  gem 'jeweler', '~> 2.0'
end
