# Grids - Solar Datasets

This folder serves as the main resource for all national-scale photovoltaic (PV) datasets. Each grid/country listed below has its own markdown file containing information about the available datasets, APIs, usage notes, and any relevant links.

## Table of Countries

| Country             | Link to Detailed Info               | Primary Data Sources     | Last Updated |
| ------------------- | ----------------------------------- | ------------------------ | ------------ |
| Germany 🇩🇪    | [germany.md](germany.md)       | ENTOSE           | 2025-02-04   |
| Netherlands 🇳🇱    | [netherlands.md](netherlands.md)       | Tennet, Ned.NL           | 2025-01-17   |
| United Kingdom 🇬🇧 | [united_kingdom.md](united_kingdom.md) | PVLive - Sheffield Solar | 2025-01-17   |

## How to Add a New Grid

1. Create a Markdown file (e.g: `Country/Region Grid.md`) in the `grids` folder based off the `GRID_TEMPLATE.md` file.
2. Add a new row in the table above that includes:
   - The Grid name (including a flag)
   - A link to your newly created file
   - The primary data sources or high-level notes
   - The last updated date
   - The country names should be listed in alphabetical order
3. In the new markdown file:
   - Provide links to official websites, APIs, or other relevant data sources.
   - Specify the strucutre of the historical data (update frequency, date range)
   - Include any notes about data quality, licensing restrictions, or access requirements.
   - (Optional) Outline how to query or retrieve data, if instructions are available.
