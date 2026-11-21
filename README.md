<h1 align="center">Landon Melesky</h1>
<p align="center"><b>GIS · Remote sensing · Spatial statistics · GeoAI</b><br>
M.S. Geography, Texas A&amp;M University · FAA Part 107 remote pilot · Bryan–College Station, TX</p>

<p align="center">
  <a href="https://landon2199.github.io"><img alt="Portfolio" src="https://img.shields.io/badge/Portfolio-landon2199.github.io-500000?style=for-the-badge"></a>
  <a href="https://www.linkedin.com/in/landonmelesky/"><img alt="LinkedIn" src="https://img.shields.io/badge/LinkedIn-landonmelesky-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white"></a>
  <a href="https://orcid.org/0009-0001-8854-1789"><img alt="ORCID" src="https://img.shields.io/badge/ORCID-0009--0001--8854--1789-A6CE39?style=for-the-badge&logo=orcid&logoColor=white"></a>
  <a href="mailto:landon2199@tamu.edu"><img alt="Email" src="https://img.shields.io/badge/Email-landon2199%40tamu.edu-555555?style=for-the-badge&logo=gmail&logoColor=white"></a>
</p>

I turn drone, aerial and satellite imagery into maps people can act on, and I show how far each answer can be trusted. Every project below runs from public data and reports its own accuracy: spatial hold-outs instead of random ones, 95% intervals, and a second, independent computation of the result.

I'm looking for GIS and remote sensing internships, especially with Esri and Esri partners and in the Houston area.

## Featured projects

All built from public data, with code, tests and write-ups, and with an AI coding assistant (Claude Code); each repository says so. Click a picture for the repository.

**ArcGIS and Esri**

<table>
<tr>
<td width="33%" valign="top"><a href="https://github.com/landon2199/agentic-site-selection"><img src="https://landon2199.github.io/assets/img/siteselect-hero.png" alt="Agentic site selection"></a><br><b><a href="https://github.com/landon2199/agentic-site-selection">Agentic site selection</a></b><br>Agents call ArcPy tools through an MCP server to rank Harris County hexes for a coffee shop; expert overlay vs Esri embeddings on held-out shops (AUC 0.71 vs 0.74). <a href="https://landon2199.github.io/agentic-site-selection/">Map</a><br><sub>ArcPy · agents · embeddings</sub></td>
<td width="33%" valign="top"><a href="https://github.com/landon2199/arcgis-accuracy-toolbox"><img src="https://landon2199.github.io/assets/img/toolbox-hero.png" alt="ArcGIS accuracy toolbox"></a><br><b><a href="https://github.com/landon2199/arcgis-accuracy-toolbox">Accuracy Assessment Toolbox for ArcGIS Pro</a></b><br>Python toolbox for sample size, area-adjusted accuracy with 95% intervals and spatial blocks; reproduces Olofsson et al.'s worked example.<br><sub>ArcPy · Python toolbox</sub></td>
<td width="33%" valign="top"><a href="https://github.com/landon2199/esri-spatial-data-science"><img src="https://landon2199.github.io/assets/img/sds-hero.png" alt="Esri Spatial Data Science MOOC rebuilt in ArcPy"></a><br><b><a href="https://github.com/landon2199/esri-spatial-data-science">Esri Spatial Data Science MOOC, rebuilt in ArcPy</a></b><br>Holding out whole states drops the turnout model's validation R² from 0.76 to 0.58; a different Gi* neighborhood cuts SNAP hot and cold spot counties from 1,912 to 759.<br><sub>ArcPy · spatial statistics</sub></td>
</tr>
</table>

**Houston and the Gulf Coast**

