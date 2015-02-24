require 'bundler/gem_tasks'
require 'rake'
require 'rake/testtask'

task :default => [:test, :build]

Rake::TestTask.new(:test) do |t|
  t.libs << 'lib'
  t.pattern = 'test/**/*_test.rb'
  t.verbose = true
end

