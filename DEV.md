// build mask 
s build="HoleFoods*.CLS,*.DFI" 
// build export 
do $system.OBJ.Export(build,"docserver_release.xml")
