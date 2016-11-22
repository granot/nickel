require 'bundler'
Bundler.setup
Bundler::GemHelper.install_tasks

require 'rake'
require 'rspec/core/rake_task'
require 'yard'
require 'pry-rails'

task default: :spec

RSpec::Core::RakeTask.new(:spec)

YARD::Rake::YardocTask.new(:yard)
