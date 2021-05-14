# blank_foamcase
Blank Busemann Biplane OpenFOAM case in a circular domain

# download

# meshing
$ gmsh busemann.geo -3 -format msh2

# convert mesh
$ gmshToFoam busemann.msh

# running
$ cd <location>
then $ rhoCentralFoam
