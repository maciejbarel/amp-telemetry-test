# AMP Telemetry Test

This project was prepared as a code test for Hive Streaming. The goal of the app is to collect information and telemetries from the Azure Media Player video player and send it to a service for collection and later processing.

## Installation

Run `npm i` to install required dependencies.

## Build

Run `npm run build` to build the project. The build artifacts will be stored in the `dist/` directory.

## Start

Install dependencies and run `npm start` to run the minified app inside webpack dev server.


## Configuration

Add url option to plugin to set a service to send the data to. Otherwise the telemetries will be logged to console.
Add interval option to set custom interval (otherwise it is 30 s).
