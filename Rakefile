require "rake/packagetask"

def package_file_name(package)
  "head_first_ruby_#{package}"
end

Rake::PackageTask.new(package_file_name("source"), :noversion) do |p|
  p.need_zip = true
  p.package_files.include("source/**/*")
end