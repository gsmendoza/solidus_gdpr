# frozen_string_literal: true

puts
puts "----------"
puts "SolidusGdpr - Rakefile"
puts "SolidusDevSupport::RakeTasks.install - START"
puts

require 'solidus_dev_support/rake_tasks'
SolidusDevSupport::RakeTasks.install

puts
puts "----------"
puts "SolidusGdpr - Rakefile"
puts "task default: 'extension:specs' - START"
puts

task default: %w[extension:test_app extension:specs]

puts
puts "----------"
puts "SolidusGdpr - Rakefile"
puts "task default: %w[extension:test_app extension:specs] - END"
puts

