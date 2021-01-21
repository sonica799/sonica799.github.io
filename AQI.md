---
layout: proj
title: AQI Dashboard
permalink: /AQI Dashboard/
---
## Introduction

A dashboard developed and designed to display Climate Change Parameters:- Temperature (in C), Relative Humidity, PM 10, PM 2.5, O3, NO2, SO2, and CO. Air Quality Index (AQI) is displayed via a radial chart.

**Check it out at [nexLOOP](https://nexloop.in)**

## Technical Details

### Libraries and Dependencies

**1. ReactJS:** This open source JavaScript library provides us with an attractive UI and easily integrable code.

**2. Axios:** It is a promise-based HTTP client that makes HTTP requests to fetch data dynamically from the API.

**3. [React ApexCharts:](https://apexcharts.com/docs/react-charts/)** A wrapper component for ApexCharts, it is used in the application to create stunning and dynamic charts. 

**4. [World AQI API:](https://aqicn.org/api/)** This API delivers real-time parameters (Temperature (in C), Relative Humidity, PM 2.5, PM,10, O3, SO2, NO2, CO and AQI)


### Flowchart

<img src="..\img\AQI\Dashboard Flowchart.png" style="width: 60vw; height: 50vw;" alt="Dashboard Flowchart">

### Air Pollutants Parameters

* **AQI:**
An Air Quality Index (AQI) is a number used by government agencies to measure the air pollution levels and communicate it to the population. As the AQI increases, it means that a large percentage of the population will experience severe adverse health effects. The measurement of the AQI requires an air monitor and an air pollutant concentration over a specified averaging period. The results are grouped into ranges, and each range is assigned a descriptor, a color code and a standardized public health advisory.

* **Temperature (T in C):**
Temperature is the measure of thermal or internal energy of the molecules within an object or gas. As an integral part of weather, temperature also determines the type of precipitation (rain/snow/sleet) that might occur if you are in a location that is experiencing near freezing conditions.

* **Relative Humidity (H):**
Relative humidity is given as a percentage and tells you how close the air is to being saturated. If the relative humidity is 100%, the air is saturated. If the relative humidity is 50%, the air contains half the water vapor required for it to be saturated. If the amount of water vapor in the air increases, the relative humidity increases, and vice versa. 

* **Particulate matter (PM10/2.5):**
Airborne particulate matter varies widely in its physical and chemical composition, source and particle size. PM10 particles (the fraction of particulates in air of very small size (<10 µm)) and PM2.5 particles (<2.5 µm) are of major current concern, as they are small enough to penetrate deep into the lungs and so potentially pose significant health risks. Larger particles meanwhile, are not readily inhaled, and are removed relatively efficiently from the air by sedimentation. The principal source of airborne PM10 and PM2.5 matter in  cities is road traffic emissions, particularly from diesel vehicles.

* **Nitrogen oxides (NOx):**
NOX is a term used to describe a mixture of nitric oxide (NO) and nitrogen dioxide (NO2). They are inorganic gases formed by combination of oxygen with nitrogen from the air. NO is produced in much greater quantities than NO2, but oxidises to NO2 in the atmosphere. NO2 causes detrimental effects to the bronchial system. Nitrogen dioxide concentrations frequently approach, and sometimes exceed air quality standards in many cities. NOx is emitted when fuel is being burned e.g. in transport, industrial processes and power generation.

* **Ozone (O3):**
Ground-level ozone (O3), unlike other pollutants mentioned, is not emitted directly into the atmosphere, but is a secondary pollutant produced by reaction between nitrogen dioxide (NO2), hydrocarbons and sunlight. Ozone levels are not as high in urban areas (where high levels of NO are emitted from vehicles) as in rural areas. Sunlight provides the energy to initiate ozone formation; consequently, high levels of ozone are generally observed during hot, still sunny, summertime weather.

* **Sulphur dioxide (SO2):**
Fossil fuels contain traces of sulphur compounds, and SO2 is produced when they are burnt. The majority of the SO2 emitted to the air is from power generation, and the contribution from transport sources is small (shipping being an exception). Exposure to SO2 can damage health by its action on the bronchial system. Sulphuric acid generated from atmospheric reactions of SO2 is the main constituent of acid rain, and ammonium sulphate particles are the most abundant secondary particles found in air.


* **Carbon monoxide (CO):**
CO is an odourless, tasteless and colourless gas produced by the incomplete burning of materials which contain carbon, including most transport fuels. CO is toxic, acting by reaction with haemoglobin and reducing its capacity for oxygen transport in the blood. Even in busy urban centres, CO concentrations rarely exceed health related standards.

### AQI Categories

<img src="..\img\AQI\AQI Chart.png" style="width: 90vw; height: 45vw;" alt="AQI Chart">

## Demonstration

The values of parameters, AQI chart data and chart colours are dynamically rendered after every search. 

* **Default City: Bangalore**

<img src="..\img\AQI\Demo_1.jpg" style="width: 90vw; height: 40vw;" alt="AQI Demo">


* **Input City: Pune**

<img src="..\img\AQI\Demo_2.jpg" style="width: 90vw; height: 40vw;" alt="AQI Demo">


* **Input City: Jaipur**

<img src="..\img\AQI\Demo_3.jpg" style="width: 90vw; height: 45vw;" alt="AQI Demo">


* **Input City: Delhi**

<img src="..\img\AQI\Demo_4.jpg" style="width: 90vw; height: 40vw;" alt="AQI Demo">


* **Learn More Button:**
The Learn More is added to inform the users about information regarding the parameters and their significance.

<img src="..\img\AQI\Demo_5.jpg" style="width: 90vw; height: 40vw;" alt="AQI Demo">

_src: ([https://www.airqualitynow.eu/pollution_home.php](https://www.airqualitynow.eu/pollution_home.php), [https://www.aqi.in/blog/aqi/](https://www.aqi.in/blog/aqi/), [https://climate.ncsu.edu/edu/Background](https://climate.ncsu.edu/edu/Background))_
