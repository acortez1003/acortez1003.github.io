---
title: "Real Estate MLS"
excerpt: "A full-stack web application designed to simulate a real estate listing platform. Utilizes SQL queries to search and filter based on various criteria. Integrated with MariaDB. [*repo*](https://github.com/acortez1003/Real-Estate-MLS).<br/><img src='/images/mls.PNG'>"
collection: portfolio
---

This is a full-stack web application for managing real estate listings, built using PHP, MySQL (MariaDB), and XAMPP as the local server environment. The application allows users to search, view, and and dynamic querying. [*repo*](https://github.com/acortez1003/Real-Estate-MLS)

## Search Functionality

The `Search Houses` and `Search Businesses` tabs filter properties based on user critera. The data submitted is passed to PHP scripts which interact with the MySQL database to retrieve the filtered results using `GET`.

![Search Houses](/images/mls.PNG)
![Search Businesses](/images/search_business.PNG)

## Dynamic Queries

The `Queries` tab allows users to write custom SQL queries. PHP is used to validate correct syntax. If valid, the application will take the user to a separate page with the results of that query.

![Query](/images/query.PNG)

## Fixed Data Views

The `Agents` and `Buyers` tabs display set information on the predefined variables.

![Agent and Buyer](/images/agent_buyer.PNG)

The `Listings` tab provides a detailed view of all active listings

![Listings](/images/listings.PNG)
