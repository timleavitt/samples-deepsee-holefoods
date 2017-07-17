# samples-holefoods
InterSystems DeepSee sample solution which illustrates the use of DeepSee Architect, Analyser, DeepSee dashboards, widgets and MDX queries.
# Installation
Import release file in any Namespace
To create data for this DeepSee model, the easiest thing to do is to
use the BuildData method:
From the command line:
```
Do ##class(HoleFoods.Utils).BuildData(1000000,1,1)
```
The first argument is the number of records to create, 
the second argument indicates that index building should be done in parallel,
the third is a verbose flag; if true, then progress is displayed as the data is built.
