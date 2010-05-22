require 'rubygems'
require 'rake'

begin
  require 'jeweler'
  Jeweler::Tasks.new do |gem|
    gem.name = "compass-slickmap"
    gem.summary = %Q{An implementation of SlickmapCSS sitemap in SCSS/Sass3}
    gem.email = "tdreyno@gmail.com"
    gem.homepage = "http://github.com/tdreyno/compass-slickmap"
    gem.authors = ["Thomas Reynolds"]
    # gem.rubyforge_project = "compassslickmap"
    # gem is a Gem::Specification... see http://www.rubygems.org/read/chapter/20 for additional settings
    gem.add_dependency("haml", ">= 3.0")
    gem.add_dependency("compass", ">= 0.10")
  end
  
  Jeweler::GemcutterTasks.new
rescue LoadError
  puts "Jeweler (or a dependency) not available. Install it with: sudo gem install jeweler"
end