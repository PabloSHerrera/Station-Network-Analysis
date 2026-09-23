# Station Network Analysis — Bike-Sharing System

Network analysis of a public bike-sharing system. Stations are modeled as nodes and trips between them as edges, in order to identify the most important stations in the network and group stations with similar usage patterns.

## Objectives

- Clean and structure raw trip data
- Describe the system through general statistics
- Identify key stations using graph centrality metrics (degree and betweenness)
- Group stations into clusters based on their characteristics

## Methodology

| Step | Notebook | Description |
|---|---|---|
| 1 | `Tratamiento De Datos.ipynb` | Data cleaning and preprocessing |
| 2 | `Estadisticas Generales.ipynb` | Descriptive statistics of trips and stations |
| 3 | `Clustering.ipynb` | Station clustering |

**Centrality metrics used:**
- **Degree centrality:** stations with the most direct connections to other stations
- **Betweenness centrality:** stations that act as bridges along the shortest paths of the network

## Outputs

- `datos limpios.csv` — cleaned dataset
- `top_estaciones_grado.csv` — top stations by degree centrality
- `top_estaciones_betweenness.csv` — top stations by betweenness centrality

## Tech Stack

Python · pandas · NetworkX · scikit-learn · Jupyter Notebook

## How to Run

1. Clone the repository
2. Install dependencies: `pip install pandas networkx scikit-learn matplotlib`
3. Run the notebooks in the order shown above

---

*Developed as part of a seminar project in Applied Mathematics at Universidad del Valle de Guatemala.*
