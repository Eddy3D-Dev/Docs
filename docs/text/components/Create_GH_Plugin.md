## ![](../../images/icons/Create_GH_Plugin.png) Create GH Plugin - [[source code]](C:\Users\pkastner\Documents\GitHub\Eddy3D\UMCF/Create%20GH%20Plugin.py)

![](../../images/components/Create_GH_Plugin.png)

Creates a Grasshopper plugin in the input directory.

#### Inputs
* ##### W []
Set to true to write the GH plugin.
* ##### P []
The directory of the MetaFOAM plugin.
* ##### C []
OpenFOAM case.
* ##### I []
Names of initial condition files to ignore.
* ##### N []
If true, boundary conditions with no values are included in the Initial Condition inputs
* ##### Z []
If true, inputs with value equal to 0 will be included in the initial condition inputs
* ##### I []
Boundary conditions in this list will be ignored
* ##### B []
Boundary condition that will be generated GH components for
* ##### D []
Descriptions of initial conditions

#### Outputs
* ##### L
Logs.


[Check Hydra Example Files for Create GH Plugin](https://hydrashare.github.io/hydra/index.html?keywords=Create GH Plugin)