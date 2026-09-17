# Amazon India facilities

This directory records publicly sourced Amazon facilities in India while keeping source evidence separate from map-provider content.

## Fulfillment-center records

The four regional CSV files contain 69 distinct fulfillment-center codes transcribed from EasyWorks' public list dated 2026-07-15:

- `fulfillment_centers_east.csv`
- `fulfillment_centers_north.csv`
- `fulfillment_centers_south.csv`
- `fulfillment_centers_west_central.csv`

Each row preserves the published FC code, state, type, and street/postal address. The `google_maps_search_url` is generated from the FC code as a navigation link. It is not a harvested Google coordinate, place ID, rating, review, business listing, or photo record.

Source: https://easyworks.in/blog/amazonfbawarehouse

## Currency boundary

The EasyWorks list predates Amazon India's 2026-09-14 announcement of 20 new fulfillment centers, six new sort centers, and 150 new last-mile delivery stations. Amazon publicly named first-ever FC launches in Raipur, Ranchi, and Varanasi, but that announcement does not publish the complete exact-address list for the new FCs. Do not infer or manufacture those addresses.

Official expansion announcement: https://www.aboutamazon.in/news/operations/amazon-india-operations-network-expansion-biggest

The current CSV set should therefore be treated as a sourced July 2026 FC snapshot, not a complete September 2026 master inventory.

## Google Maps boundary

Google Maps links are outbound search links only. Do not bulk-copy or persist Google Maps place metadata, coordinates, ratings, reviews, imagery, or other Maps content into this corpus unless a separate license or Google-provided mechanism explicitly permits the intended reuse.

Google Maps Additional Terms: https://www.google.com/help/terms_maps/

## Photos

`licensed_photos.csv` contains only media for which an explicit reusable license was found. A photo must be labeled with what it actually depicts. Corporate-office or campus photographs must not be attached to fulfillment-center rows merely because they are in the same city.

Google Maps user photos are not presumed reusable. Link to the map page if useful; copy or rehost an image only when the rights holder has supplied a compatible license elsewhere or permission is otherwise clear.
