# opendatacity

> 日本語のREADMEはこちらです: [README.ja.md](README.ja.md)

A collection of dashboards, visualizations, and tools for analyzing open data related to Japanese local governments.

This project uses data on municipal websites, open data initiatives, and educational preparedness to create interactive maps and charts.

## Visualizations & Demos

### Security & Domain Analysis
*   [**AOSSL Dashboard (Municipalities)**](https://code4fukui.github.io/opendatacity/citiesratio7x7ssl.html) - A 7x7 tabular map visualizing the SSL adoption rate of municipal websites across Japan.
*   [**Web Security Rate**](https://code4fukui.github.io/opendatacity/localgovjp-secureornot.html) - A pie chart showing the ratio of `https` to `http` across all local government websites.
*   [**Trustworthy Source Rate**](https://code4fukui.github.io/opendatacity/localgovjp-trust.html) - Analyzes the adoption of both SSL (`https`) and the official `.lg.jp` domain as a metric for information reliability.
*   [**Municipal Domain Census**](https://code4fukui.github.io/opendatacity/localgovjp-domain.html) - A census of domains used by Japanese municipalities.
*   [**AOSSL Dashboard (Prefectures)**](https://code4fukui.github.io/opendatacity/prefratio7x7ssl.html) - A tabular map focused on the SSL adoption rate of the 47 prefectural government websites.

### Open Data & Education Dashboards
*   [**Programming Education Readiness**](https://code4fukui.github.io/opendatacity/progedu7x7.html) - Visualizes the preparedness of municipalities for programming education, based on MEXT survey data.
*   [**Residential Address Data Publication Rate**](https://code4fukui.github.io/opendatacity/jpaddress.html) - A dashboard showing which municipalities have published official residential address data.
*   [**Open Data Cities by Region**](https://code4fukui.github.io/opendatacity/area.html) - A breakdown of open data-adopting cities by geographic region.
*   [**Open Data by Data Type**](https://code4fukui.github.io/opendatacity/type.html) - A chart showing the distribution of different categories of open data being published.
*   [**Open Data Evangelists**](https://code4fukui.github.io/opendatacity/evangelist.html) - A searchable list of official Open Data Evangelists in Japan.

### Quizzes
*   [**Quiz: Mura or Son?**](https://code4fukui.github.io/opendatacity/muraorson.html) - A simple quiz game that tests your knowledge of the pronunciation of Japanese village names (ending in むら vs. そん).

## How to Use

1.  Clone the repository: `git clone https://github.com/code4fukui/opendatacity.git`
2.  Navigate to the project directory: `cd opendatacity`
3.  Open any of the `.html` files in your web browser to view the visualizations. A local web server may be required for some functionalities.

The core dataset, `localgovjp.js`, can be updated or replaced to perform custom analyses.

## Data Sources & References

*   **[localgovjp](https://github.com/code4fukui/localgovjp)**: The primary dataset containing a list of Japanese local governments, their websites, and other metadata. (by Code for Fukui)
*   **[TabularMaps / カラム地図](https://github.com/tabularmaps/hq)**: The 7x7 grid map layout used for geographic visualizations.
*   **MEXT Programming Education Survey**: Data from the Ministry of Education, Culture, Sports, Science and Technology on programming education preparedness.
*   **Government CIO Portal**: Source for the Open Data Evangelist list.
*   **Geospatial Information Authority of Japan (国土地理院)**: Source for the residential address data.

## License

MIT License