#!/usr/bin/env rake
# frozen_string_literal: true

require 'bundler/gem_tasks'

$LOAD_PATH.unshift(File.join(File.dirname(__FILE__), 'lib'))

require 'rspec/core'
require 'rspec/core/rake_task'

task default: :spec

desc 'Run all specs in spec directory'
RSpec::Core::RakeTask.new(:spec)

desc 'Run CI tasks'
task ci: [:spec]
