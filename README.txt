#Script to use OSMNX to find shortest path as route distance

Update:
2021-07-27  Created by Tawan,T.

Why:
- Sometimes we need to calculate distance between two locations.
- Normally we could use googlemap api to compute a route distance but this comes with cost.
- OSMNX could be an alternative. It uses openstreetmap nodes and networkx to compute this route distance for us.

How:
- Input  
1.Location of interest, e.g. Bangkok
2.lat, lng of origin and destination in ipython notebook (both needs to be in the selected location)
3.Run the script to see the result to see how it works


Note:
At the creation of this repo, I could not find a way to install OSMNX on windows.
The option I used is to install it on Linux.

installation:
1.Use yml file to install environment

or

2.Follow the link below to install all the required package
installation

[1] [https://osmnx.readthedocs.io/en/stable/](https://osmnx.readthedocs.io/en/stable/)  (install on linux Ubuntu, windows not success)

[2] [https://anaconda.org/conda-forge/descartes](https://anaconda.org/conda-forge/descartes)

[3] [https://anaconda.org/ufechner/graphics](https://anaconda.org/ufechner/graphics)