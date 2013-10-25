require 'rake'
require 'rake/testtask'

desc 'Run tests'
Rake::TestTask.new do |t|
  t.libs << 'test'
  t.pattern = 'test/**/*_test.rb'
end

desc 'Run example'
task :example do
  puts '5'
end

task default: :test
