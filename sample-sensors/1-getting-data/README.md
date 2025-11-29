# Getting sensor data

For the PAE Living Building, a Skybox from SkyCentrics is being used. It collects the data on premise from different Building Automation Systems and transmits this data via high speed cellular technology to SkyCentric's cloud infrastructure.

The CMMS System in the cloudBIM utilizes an API to fetch the sensor data every 15 minutes (or more if needed).

### API Overview

[SkyCentric's API documentation](../docs/SkyCentrics-API-Examples-0731.pdf) The document contains brief instructions and examples of using the SkyCentrics API to access data from the Super SkyBox installed at PAE Living Building.

[Working example of a Postman Collection](../docs/PAE-SkyCentrics.postman_collection.json) with redacted secret.