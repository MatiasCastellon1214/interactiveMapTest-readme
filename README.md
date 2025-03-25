# Interactive Map Project - Jujuy Providence

<img src="images/Logotipo-CEICAAL-HD.png" width=300>

## 🔐 Note about the Repository

This public repository contains only the project documentation. **The complete source code and data are in a private repository** due to the sensitivity of the geospatial information handled. For access to the full repository or more information:

📧 Contact the author: mirtybmx@gmail.com

## 📌 Description

Interactive web application that visualises geospatial information of the province of Jujuy, Argentina, with a focus on limnology. The project allows to analyse:

- Watersheds and micro-watersheds.
- Network of watercourses
- Distribution of ecoregions
- Soil textural composition

## 🏛️ Institutional context

This project is developed within the framework of the activities of the **Centro de Investigación de Calidad de Aguas de Ambientes de Altura (CEICAAL) (Centre for Research on Water Quality in High Altitude Environments)**, where the author is part of the research team.  

The application constitutes a **geospatial complement** to the [Official Web Site of CEICAAL](https://ceicaal0.webnode.page/), extending the analysis capabilities of:

- Regional hydrological dynamics  
- Characterisation of high Andean watersheds  
- Water quality monitoring  

We invite you to explore our main site to learn more:

- Active research lines  
- Scientific publications  
- Projects under development  
- Community services  

*"Integrating limnological knowledge with geospatial technologies for sustainable water resources management"*

## ✨ Main Features

### 🗺️ Map Functionalities
- **Interactive layer contro**  (on/off)
- **Individual opacity control** for each layer
- **Detailed information** via tooltips and popups
- **Responsive interface** adaptable to different devices

## 🗃️ Data sources

| Layers               | Source                        | Link |
|--------------------|-------------------------------|--------|
| Basins           | Energy Secretariat        | [Dataset](http://datos.energia.gob.ar/dataset/2c8b870a-7d6b-4ad0-ace0-86c4a9c9e3c0/archivo/ace98ef1-e7a8-4d5d-8f44-2e85a2d824a4) |
| Water courses    | IDESA  Geoportal              | [WMS layer](http://geoportal.idesa.gob.ar/layers/geonode%3Acursosdeagua) |
| Micro-basins      | IDESA  Geoportal              | [GeoNode layer](http://geoportal.idesa.gob.ar/layers/geonode%3Acuencas_noa_ll) |
| Ecoregions      | Miguel Lillo Foundation      | [Publication](https://www.lillo.org.ar/editorial/index.php/publicaciones/catalog/book/253) |
| Soil Texture  | Earth Engine Data Catalog    | [Dataset](https://developers.google.com/earth-engine/datasets/catalog/OpenLandMap_SOL_SOL_TEXTURE-CLASS_USDA-TT_M_v02?hl=es-419) |

## 🛠️ Technologies Used

### GIS Tools
- <img src="https://upload.wikimedia.org/wikipedia/commons/9/91/QGIS_logo_new.svg" width=16> **QGIS** (Geospatial processing)
- **Qgis2Web** (Export to web format)

### Web development
- <img src="images/leaflet.jpg" width=20> **Leaflet.js** (Map visualisation)
- <img src="images/bootstrap-5.png" width=20> **Bootstrap 5** (Responsive design)
- <img src="images/javascript.png" width=20> **JavaScript** (Interactivity)
- <img src="images/github.jpg" width=20> **GitHub** (Version control)
- <img src="images/netlify.jpg" width=20> **Netlify** (Continuous Deployment)

## 🎯 How to Use the Map

1. **Basic navigation:
   - Zoom: Mouse wheel or +/- buttons.
   - Movement: Drag with the cursor

2. **Layer control**:
   - Activate/deactivate from the side panel.
   - Adjust opacity with sliders

3. **Data query**:
   - Click on any element to view attributes
   - Search by coordinates

## 🌍 Live Demo

![Demo GIF](images/interactiveMapProject.gif)  
[Access the application](https://ceicaalmap.netlify.app)

## 👨‍💻 Contact

**Matías Joel Castellón**  
- 📧 mirtybmx@gmail.com  
- 🔗 [LinkedIn](http://www.linkedin.com/in/matias-castellon)  
- <img src="images/Logotipo-CEICAAL-HD.png" width=20> [CEICAAL](https://ceicaal0.webnode.page/)
---

*Academic project developed with official public data (2024/2025)*
