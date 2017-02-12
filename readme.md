# Voronoi District #

Solve [Gerrymandering](https://en.wikipedia.org/wiki/Gerrymandering) once and for all by districting the United States using [Voronoi Tesselations](https://en.wikipedia.org/wiki/Voronoi_diagram).

### Methodology ###

1. Lay random points over all states with more than one district according to population density.
2. Create Voronoi cells from the random points. These cells become Congressional districts.
3. Estimate the party balance in the House of Representatives using past voting data.
4. Calculate different tessllations and party membership for a large number of different random number seeds to find
probabilities of different levels of party membership.
5. Compare to current level of party membership.

### Dependencies ###

1. Jupyter
2. Numpy
3. Matplotlib
4. Basemap
5. Shapely
