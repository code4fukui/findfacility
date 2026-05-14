> 日本語のREADMEはこちらです: [README.ja.md](README.ja.md)

A web application to find and map public facilities in Japanese cities like Kyoto, Osaka, and Kobe using open data.

## Demo

- Web application *(demo unavailable)*

## Features

-   **Facility Search**: Finds various public facilities such as monuments, evacuation shelters, and more.
-   **Geolocation**: Uses your device's location to automatically find the nearest facilities.
-   **Interactive Map**: Integrates with Google Maps to display facility locations with clickable markers for details.
-   **Location Presets**: Quickly jump to major locations like Kyoto, Osaka, and Kobe stations using a dropdown menu.
-   **Multi-language Support**: The interface is available in multiple languages, including English, Japanese, Spanish, Chinese, and more.

## Usage

1.  Open the web application *(demo unavailable)*.
2.  Allow location access to automatically find facilities near you.
3.  Use the dropdown menu to jump to a specific city, or browse the map. Click on a marker to see facility details.

## Data Sources

This application queries data from the following SPARQL endpoints:

-   [Kyoto City Open Data Portal](https://sparql.city.kyoto.lg.jp/sparql/)
-   [Osaka City Open Data Portal](https://data.city.osaka.lg.jp/sparql)
-   [Kobe City Open Data Portal](https://data.city.kobe.lg.jp/sparql)
-   [Open Data Portal (ODP)](https://sparql.odp.jig.jp/data/sparql)

## Credits

This project was created by Taisuke Fukuno. See also: [fukuno.js](lib/fukuno.js).

## License

MIT License — see [LICENSE](LICENSE).