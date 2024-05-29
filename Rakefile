
manifest =
{
    :version => "R1",
    :project_name => "UtilitySCAD"
}
directory_name = manifest[:project_name] + "-" + manifest[:version]

task :create do
    FileUtils.mkdir(directory_name)
    FileUtils.cp("utility.scad",directory_name + "/utility.scad")
    FileUtils.cp("examples.scad",directory_name + "/examples.scad")
    FileUtils.cp("hooks.scad",directory_name + "/hooks.scad")
end

task :remove do
    FileUtils.rm_r(directory_name)
end
