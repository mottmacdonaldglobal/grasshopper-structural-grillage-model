# Grasshopper_STRUCTURAL_Grillage_Model

*this script is mainly used for structural engineers to build grillage model for structural analysis

The model has been separated to two major parts, which are:

- Longitudinal Section:
  > Users will have to enter the value of overall longitudinal length, edge distance and interval distance

- Tranverse Section:
  > Users will have to enter the value overall tranverse length and interval distance
  
After filling uo the inputs, bake(to create physcially usable geometry) the components in grasshopper by assigning them to different layers.

Lastly, select the layer in Rhino and export them to any CAD format shown below:

Spacegass         : DXF
MIDAS Civil       : DXF 
Strand 7          : IGES, STEP, ACIS-SAT
Autodesk Robot    : DWG, DGN
