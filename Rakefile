require 'rake/testtask'

Rake::TestTask.new do |t|
  t.libs << 'spec'
  t.pattern = "spec/**/test_*.rb"
end

desc "Run tests"
task :default => :test