require "bundler/gem_tasks"
require "rspec/core/rake_task"

RSpec::Core::RakeTask.new(:spec) do |t|
  t.rspec_opts = "--format=RspecProgressExtended::Formatter"
  t.verbose = false
end

task default: :spec
