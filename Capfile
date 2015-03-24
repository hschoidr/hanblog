# Load DSL and set up stages
require 'capistrano/setup'

# Include default deployment tasks
require 'capistrano/deploy'

# Include tasks from other gems included in your Gemfile
require 'capistrano/bundler'
require 'capistrano/rbenv'
require 'capistrano/rbenv_install'
require 'capistrano/rails/assets'
require 'capistrano/faster_assets'
require 'capistrano/safe_deploy_to'
require 'capistrano/rails_tail_log'
require 'capistrano/rails/console'
require 'capistrano/rails/migrations'
require 'capistrano/rails/collection'
require 'capistrano/rails/migrations'
require 'capistrano/secrets_yml'
require 'capistrano/unicorn_nginx'


# Load custom tasks from `lib/capistrano/tasks` if you have any defined
Dir.glob('lib/capistrano/tasks/*.rake').each { |r| import r }
