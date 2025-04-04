<img src="https://img.shields.io/badge/Python-white?logo=Python" style="height: 25px; width: auto;">  <img src="https://img.shields.io/badge/pandas-white?logo=pandas&logoColor=250458" style="height: 25px; width: auto;">  <img src="https://img.shields.io/badge/NumPy-white?logo=numpy&logoColor=013243" style="height: 25px; width: auto;">  <img src="https://img.shields.io/badge/Geopandas-white?logo=geopandas" style="height: 25px; width: auto;">  <img src="https://img.shields.io/badge/Plotly-white?logo=plotly&logoColor=636efa" style="height: 25px; width: auto;">  <img src="https://img.shields.io/badge/Seaborn-white?logo=python" style="height: 25px; width: auto;">  <img src="https://img.shields.io/badge/MLforecast-white?logo=python" style="height: 25px; width: auto;">  <img src="https://img.shields.io/badge/Scikit--learn-white?logo=scikit-learn" style="height: 25px; width: auto;">

## Food Carbon Impact: What's on Your Plate?

This report breaks down a data project that analyzes how much our food choices impact climate change, using data from the Food and Agriculture Organization (FAO).

## What We Did

We looked at food emissions from different angles:
- How food shipping creates emissions
- Which foods produce the most greenhouse gases
- How countries compare in food-related emissions
- What might happen with food emissions in the future

## Key Findings

### Food Miles Matter

Looking at how food shipping affects climate:
- Asia and Europe import the most food
- North America and South America export the most
- The North America → Asia route creates the most shipping emissions
- Europe's total imports generate the highest shipping emissions globally

<p align="center">
    <b>2022 Food Emissions Between Continents in relation with trade</b>
</p>
<p align="center">
    <img src="./readme_img/sankey.png" alt="Sankey Diagram of Food Trading Emissions" style="width: 70%;">
    <br>
</p>

Crops travel more than animal products, with **soya beans** being the most transported food item, causing **over 20,000 kilotonnes of CO2-equivalent emissions yearly**. Most soya goes to Europe.

<p align="center">
    <b>Soya Beans Top Contaminating Trades (2021)</b>
<p align="center">
    <img src="./readme_img/map_soya.png" alt="Soya Beans CO2 Emissions" style="width: 70%;">
    <br>
</p>

### Production Emissions: Animals vs Plants

While crops cause more shipping emissions, livestock creates WAY more production emissions:
- Livestock emissions are growing by 2771.76 kilotonnes yearly
- Crop emissions grow by only 408.02 kilotonnes yearly
- Livestock emissions are about 7 times higher than crops
- Cattle products and rice are the highest emitters in their categories

<p align="center">
    <b>Crops vs Livestock Production Emissions (2021)</b>
<p align="center">
    <img src="./readme_img/items.png" alt="Food items CO2 Emissions" style="width: 55%;">
</p>

Why cattle and rice emit so much:
- Cattle: 90% comes from **enteric fermentation** (digestive methane) and **pasture** (nitrous oxide)
- Rice: 85% from **rice cultivation** (methane from flooded fields)

<p align="center">
    <img src="./readme_img/treemaps.png" alt="Food items CO2 Emissions" style="width: 100%;">
</p>

### Food Groups: Not Just Animal vs Plant

Foods cluster into four groups with surprising mixes of plants and animals:
- **Group 1**: Soybeans, wheat, maize - high shipping emissions
- **Group 4**: Cattle and rice - highest production emissions
- **Groups 2-3**: Other crops and animals with lower impacts

<p align="center">
    <b>Clustermap of Food Items with Environmental and Production Data</b>
<p align="center">
    <img src="./readme_img/clustermap.png" alt="forecast" style="width: 80%;">
</p>

### Future Trends

Food emissions have jumped 10% in two decades, hitting **16.4 gigatons of CO2** in 2021, and growing about 1.5% yearly. Asia leads emissions, and forecasts show continued growth through 2030, especially in Asia, Africa, and Europe.

<p align="center">
    <b>Forecasted Agrifood Emissions by Region</b>
<p align="center">
    <img src="./readme_img/forecast.png" alt="forecast" style="width: 100%;">
</p>

### Country Hotspots

Countries fall into six emission groups:
- **The Giant**: China alone - massive emissions across all categories
- **Major Emitters**: US and India
- **Deforestation Hotspots**: Brazil, Congo, and Indonesia
- **Emerging Deforestation Areas**: Bolivia, Peru, Mozambique
- **Big Agricultural Producers**: Argentina, Australia, Russia
- **Smaller Producers and Importers**: Over 100 countries including Spain, Chile, Portugal

<p align="center">
    <b>Map of Country Clusters (2021 data)</b>
<p align="center">
    <img src="./readme_img/map_clusters.png" alt="forecast" style="width: 80%;">
</p>

## Data Notes

The FAO data covers:
- 245+ countries and territories
- 200+ crops and livestock products
- Production, trade, and emissions info
- Historical data back to 1961

We processed this massive dataset to calculate:
- Shipping distances between countries
- Transportation methods and their emissions
- CO2 equivalents for different greenhouse gases
- Production emissions for different foods

  
