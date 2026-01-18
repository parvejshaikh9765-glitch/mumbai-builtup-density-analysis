# Mumbai-builtup-density-analysis
Ward-level built-up density analysis of Mumbai using QGIS and OpenStreetMap data, measuring built-up area as a proportion of ward area to understand urban growth patterns.
# Mumbai Built-up Density Analysis

## Overview
This project analyzes ward-level built-up density across Mumbai using GIS techniques.
Built-up density is calculated as the ratio of total built-up area to total ward area,
helping understand spatial patterns of urban growth and concentration.

## Study Area
- Mumbai Municipal Corporation (MCGM) wards

## Data Sources
- Ward boundaries: Municipal Corporation of Greater Mumbai (MCGM)
- Building footprints: OpenStreetMap (OSM)

⚠️ Due to GitHub size limits, full datasets are hosted externally.
See the `data/README.md` for download links.

## Methodology
1. Reprojected all layers to **EPSG:32643 (WGS 84 / UTM Zone 43N)**
2. Cleaned and clipped building footprints to ward boundaries
3. Calculated:
   - Ward area (sq. km)
   - Total built-up area per ward (sq. km)
4. Derived built-up density:

Built-up Density = Built-up Area / Ward Area

5. Classified density using Natural Breaks (Jenks)
6. Visualized results in QGIS using graduated symbology

## Outputs
- Ward-level built-up density map
- Classified density categories:
- Very Low
- Low
- Moderate
- High
- Very High

## Tools Used
- QGIS
- OpenStreetMap
- GitHub
- Google Drive (data hosting)

## Author
Pravesh Shaikh
Linkedin https://www.linkedin.com/in/pravesh-shaikh-b1386930a?lipi=urn%3Ali%3Apage%3Ad_flagship3_profile_view_base_contact_details%3BEOM5TzPORV2MtHwNUscttQ%3D%3D
