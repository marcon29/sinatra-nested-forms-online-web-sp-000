ENV["SINATRA_ENV"] ||= "development"

require_relative './environment'

# Type `rake -T` on your command line to see the available rake tasks.

def reload!
  load_all './app/models'
end

task :console do
  Pry.start
end