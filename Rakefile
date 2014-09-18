#!/usr/bin/env rake

require 'bundler/setup'
require 'rspec/core/rake_task'

desc 'Run ChefSpec unit tests'
RSpec::Core::RakeTask.new(:unit) do |t|
  t.rspec_opts = '--color --format progress'
end

desc 'Run all tests on Travis'
task travis: %w(unit)

# Default
task default: %w(unit)
