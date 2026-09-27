# Data notes
## Grid3 Nigeria Operational Wards v3.0
-Source: https://data.grid3.org
-Downloaded: [date]
-8,809 features, polygons 
-Columns: ward_name (kardi), Lga_name (Birnin Kebbi), State (Kebbi)
-Covers my LGA fully

### OSM healthfacilities, extracted via QuickOSM
-Query: amenity=* within Birnin Kebbi North extent 
-Extracted: [26-09-2026]
COMPLETENESS; good (is in the same position compared with google satelite)
CURRENCY:UP TO DATE
POSITIONAL: Health facility point align well with the google imagery
ATTRIBUTE: Accessible
FITNESS: Adequate for access analysis
#CRS and preparations
-All source layers arrived in EPSG:4326
-Study area: Birnin kebbi LGA, extracted from GRID3 LGAs
-The LGA clip to study area, then  reprojected to EPSG:32631 (UTM 31N)
-Area check: Birnin Kebbi lga, matches published figure
-Working files in data/processed/, raw files untouched.
