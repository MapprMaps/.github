# MapprMaps

Source code for Andreas De Rosi's Mappr ecosystem — Mappr.co + Mappr.de editorial sites, the apps embedded in them, the external sites that share infrastructure, and the WP/Astro plumbing underneath.

This page is generated and kept in sync via the `mappr-tool` / `mappr-embedded-iframe` / `tile-proxy-client` / etc. **topic tags** applied across repos. Use those topics directly to filter in the GitHub search bar, e.g. `org:MapprMaps topic:tile-proxy-client`.

---

## Mappr.co — Embedded Apps (34)

Iframe-embedded into Mappr.co WP posts. Each app deploys to its own `*.mappr.co` subdomain on Vercel.

- [US-Geography-Quiz-Game](https://github.com/MapprMaps/US-Geography-Quiz-Game) → [mappr.co/us-geography-quiz/](https://www.mappr.co/us-geography-quiz/) · `us-geography-quiz.mappr.co` — US geography quiz game (states, capitals, regions)
- [airports_near_me](https://github.com/MapprMaps/airports_near_me) → [mappr.co/airports-near-me/](https://www.mappr.co/airports-near-me/) · `airports-near-me.mappr.co` — Find airports close to you or within a certain radius
- [antipode_finder](https://github.com/MapprMaps/antipode_finder) → [mappr.co/antipode-finder/](https://www.mappr.co/antipode-finder/) · `antipode-finder.mappr.co` — Antipode Finder
- [attractions_near_me](https://github.com/MapprMaps/attractions_near_me) → [mappr.co/tourist-attractions-near-me/](https://www.mappr.co/tourist-attractions-near-me/) · `attractions-near-me.mappr.co` — Find tourist attractions near any location
- [country_comparison](https://github.com/MapprMaps/country_comparison) → [mappr.co/country-comparison/](https://www.mappr.co/country-comparison/) · `country-comparison.mappr.co` — Country Comparison Tool
- [csv_to_map](https://github.com/MapprMaps/csv_to_map) → [mappr.co/csv-to-map-converter/](https://www.mappr.co/csv-to-map-converter/) · `csv-to-map-converter.mappr.co` — Turn any csv with lat/long into a map
- [distance_calculator](https://github.com/MapprMaps/distance_calculator) → [mappr.co/geodistance-smart-calculator/](https://www.mappr.co/geodistance-smart-calculator/) · `geodistance-smart-calculator.mappr.co` — Calculate Distance from one place to another
- [drive_time_map](https://github.com/MapprMaps/drive_time_map) → [mappr.co/travel-time-map/](https://www.mappr.co/travel-time-map/) · `travel-time-map.mappr.co` — How far can you get within a certain time
- [flight_time_calculator](https://github.com/MapprMaps/flight_time_calculator) → [mappr.co/flight-time-calculator/](https://www.mappr.co/flight-time-calculator/) · `flight-time-calculator.mappr.co` — Calculates the average flight time
- [geojson_viewer](https://github.com/MapprMaps/geojson_viewer) → [mappr.co/geojson-viewer/](https://www.mappr.co/geojson-viewer/) · `geojson-viewer.mappr.co` — View geojson data on map
- [interactive_world_timezone_map](https://github.com/MapprMaps/interactive_world_timezone_map) → [mappr.co/interactive-world-time-zones-map/](https://www.mappr.co/interactive-world-time-zones-map/) · `world-time-zones-map.mappr.co` — Global Interactive Timezone Map
- [land_area_calculator_map](https://github.com/MapprMaps/land_area_calculator_map) → [mappr.co/land-area-calculator-map/](https://www.mappr.co/land-area-calculator-map/) · `land-area-calculator-map.mappr.co` — Draw area to calculate land size
- [lat_long_to_utm_converter](https://github.com/MapprMaps/lat_long_to_utm_converter) → [mappr.co/latitude-longitude-to-utm-converter/](https://www.mappr.co/latitude-longitude-to-utm-converter/) · `lat-long-to-utm-converter.mappr.co` — Convert lat/long coordinates to UTM
- [latlong_finder](https://github.com/MapprMaps/latlong_finder) → [mappr.co/latitude-longitude-finder/](https://www.mappr.co/latitude-longitude-finder/) · `latitude-longitude-finder.mappr.co` — Find lat long locations, or the lat long based on location.
- [live_earthquake_map](https://github.com/MapprMaps/live_earthquake_map) → [mappr.co/earthquakes-map/](https://www.mappr.co/earthquakes-map/) · `live-earthquake-map.mappr.co` — Live Earthquake Map
- [midpoint_finder](https://github.com/MapprMaps/midpoint_finder) → [mappr.co/midpoint-finder/](https://www.mappr.co/midpoint-finder/) · `midpoint-finder.mappr.co` — Midpoint Finder
- [places_within_radius](https://github.com/MapprMaps/places_within_radius) → [mappr.co/places-within-radius/](https://www.mappr.co/places-within-radius/) · `places-within-radius.mappr.co` — Shows places within a certain radius in time or distance
- [plus_code_converter](https://github.com/MapprMaps/plus_code_converter) → [mappr.co/plus-code-to-lat-long-converter/](https://www.mappr.co/plus-code-to-lat-long-converter/) · `plus-code-to-lat-long-converter.mappr.co` — Converts Google Plus Code into Lat Long
- [population_explorer](https://github.com/MapprMaps/population_explorer) → [mappr.co/population-explorer/](https://www.mappr.co/population-explorer/) · `population-explorer.mappr.co` — Population Explorer
- [static-map-maker](https://github.com/MapprMaps/static-map-maker) → [mappr.co/static-map-generator-with-marker/](https://www.mappr.co/static-map-generator-with-marker/) · `static-map-maker.mappr.co` — Static map generator with markers, exportable as PNG
- [sunrise_sunset_finder](https://github.com/MapprMaps/sunrise_sunset_finder) → [mappr.co/sunrise-sunset-finder/](https://www.mappr.co/sunrise-sunset-finder/) · `sunrise-sunset-finder.mappr.co` — Shows sunrise and sunset at any location in the world
- [thematic_map_creator](https://github.com/MapprMaps/thematic_map_creator) → [mappr.co/thematic-map-creator/](https://www.mappr.co/thematic-map-creator/) · `thematic-map-creator.mappr.co` — Thematic Map Creator
- [time_zone_finder](https://github.com/MapprMaps/time_zone_finder) → [mappr.co/time-zone-finder/](https://www.mappr.co/time-zone-finder/) · `time-zone-finder.mappr.co` — Intelligent Time Zone Finder
- [toilet_finder](https://github.com/MapprMaps/toilet_finder) → [mappr.co/toilet-finder/](https://www.mappr.co/toilet-finder/) · `toilet-finder.mappr.co` — Finds public toilets by location
- [travel_map](https://github.com/MapprMaps/travel_map) → [mappr.co/travel-map-planner-visualize-multi-stop-trip-itineraries/](https://www.mappr.co/travel-map-planner-visualize-multi-stop-trip-itineraries/) · `travel-map.mappr.co` — Show travel route on a map for publishing and sharing
- [true_size_compare](https://github.com/MapprMaps/true_size_compare) → [mappr.co/true-size-compare/](https://www.mappr.co/true-size-compare/) · `true-size-compare.mappr.co` — Compare the true size of countries
- [us_camping_finder](https://github.com/MapprMaps/us_camping_finder) → [mappr.co/us-camping-finder/](https://www.mappr.co/us-camping-finder/) · `us-camping-finder.mappr.co` — Finds camp sites and more in the USA territory
- [us_national_park_finder](https://github.com/MapprMaps/us_national_park_finder) → [mappr.co/us-national-park-finder/](https://www.mappr.co/us-national-park-finder/) · `us-national-park-finder.mappr.co` — Database of all the US National Parks
- [us_time_zones_map](https://github.com/MapprMaps/us_time_zones_map) → [mappr.co/us-time-zones-map/](https://www.mappr.co/us-time-zones-map/) · `us-time-zones-map.mappr.co` — US Time Zones Interactive Map
- [utm_to_lat_long_converter](https://github.com/MapprMaps/utm_to_lat_long_converter) → [mappr.co/utm-to-latitude-longitude-converter/](https://www.mappr.co/utm-to-latitude-longitude-converter/) · `utm-to-latitude-longitude-converter.mappr.co` — Converts UTM to latitude and longitude
- [what_is_my_elevation](https://github.com/MapprMaps/what_is_my_elevation) → [mappr.co/what-is-my-elevation/](https://www.mappr.co/what-is-my-elevation/) · `what-is-my-elevation.mappr.co` — What Is My Elevation
- [what_us_county_am_i_in](https://github.com/MapprMaps/what_us_county_am_i_in) → [mappr.co/what-county-am-i-in/](https://www.mappr.co/what-county-am-i-in/) · `what-county-am-i-in.mappr.co` — Find out in what US county I am currently in
- [where_am_i](https://github.com/MapprMaps/where_am_i) → [mappr.co/where-am-i/](https://www.mappr.co/where-am-i/) · `where-am-i.mappr.co` — Instant Location Lookup
- [zip_code_finder](https://github.com/MapprMaps/zip_code_finder) → [mappr.co/zip-code-finder/](https://www.mappr.co/zip-code-finder/) · `zip-code-finder.mappr.co` — Finds zip code in the world based on location

## Mappr.co — Standalone Tool Pages (1)

Tools that render directly as a Mappr.co page (no iframe).

- [cost_of_living](https://github.com/MapprMaps/cost_of_living) → [www.mappr.co/cost-of-living](https://www.mappr.co/cost-of-living/) — Cost of Living

## Mappr.co — Editorial & WP Infrastructure (5)

WordPress theme, custom blocks, static assets, and supporting infrastructure for Mappr.co + Mappr.de.

- [mappr-child](https://github.com/MapprMaps/mappr-child) → [www.mappr.co](https://www.mappr.co) — 2026 Theme for Mappr
- [mappr-maps](https://github.com/MapprMaps/mappr-maps) — Local-only QGIS workspace for editorial maps on mappr.co
- [mappr-static-assets](https://github.com/MapprMaps/mappr-static-assets) → [assets.mappr.co](https://assets.mappr.co) — Static assets for assets.mappr.co (logo, favicon, OG images)
- [mappr_custom_blocks](https://github.com/MapprMaps/mappr_custom_blocks) → [www.mappr.co](https://www.mappr.co) — Genesis Custom Blocks + display-posts CSS for mappr.co (astra-child)
- [mappr_de](https://github.com/MapprMaps/mappr_de) → [www.mappr.de](https://www.mappr.de) — WordPress infrastructure for mappr.de

## Astro Migrations (1)

- [mappr-de-astro](https://github.com/MapprMaps/mappr-de-astro) → [www.mappr.de](https://www.mappr.de) — Astro-based migration of mappr.de (work in progress)

## AirportRoutes.com + Airport Tools (5)

- [airportroutes](https://github.com/MapprMaps/airportroutes) → [www.airportroutes.com](https://www.airportroutes.com) — AirportRoutes.com main site — route maps, search, route detail pages
- [airportspots](https://github.com/MapprMaps/airportspots) → [www.airportspots.com](https://www.airportspots.com) — AirportSpots — Google Places near airports
- [bigairports](https://github.com/MapprMaps/bigairports) → [www.bigairports.com](https://www.bigairports.com) — BigAirports.com — world's biggest airports
- [ourairports-data](https://github.com/MapprMaps/ourairports-data) — Open-data downloads for OurAirports.com
- [ourairports_sync](https://github.com/MapprMaps/ourairports_sync) — Sync job pulling open-data from OurAirports.com (ETL)

## DataToMap (3)

- [datatomap-landing-page](https://github.com/MapprMaps/datatomap-landing-page) → [datatomap.com](https://datatomap.com) — DataToMap landing page (Sevalla-deployed)
- [datatomap_ai](https://github.com/MapprMaps/datatomap_ai) — AI-driven data-to-map self-service tool (DataToMap)
- [datatomap_webapp](https://github.com/MapprMaps/datatomap_webapp) → [app.datatomap.com](https://app.datatomap.com) — DataToMap web app — self-serve map making

## Other External Projects (1)

- [country_stays](https://github.com/MapprMaps/country_stays) → [country-stays.vercel.app](https://country-stays.vercel.app) — Tracks the time spent in a country

## Archived (2)

No longer maintained or deployed.

- [airports](https://github.com/MapprMaps/airports) — Largest Airports Database
- [datatomap](https://github.com/MapprMaps/datatomap) — 

## Uncategorized (1)

- [easymaps](https://github.com/MapprMaps/easymaps) — AI Studio template experiment — Gemini-based map app (not deployed)

---

## Shared Infrastructure

- **`tiles.mappr.co`** — Cloudflare Worker proxy for MapTiler tile/glyph/sprite/style requests. Used by `mappr_custom_blocks` (WordPress interactive maps) + 3 Vercel apps (`travel_map`, `land_area_calculator_map`, `thematic_map_creator`). Caches ~95% of tile loads at the CF edge so the team's shared MapTiler plan supports ~10× the traffic. Source: not yet in a repo; deployed via Cloudflare API. Tagged repos: `topic:tile-proxy-client`.
- **Vercel team `aderosi-projects`** — production hosting for all `mappr-tool` and `external-site` Vercel apps. Pro plan (required for private org-owned repos).
- **`wp-us` (Hetzner)** — production WordPress for Mappr.co, hosting `mappr_custom_blocks` deploys via `/srv/mappr-blocks-source/deploy.sh`.

Last generated: 2026-05-21.
