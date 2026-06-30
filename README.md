# Knowledge Graph Enrichment for Building-Oriented Smart Meter Data Analysis

This repository contains the code and data used in the thesis project on enriching a smart meter knowledge graph with building and location information.

The project investigates how semantic enrichment can improve building-level electricity analysis and support visual, interactive exploration of meter readings.

## Main files

- `final_enrichment_CQs.ipynb` — main notebook with the enrichment, querying, analysis, and evaluation workflow.
- `meter_locations.csv` — example meter metadata and location information.
- `kadaster_buildings.csv` — building data used for enrichment, queried from the Kadaster Knowledge Graph.
- `data/` — folder containing example smart meter knowledge graph data.

## Setup

To run the notebook, open Anaconda Prompt and run these commands:

1. Activate your Anaconda environment.
2. Install Jupyter Notebook 7:
   - `conda install -c conda-forge notebook`
3. Install the packages needed for interactive outputs:
   - `conda install -c conda-forge ipywidgets widgetsnbextension`
4. Start the notebook editor:
   - `python -m notebook`

Then open the repository folder in the notebook interface and run `final_enrichment_CQs.ipynb`.
