# Cologne Project Ideas List for the #30DayMapChallenge 2025

Here is a list of 30 project ideas, specifically tailored to Cologne, based on the official categories of the 30-Day Map Challenge 2025. Each idea uses Open Data from sources like the Cologne Open Data Portal [](https://offenedaten-koeln.de), Open.NRW, and OpenStreetMap (OSM). The structure includes **Concept**, **Explanation**, **Roadmap**, **Purpose**, and **Tech**. The ideas are designed to be implementable with GIS tools and shareable daily. Download links to relevant datasets are included.

## 1. Points: School Locations in Cologne
- **Concept**: A point map of all schools in Cologne, color-coded by school type.
- **Explanation**: Shows the distribution of primary schools, high schools, and vocational schools to highlight gaps in educational infrastructure.
- **Roadmap**: Day 1: Download and import data; Day 2: Plot points and style; Day 3: Finalize interactive map and post.
- **Purpose**: Sparks discussions about access to education in urban districts.
- **Tech**: QGIS for point layers;  
  **Data**: [Schools in Cologne (GeoJSON/Shapefile)](https://offenedaten-koeln.de/dataset/schulen-köln)

## 2. Lines: Cologne Bike Path Network
- **Concept**: Line map of the cycling network with thickness based on popularity.
- **Explanation**: Visualizes safe bike paths and connections between districts, based on OSM data.
- **Roadmap**: Extract lines, adjust styles, add legend, and export.
- **Purpose**: Supports sustainable mobility and route planning for cyclists.
- **Tech**: OSM extract in QGIS;  
  **Data**: [OSM NRW Shapefiles (clip to Cologne)](https://download.geofabrik.de/europe/germany/nordrhein-westfalen.html)

## 3. Polygons: Cologne City Districts
- **Concept**: Polygon map of the 9 city districts with colors by population density.
- **Explanation**: Highlights urban density and boundaries to show growth patterns.
- **Roadmap**: Load polygons, join attributes, create choropleth, and share.
- **Purpose**: Aids in urban planning and resource allocation analysis.
- **Tech**: ArcGIS Online or QGIS;  
  **Data**: [Cologne City Districts (Shapefile)](https://offenedaten-koeln.de/dataset/stadtbezirke-köln)

## 4. Data challenge: My Data – Personal Commuter Data
- **Concept**: Polygon overlays with personal GPS tracks of commuting routes in Cologne.
- **Explanation**: Combines personal lines with public polygons (e.g., districts) to map daily routes.
- **Roadmap**: Collect own data, join with public, visualize, and anonymize.
- **Purpose**: Shows individual impacts of transport networks on life in Cologne.
- **Tech**: GPX import in QGIS;  
  **Data**: Personal + [City Districts (Supplement)](https://offenedaten-koeln.de/dataset/stadtbezirke-köln)

## 5. Earth: Terrain Model of the Rhineland
- **Concept**: 3D Earth visualization of Cologne’s terrain along the Rhine.
- **Explanation**: Uses DEM data to show hills and valleys around Cologne, focusing on the Rhine.
- **Roadmap**: Load raster, generate hillshade, 3D export, and post.
- **Purpose**: Explains geological foundations for flood risks.
- **Tech**: QGIS 3D View;  
  **Data**: [Digital Terrain Model NRW (GeoTIFF)](https://open.nrw/dataset/0c6796e5-9eca-4ae6-8b32-1fcc5ae5c481)

## 6. Dimensions: 3D Building Model of Cologne
- **Concept**: Multi-dimensional map with building heights in LoD2.
- **Explanation**: Shows height profiles of icons like the Cathedral in 3D overlay.
- **Roadmap**: Import models, scale dimensions, animate, and render.
- **Purpose**: Demonstrates vertical urban density.
- **Tech**: Blender with GIS plugin;  
  **Data**: [3D Building Model NW LoD2](https://open.nrw/dataset/5d9a8abc-dfd0-4dda-b8fa-165cce4d8065)

## 7. Accessibility: Barrier-Free Paths in Cologne
- **Concept**: Heatmap of wheelchair-accessible paths.
- **Explanation**: Evaluates lines by accessibility (e.g., ramps from OSM).
- **Roadmap**: Filter attributes, create buffers, generate heatmap.
- **Purpose**: Promotes inclusion in city planning.
- **Tech**: Network Analyst in QGIS;  
  **Data**: [OSM NRW (Accessibility Tags)](https://download.geofabrik.de/europe/germany/nordrhein-westfalen.html)

## 8. Urban: Green Spaces in Urban Districts
- **Concept**: Urban polygon map of parks and green areas.
- **Explanation**: Measures green space share per district for urban ecology.
- **Roadmap**: Classify polygons, calculate areas, create choropleth.
- **Purpose**: Highlights need for more green in dense areas.
- **Tech**: QGIS Field Calculator;  
  **Data**: [ALKIS Base Maps (Green Areas)](https://open.nrw/dataset/407373a2-422c-469c-a7e9-06a62b4d7d9a)

## 9. Analog: Hand-Drawn Rhine Promenade
- **Concept**: Analog sketched line map of the promenade, scanned and digitized.
- **Explanation**: Combines hand-drawn lines with real points (e.g., bridges).
- **Roadmap**: Sketch, scan, overlay in GIS.
- **Purpose**: Emphasizes creative, non-digital cartography.
- **Tech**: Inkscape for digitization;  
  **Data**: [OSM Rhine Lines (Base)](https://download.geofabrik.de/europe/germany/nordrhein-westfalen.html)

## 10. Air: Air Quality Monitoring Stations
- **Concept**: Point map of air monitoring stations with values.
- **Explanation**: Visualizes PM2.5 levels at key locations in Cologne.
- **Roadmap**: Plot points, scale symbols, add time series.
- **Purpose**: Raises awareness of environmental health.
- **Tech**: Leaflet.js;  
  **Data**: [Air Quality NRW (Points)](https://offenedaten-koeln.de/search?groups=umwelt) *(search for "Luftqualität")*

## 11. Minimal map: Simplified Cologne Outline
- **Concept**: Minimalist polygon map with just the Rhine and Cathedral symbol.
- **Explanation**: Reduces to essentials for clear overview.
- **Roadmap**: Simplify (Simplify Tool), export as SVG.
- **Purpose**: Shows elegance in minimalism.
- **Tech**: QGIS Simplify;  
  **Data**: [City Districts (simplified)](https://offenedaten-koeln.de/dataset/stadtbezirke-köln)

## 12. Map from 2125: Futuristic Cologne Scenarios
- **Concept**: Speculative map with hypothetical polygons (e.g., floating districts).
- **Explanation**: Projects urban growth based on current trends.
- **Roadmap**: Extrapolate current data, draw new layers.
- **Purpose**: Discusses sustainable future visions.
- **Tech**: Adobe Illustrator;  
  **Data**: [City Districts (Base)](https://offenedaten-koeln.de/dataset/stadtbezirke-köln)

## 13. 10 minute map: Quick Bus Lines
- **Concept**: 10-minute line map of main bus routes.
- **Explanation**: Focuses on central connections for commuters.
- **Roadmap**: Quickly load, style, export.
- **Purpose**: Demonstrates efficiency in cartography.
- **Tech**: QGIS QuickMapServices;  
  **Data**: [Cologne Streets (Lines)](https://open.nrw/dataset/strassen-koln-k)

## 14. Data challenge: OpenStreetMap – Extract Parks
- **Concept**: OSM polygons of all parks in Cologne.
- **Explanation**: Filters `leisure=park` for green analysis.
- **Roadmap**: Query in Overpass, import, style.
- **Purpose**: Shows OSM potential for local data.
- **Tech**: Overpass Turbo;  
  **Data**: [OSM NRW Full](https://download.geofabrik.de/europe/germany/nordrhein-westfalen.html)

## 15. Fire: Fire Risk Zones
- **Concept**: Heatmap of fire stations and risk areas.
- **Explanation**: Points with buffers for response times.
- **Roadmap**: Load points, calculate buffers, generate heatmap.
- **Purpose**: Improves emergency planning.
- **Tech**: QGIS Heatmap;  
  **Data**: [Fire Stations (via OSM)](https://download.geofabrik.de/europe/germany/nordrhein-westfalen.html)

## 16. Cell: Hexagonal Population Cells
- **Concept**: Hexagonal grid map with population density.
- **Explanation**: Divides Cologne into cells for granular analysis.
- **Roadmap**: Generate hex grid, join data, color.
- **Purpose**: Enables scalable demographic studies.
- **Tech**: QGIS Hexagonal Grid;  
  **Data**: [Population per District](https://offenedaten-koeln.de/search?groups=statistik)

## 17. A new tool: Kepler.gl for Cologne Traffic
- **Concept**: New tool exploration: Traffic flows in Kepler.gl.
- **Explanation**: Interactive lines of traffic data.
- **Roadmap**: Learn tool, load data, build dashboard.
- **Purpose**: Introduces modern visualization tools.
- **Tech**: Kepler.gl;  
  **Data**: [Streets (Lines)](https://open.nrw/dataset/strassen-koln-k)

## 18. Out of this world: Astronomical Points over Cologne
- **Concept**: Star points over Cologne skyline (overlay).
- **Explanation**: Combines Earth map with sky map.
- **Roadmap**: Import star data, project.
- **Purpose**: Creatively connects city and cosmos.
- **Tech**: Stellarium + QGIS;  
  **Data**: [City Outline](https://offenedaten-koeln.de/dataset/stadtbezirke-köln)

## 19. Projections: Cologne in Different Projections
- **Concept**: Comparison of Mercator vs. UTM for the Rhine.
- **Explanation**: Shows distortions in areas.
- **Roadmap**: Re-project, side-by-side.
- **Purpose**: Teaches projection knowledge.
- **Tech**: QGIS Reproject;  
  **Data**: [Rhine Lines (OSM)](https://download.geofabrik.de/europe/germany/nordrhein-westfalen.html)

## 20. Water: Rhine and Water Bodies Polygons
- **Concept**: Water area map with flood risks.
- **Explanation**: Polygons of rivers and canals.
- **Roadmap**: Extract, style as blue gradient.
- **Purpose**: Raises awareness of water resources.
- **Tech**: QGIS Raster to Vector;  
  **Data**: [Water Bodies NRW](https://open.nrw/search?groups=umwelt)

## 21. Icons: Symbol Map of Landmarks
- **Concept**: Points with custom icons (Cathedral, Chocolate Museum).
- **Explanation**: Icons for tourist attractions.
- **Roadmap**: Design symbols, assign.
- **Purpose**: Makes maps more engaging.
- **Tech**: QGIS Symbology;  
  **Data**: [POI Cologne (OSM)](https://download.geofabrik.de/europe/germany/nordrhein-westfalen.html)

## 22. Data challenge: Natural Earth – Cologne Context
- **Concept**: Global context with Natural Earth, zoom to Cologne.
- **Explanation**: Overlays world boundaries with local data.
- **Roadmap**: Download, clip, integrate.
- **Purpose**: Shows scale levels.
- **Tech**: GDAL Clip;  
  **Data**: [Natural Earth (free)](https://www.naturalearthdata.com/) + [Cologne Base](https://offenedaten-koeln.de/dataset/stadtbezirke-köln)

## 23. Process: Data Processing for Green Spaces
- **Concept**: Workflow map: Raw data to final green map.
- **Explanation**: Documents cleaning steps.
- **Roadmap**: Sketch process, output as map.
- **Purpose**: Transparency in GIS processes.
- **Tech**: QGIS Processing Toolbox;  
  **Data**: [ALKIS Green](https://open.nrw/dataset/407373a2-422c-469c-a7e9-06a62b4d7d9a)

## 24. Places and their names: Cologne Neighborhoods
- **Concept**: Label map with historical names.
- **Explanation**: Polygons with etymology labels.
- **Roadmap**: Join names, place labels.
- **Purpose**: Preserves cultural heritage.
- **Tech**: QGIS Labels;  
  **Data**: [Neighborhoods (Shapefile)](https://offenedaten-koeln.de/dataset/stadtbezirke-köln)

## 25. Hexagons: Mobility Hexagons
- **Concept**: Hex map of public transit density.
- **Explanation**: Aggregates stops per hexagon.
- **Roadmap**: Generate hex, count, color.
- **Purpose**: Identifies mobility gaps.
- **Tech**: QGIS Vector Grid;  
  **Data**: [Public Transit Points (OSM)](https://download.geofabrik.de/europe/germany/nordrhein-westfalen.html)

## 26. Transport: S-Bahn Network
- **Concept**: Line map of all S-Bahn routes.
- **Explanation**: With stations and frequencies.
- **Roadmap**: Load lines, joins, style.
- **Purpose**: Optimizes commuter planning.
- **Tech**: QGIS Network;  
  **Data**: [Transport OSM](https://download.geofabrik.de/europe/germany/nordrhein-westfalen.html)

## 27. Boundaries: Administrative Boundaries
- **Concept**: Multi-level boundaries (district, neighborhood).
- **Explanation**: Nested polygons for hierarchy.
- **Roadmap**: Stack layers, transparency.
- **Purpose**: Clarifies administrative structures.
- **Tech**: QGIS Layer Properties;  
  **Data**: [City Districts](https://offenedaten-koeln.de/dataset/stadtbezirke-köln)

## 28. Black: Dark Map of Night Lights
- **Concept**: Black theme with raster night images.
- **Explanation**: Shows light pollution in Cologne.
- **Roadmap**: Invert raster, overlay.
- **Purpose**: Thematizes environmental protection.
- **Tech**: QGIS Raster Styling;  
  **Data**: [Orthophotos NW (Base)](https://open.nrw/dataset/56fb584b-10cf-4009-a405-0bef06bb3e00)

## 29. Raster: Orthophotos of the Old Town
- **Concept**: Raster map with aerial image overlay.
- **Explanation**: Detailed texture of the historic zone.
- **Roadmap**: Clip raster, georeference.
- **Purpose**: For visual exploration.
- **Tech**: QGIS Georeferencer;  
  **Data**: [Digital Orthophotos NW](https://open.nrw/dataset/56fb584b-10cf-4009-a405-0bef06bb3e00)

## 30. Makeover: Redesign of an Old Cologne Map
- **Concept**: Modern update of a historical map (e.g., 1900s).
- **Explanation**: Adds current Open Data (e.g., new bridges).
- **Roadmap**: Import scan, overlays, comparison.
- **Purpose**: Shows city evolution.
- **Tech**: Photoshop + QGIS;  
  **Data**: [Official City Map 1:20,000](https://open.nrw/dataset/ad880e57-73b9-4ea5-be7d-918af17fe7a5)
