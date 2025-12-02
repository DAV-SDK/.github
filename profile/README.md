## DAV SDK

The data, analysis, and visualization (DAV) software development kit (SDK), or DAV SDK, is an integration effort for the collection of data I/O, analysis, and visualization software developed under the Department of Energy (DOE) Advanced Scientific Computing Research (ASCR). The software products target using Spack, an HPC-targeted source-based package manager, for deployment on HPC platforms and beyond. The primary product of this project is the davsdk Spack meta-package which builds a set of DAV SDK member packages together in a way that enables optimal features for target environments as well as interoperable features provided by other packages within the DAV SDK. The DAV SDK is an outcome of the work within the DOE OASIS project and is sustained and advanced by the DOE PESO project.


## Dependency table

M -> Mandatory  
O -> Optional


  |          | ZFP | DIY | HDF5 | PNetCDF | ADIOS2 | Viskores | Ascent | Catalyst | ParaView | VisIt |
  |----------|-----|-----|------|---------|--------|----------|--------|----------|----------|-------|
  | ZFP      |  -  |     |      |         |        |          |        |          |          |       |
  | DIY      |     |  -  |      |         |        |          |        |          |          |       |
  | HDF5     |  O  |     |  -   |         |        |          |        |          |          |       |
  | PNetCDF  |     |     |      |    -    |   O    |          |        |          |          |       |
  | ADIOS2   |  O  |     |  O   |    O    |   -    |          |        |          |          |       |
  | Viskores |  O  |  M  |      |         |        |    -     |        |          |          |       |
  | Ascent   |     |     |      |         |   O    |    M     |   -    |          |          |       |
  | Catalyst |     |     |      |         |   O    |          |        |    -     |          |       |
  | ParaView |     |     |  O   |    O    |   O    |    O     |        |    M     |    -     |       |
  | VisIt    |     |     |  O   |         |        |          |        |          |          |   -   |
