require 'rake/testtask'
require 'rspec/core/rake_task'

Rake::TestTask.new do |t|
  t.pattern = "test/**/test_helper.rb"
end

RSpec::Core::RakeTask.new(:spec)

task default: :test