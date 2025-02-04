# GitOps repo for battery-simulation demo

## Components

- AMQ Broker Operator
- AMQ Broker: Used as MQTT broker
- Battery simulator: Simulates the battery of a driving Tesla S. The BMS is sending telemetry data to the MQTT broker.
- 

## Installation

Create a new Argo application that points to `groups/dev`. It will install all the components in the `battery-demo` namespace

