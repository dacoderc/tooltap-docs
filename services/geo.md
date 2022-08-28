# GeoLocation API

This API is focused on services around network IP and a Geo Location

## Status: available APIs and roadmap

| API | Status |
| --- | --- |
| IPv4 -> Geolocation | Production | 
| IPv6 -> Geolocation | Backlog |


### IPv4 to Geolocation
> [Full API documentation](https://tooltap.stoplight.io/docs/tooltap-api-services/b6bb5530e4aa5-resolve-i-pv4-to-geo-location)

Use this call to retrieve the following geo-related information:

| Returned Data | Description |
| --- | --- |
| continent_name | Continent associated with the queried IP |
| continent_code | 2-letter representation of continent name |
| country_name | Country associated with the queries IP |
| country_code | [ISO-3166](https://en.wikipedia.org/wiki/ISO_3166-1_alpha-2) country code | 
| currency_code | [ISO-4217](https://en.wikipedia.org/wiki/ISO_4217) National currency code |
| us_state_name | US state code, relevant only when Country is USA |
| us_state_code | US state name, relevant only when Country is USA |
| district | District or region name |
| city | City name |
| zip | Zip code |
| latitude | Geographic latitude value |
| longitude | Geographic longitude value |
| timezone | Timezone descriptor |
| tz_offset_utc | Timezone offset from UTC, in seconds |

