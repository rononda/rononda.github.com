task :default => [:build, :cp]

desc "Compiles the haml and sass files with staticmatic"
task :build do
  system "staticmatic build ."
end

desc "Copies built html and css files to deploy"
task :cp do
  system "cp site/*.html ."
  system "cp site/stylesheets/*.css stylesheets"
end
