# Load DSL and set up stages
require 'capistrano/setup'

# Include default deployment tasks
require 'capistrano/deploy'

#   https://github.com/capistrano/rbenv
require 'capistrano/rbenv' if ENV['rbenv']

# Server
require 'capistrano/puma'

#   https://github.com/capistrano/bundler
#   https://github.com/capistrano/rails
require 'capistrano/bundler'
require 'capistrano/rails/assets'
require 'capistrano/rails/migrations'

require 'capistrano/uberspace'

# Load custom tasks from `lib/capistrano/tasks` if you have any defined
Dir.glob('lib/capistrano/tasks/*.rake').each { |r| import r }
