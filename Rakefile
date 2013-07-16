require 'rake'
require 'rake/testtask'
require 'bundler/gem_tasks'
Bundler::GemHelper.install_tasks

task default: :test

Rake::TestTask.new :test do |t|
  t.libs << 'lib' << 'test'
  t.pattern = 'test/*_test.rb'
  t.verbose = true
end
