---
title: "Cluster-Based System Monitoring Dashboard"
excerpt: "Built and deployed a secure system monitoring dashboard using Flask and Netdata to track CPU, memory, disk, and network metrics across a 5-user cluster."
collection: portfolio
---

## Project Overview
Built and deployed a secure system monitoring dashboard using Flask and Netdata to track CPU, memory, disk, and network usage across a 5-user cluster. The app logs metrics to a local SQLite database and visualizes real-time trends using Chart.js.

## Tech Stack
Python, Flask, Netdata API (RESTful), SQLite, Chart.js, Gunicorn, Nginx, Linode, GitLab

## Key Features
* Real-time Metrics Visualization
    * Metrics  (CPU, memory, etc.) updated every 10 seconds
    * Visualized with dynamic line graphs using Chart.js
    * Provides instant feeback on system load and usage

![Live metrics](/images/metrics.png)

* Database Logging
    * Metrics from all cluster machines logged every 10 minutes
    * Stored using SQLite for lightweight persistence
    * Enables historical data trends and analysis

![Database logs](/images/database.png)

* Security and Deployment
    * Deployed on Linode with Nginx + Gunicorn
    * Secured with HTTPS via Certbot
    * Restricted Netdata API access to cluster members only

This project allowed me to learn how to manage and secure a live production server. I gained hands-on experience with REST APIs, background logging, and system-level monitoring.