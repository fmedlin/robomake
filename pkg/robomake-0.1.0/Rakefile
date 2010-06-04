require 'rubygems'  
require 'rake'  
require 'echoe'  

Echoe.new('robomake', '0.1.0') do |p|  
  p.description     = "Automatically build an Android NDK application"  
  p.url             = "http://github.com/fmedlin/robomake"  
  p.author          = "Fred Medlin"
  p.email           = "fred@medl.in"
  p.ignore_pattern  = ["tmp/*", "script/*"]  
  p.development_dependencies = []  
end  
   
Dir["#{File.dirname(__FILE__)}/tasks/*.rake"].sort.each { |ext| load ext }