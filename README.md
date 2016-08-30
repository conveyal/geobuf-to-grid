# geobuf-to-grid

 Convert a GeoBuf file to a binary regular grid for use in a static site
 Usage: geobuf-grid.js [--png] geobuf.pbf output_prefix.
 Creates one .grid file for each numeric attribute in the geobuf. If --png is specified, creates log-scaled pngs as well (useful for debugging).