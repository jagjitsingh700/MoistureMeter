# MoistureMeter

POC - Moisture Meters are used to measure percentage of water in a given substance. This system will simulate reading from a moisture meter device in a building every minute and store the measurements in a blob storage. In case there is a value over a given treshold in the blob storage, then the department managing the blob storage will react right away to stop a potential water leakage in the building to reduce damages. 

# 1. Logging System

In order for this system to provide value, it needs to be live 24/7. We need logging, telemetry and monitoring to ensure that. That is why we will develop an instrumentation strategy for the app.
