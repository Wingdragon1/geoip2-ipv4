Database of IPv4 address networks with their respective geographical location.

## Data

Based on GeoLite2 Country Free Downloadable Databases as of Jan 30, 2024 http://dev.maxmind.com/geoip/geoip2/geolite2/

Two files were used to generate this dataset: 

```
GeoLite2-Country-Blocks-IPv4.csv  
GeoLite2-Country-Locations-en.csv  
```

with the following considerations:  

- Where geoname_id was not available, registered_country_geoname_id was used.
- Where geoname_id and registered_country_genoname_id where empty, geoname_id, continent_code, continent_name, country_iso_code and country_name are empty.

## Preparation

Original CSVs were imported into MS Excel, then with the use of Power Query Editor Continent and Country names were created based on matching geoname_id's.

## License

Datapackage: Creative Commons Zero 

Original CSV: This dataset includes GeoLite2 data created by MaxMind, available from www.maxmind.com
