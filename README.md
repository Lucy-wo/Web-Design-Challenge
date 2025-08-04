# Latitude — Weather vs. Latitude Visualization (OpenWeatherMap, Matplotlib, Bootstrap)

> A small data-viz site that explores how weather changes with latitude using a 500+ city sample from the OpenWeatherMap API, plotted with Matplotlib and presented as a Bootstrap site. :contentReference[oaicite:16]{index=16}

## Summary
The project assembles a multi-city weather dataset (temperature, humidity, cloudiness, wind speed) via **OpenWeatherMap**, visualizes each metric against **latitude**, and publishes the results as a simple multi-page site (Plots → Max Temp, Humidity, Cloudiness, Wind Speed; plus Comparison and Data). :contentReference[oaicite:17]{index=17} :contentReference[oaicite:18]{index=18}

## Goal
- Show clear, reproducible relationships between **latitude** and common weather variables.
- Provide a clean, navigable site so viewers can inspect plots and the full **source data table**. :contentReference[oaicite:19]{index=19}

## Procedure
1. **Acquire data** from the **OpenWeatherMap API** for **500+ cities**. :contentReference[oaicite:20]{index=20}  
2. **Plot** weather vs. latitude (temperature, humidity, wind, cloudiness) using **Matplotlib**. :contentReference[oaicite:21]{index=21}  
3. **Publish** results with a **Bootstrap** layout and navigation: *Plots* (four figures), *Comparison*, and *Data*. :contentReference[oaicite:22]{index=22}  
4. **Expose data** in a tabular page with key fields (City, Country, Date, Lat/Lng, Max Temp, Humidity, Cloudiness, Wind Speed). :contentReference[oaicite:23]{index=23}

## Results
- **Wind Speed vs. Latitude:** Textual takeaway on the page notes wind speed rises approaching the equator; southern hemisphere is lower than the northern during the sampled period. :contentReference[oaicite:24]{index=24}  
- **Cloudiness context:** Page notes continents are generally less cloudy than adjacent oceans (same latitude), with polar/seasonal nuances. :contentReference[oaicite:25]{index=25}  
- **Data availability:** A full **city-level table** is published to support plot reproduction and QA. :contentReference[oaicite:26]{index=26}

## Business Impact
- **Education & demos:** Compact example of API → analysis → web publishing for data-viz curricula and portfolio work.
- **Travel & operations:** Quick intuition about expected conditions by latitude (e.g., windiness, cloud patterns) for planning.
- **Team efficiency:** Clear data table and plots reduce back-and-forth when sharing methodology and inputs.

## Next Step to Make It Better
- **Data freshness:** Schedule periodic API pulls; store raw/processed datasets with timestamps.
- **Interactivity:** Add filtering (hemisphere, month/season), hoverable tooltips, and plot overlays (regression lines/fit bands).
- **Coverage & quality:** Increase city count, add time windows (seasonal slices), and document units/transformations on each page.
- **Reproducibility:** Publish the Python notebook/script that generates the figures and the table; pin library versions.
- **Accessibility & design:** Improve color/contrast, responsive image sizing, and fix typos (“Visualizations”). :contentReference[oaicite:27]{index=27}

---

### Site Map (for reference)
- **Home (Summary)** — project purpose and methods (API + Matplotlib). :contentReference[oaicite:28]{index=28}  
- **Plots** — Max Temp, Humidity, Cloudiness, Wind Speed. :contentReference[oaicite:29]{index=29}  
- **Comparison** — side-by-side thumbnails of plots. :contentReference[oaicite:30]{index=30}  
- **Data** — full table of all records used for plotting. :contentReference[oaicite:31]{index=31}
