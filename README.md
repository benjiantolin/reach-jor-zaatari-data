# Folder Structure

Files are separated into 2 categories, source `Data` and output `Maps`:

```
Data/
Maps/
```

# Shapefiles

Shapefiles are split into 4 file types, all 4 are required to use it properly. The following information is contained in each file:

- .shp — shape format; the feature geometry itself
- .shx — shape index format; a positional index of the feature geometry to allow seeking forwards and backwards quickly
- .dbf — attribute format; columnar attributes for each shape, in dBase IV format
- .prj — projection format; the coordinate system and projection information, a plain text file describing the projection using well-known text format

# Data Types

All data are separated into 5 categories:

```
Address/
Common/
Flood/
General_Infrastructure/ 
Waste_Water_Network/
```

## Address

Address files contains a single type:

```
Addresses_YYYY_MM
```

## Common

Common files are split into 4 types:

```
BlockBoundaries_YYYY_MM
CampFacilities_YYYY_MM
DistrictBoundaries_YYYY_MM
Roads_YYYY_MM
```

## Flood

Flood files are split into 3 types:

```
FloodPoints_YYYY_MM
FloodLines_YYYY_MM
FloodWaterPath_YYYY_MM
```

## General Infrastructure

General Infrastructure files are split into 4 types:

```
AssemblyPoints
GarbageBins_YYYY_MM
Mosques_YYYY_MM
WASH_YYYY_MM
```

## Waste Water Network

Waste Water Network files are split into 3 types:

```
Pipes_YYYY_MM
SepticTanks_YYYY_MM
SteelTanks_YYYY_MM
```

# Info

All shapefiles are in WGS 84 datum and UTM 37N projection.