<table>
<tr>
<td width="33%" valign="top"><a href="https://github.com/landon2199/houston-heat-hotspots"><img src="https://landon2199.github.io/assets/img/heat-hero.png" alt="Houston heat hot spots"></a><br><b><a href="https://github.com/landon2199/houston-heat-hotspots">Houston heat hot spots</a></b><br>Landsat surface temperature for 1,111 tracts: Gi* and LISA hot spots, spatial error model (+0.1 NDVI ≈ 1.9 °C cooler). <a href="https://landon2199.github.io/houston-heat-hotspots/map.html">Map</a><br><sub>PySAL · Landsat · spatial regression</sub></td>
<td width="33%" valign="top"><a href="https://github.com/landon2199/texas-flood-exposure-sql"><img src="https://landon2199.github.io/assets/img/flood-hero.png" alt="Flood exposure"></a><br><b><a href="https://github.com/landon2199/texas-flood-exposure-sql">Critical facilities in flood zones</a></b><br>Spatial SQL screen of 2,860 Gulf Coast facilities against FEMA flood zones: 250 inside, including 13 hospitals. <a href="https://landon2199.github.io/texas-flood-exposure-sql/map.html">Map</a><br><sub>DuckDB · spatial SQL · FEMA NFHL</sub></td>
<td width="33%" valign="top"><a href="https://github.com/landon2199/brazos-fire-access"><img src="https://landon2199.github.io/assets/img/fire-hero.png" alt="Fire station access"></a><br><b><a href="https://github.com/landon2199/brazos-fire-access">How fast can a fire engine reach you?</a></b><br>Drive-time coverage from 25 Brazos County stations (82% of residents within 4 min) and optimal new sites (MCLP, p-median). <a href="https://landon2199.github.io/brazos-fire-access/map.html">Map</a><br><sub>OSMnx · PuLP · network analysis</sub></td>
</tr>
</table>

**Remote sensing and GeoAI**

<table>
<tr>
<td width="33%" valign="top"><a href="https://github.com/landon2199/open-earth-mcp"><img src="https://landon2199.github.io/assets/img/mcp-hero.png" alt="Open Earth MCP server"></a><br><b><a href="https://github.com/landon2199/open-earth-mcp">Open Earth MCP server</a></b><br>Gives AI assistants traceable access to Sentinel-2 NDVI, ESA WorldCover and Copernicus DEM, with a tool that verifies its own answers. <a href="https://glama.ai/mcp/servers/landon2199/open-earth-mcp">Listed on Glama</a>.<br><sub>Python · MCP · STAC</sub></td>
<td width="33%" valign="top"><a href="https://github.com/landon2199/geoai-sam-naip"><img src="https://landon2199.github.io/assets/img/sam-hero.jpg" alt="Segment Anything on NAIP"></a><br><b><a href="https://github.com/landon2199/geoai-sam-naip">Segment Anything on aerial imagery</a></b><br>Text-prompted SAM on NAIP: building F1 0.69 (95% CI 0.62–0.74) on a held-out area vs 0.50 for a spectral baseline.<br><sub>PyTorch · SAM · Grounding DINO</sub></td>
<td width="33%" valign="top"><a href="https://github.com/landon2199/sentinel2-landcover-ml"><img src="https://landon2199.github.io/assets/img/landcover-hero.png" alt="Sentinel-2 land cover"></a><br><b><a href="https://github.com/landon2199/sentinel2-landcover-ml">Land cover with honest accuracy</a></b><br>Sentinel-2 random forest: random CV said 0.89, spatial blocks said 0.83. Olofsson area-adjusted estimates with 95% intervals.<br><sub>scikit-learn · Sentinel-2 · spatial CV</sub></td>
</tr>
</table>

More: [COVID-19 in Texas, 2020–2023](https://github.com/landon2199/texas-covid-spacetime) (space-time hot spots, [map](https://landon2199.github.io/texas-covid-spacetime/)) · [foundation-model similarity search](https://github.com/landon2199/geoai-embedding-search) (SSL4EO embeddings over 7,974 Sentinel-2 chips) · [College Station daylight](https://github.com/landon2199/college-station-daylight) (NOAA solar equations)

## Tools I use

**GIS:** ArcGIS Pro, ArcPy, ArcGIS Online, StoryMaps, QGIS, geodatabase design, spatial SQL (SQL Server, DuckDB)<br>
**Remote sensing:** Sentinel-2, Landsat, NAIP, hyperspectral (ENVI), Google Earth Engine, STAC<br>
**Machine learning and GeoAI:** scikit-learn, PyTorch, TorchGeo, Segment Anything, embeddings, MCP servers and tool-using agents<br>
**Spatial statistics:** PySAL (Gi*, Moran's I, LISA, spatial regression), space-time hot spots<br>
**Programming:** Python (GeoPandas, rasterio, xarray, GDAL), SQL, R, JavaScript

## Now

- M.S. research: part of a funded project led by my advisor, Dr. Leila Character, using drone hyperspectral imaging and machine learning to study tropical forest vegetation. Details stay private until published.
- Graduate Teaching Assistant: four GIS lab sections, 80 students (Geodatabases, plus a Principles of GIS lab)
- Team lead on an eight-person study of vegetation along Texas pipelines with Sentinel-2 and Landsat
- Earned in October 2026: FAA Part 107 Remote Pilot Certificate and Esri's Spatial Data Science MOOC certificate
