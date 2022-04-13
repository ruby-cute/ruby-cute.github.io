
source_readme = "https://raw.githubusercontent.com/ruby-cute/ruby-cute/master/README.md"

task :web do

system("rm -f README.md") or raise
system("wget #{source_readme}") or raise
system("pandoc README.md -o index.html --template template.html --css template.css --self-contained --metadata title='Ruby-Cute'")
end

task :default => :web
