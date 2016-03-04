require 'bundler'

desc "Generate the blog and test the HTML-ness"
task "test" do
  Bundler.require
  system "jekyll build; htmlproof --disable-external ./_site"
end

task default: [:test]