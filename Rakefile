require 'bundler/gem_tasks'
require 'rake/extensiontask'

task default: :spec
Rake::ExtensionTask.new 'miga' do |ext|
  ext.lib_dir = 'lib/miga'
end
