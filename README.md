# Heroku-friendly-config-database.yml

Using database gem 'pg' instead of default database gem 'sqlite3' for deploying rails app to heroku.
config/database.yml also should be changed.
Run 'rake db:create' and 'rake db:migrate' commands after altering database.yml file.
