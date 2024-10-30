# Parsing JSON file logs with the filelogreceiver

This repo is to accompany the blog I've written around effective parsing of JSON logs using the filelogreceiver.

You can run the collector and Aspire using docker-compose, and that will mount the `src/logs` folder inside the collector's container. If you then run the application in the `src/` folder, it will generate some logs for you to view.

You can then access Aspire using `localhost:18888`

## Pre-requistes

* .NET 8
* Docker