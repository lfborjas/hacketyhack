desc "Update pot/po files."
task :makemessages do
  require 'gettext/tools'
  GetText.update_pofiles("HH", Dir.glob("{lib,bin}/**/*.{rb,rhtml}"), "HacketyHack")
end

desc "Create mo-files"
task :compilemessages do
  require 'gettext/tools'
  GetText.create_mofiles
end
