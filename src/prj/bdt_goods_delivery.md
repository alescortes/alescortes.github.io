---
layout: default
---

## [Big Data System to optimize the delivery of goods in the city of Milan](https://github.com/alescortes/food-delivery_bdt2022)
- Developed a big data system to generate orders to a food delivery service and to match a set of delivery men to deliver such orders. 
- The system includes a MongoDB database to store the deliverymen, the pending orders, and the processed orders and a MQTT queue which acts as a buffer in the data ingestion phase.
- Distances are calculated using Openrouteservice API.
- The result of the program is a flask dashboard which displays a map and a series of analytics about the orders.
- Code is packaged using docker

[back](./portfolio.md)