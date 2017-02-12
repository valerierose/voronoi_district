# Voronoi District #

Solve [Gerrymandering](https://en.wikipedia.org/wiki/Gerrymandering) once and for all by districting the United States using [Voronoi Tesselations](https://en.wikipedia.org/wiki/Voronoi_diagram).

### Methodology ###

# Lay random points over all states with more than one district according to population density.
# Create Voronoi cells from the random points. These cells become Congressional districts.
# Estimate the party balance in the House of Representatives using past voting data.
# Calculate different tessllations and party membership for a large number of different random number seeds to find
probabilities of different levels of party membership.
# Compare to current level of party membership.

### Dependencies ###

# Jupyter
# Numpy
# Matplotlib
# Basemap
# Shapely
