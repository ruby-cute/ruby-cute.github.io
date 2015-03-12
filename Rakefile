
source_readme = "https://raw.githubusercontent.com/ruby-cute/ruby-cute/master/README.md"

task :web do

`wget #{source_readme}`
`pandoc README.md -o index.html --template template.html --css template.css --self-contained`
end

task :default => :web
