# Ribbit Network Frequently Asked Questions
Frequently Asked Questions About the Ribbit Network

Ribbit Network is the world's largest crowdsourced network of open-source, low-cost, Greenhouse Gas Detection Sensors.

This project will create the world's largest Greenhouse Gas Emissions dataset that will empower anyone to join in the work on climate and provide informed data for climate action.

See more details about:
* [The Web Database](https://github.com/Ribbit-Network/ribbit-network-dashboard/blob/main/README.md)
* [The Frog Sensors](https://github.com/Ribbit-Network/ribbit-network-frog-sensor)

## F.A.Q.

### Do I need to build a Frog Sensor myself or can I buy one pre-assembled?
This project is and will always be Open-Source, meaning you are encouraged to build a sensor yourself! However, you can also purchase an assembled sensor at [ribbitnetwork.org](https://ribbitnetwork.org/).

### How does the sensor connect to the Internet?
The sensor uses a wi-fi radio to connect to the internet in order to send sensor data to the Ribbit Network Database and recieve Software Updates from the Ribbit team.

### Can the public data be used to locate my sensor?
[The sensor rounds it's GPS location](https://github.com/Ribbit-Network/ribbit-network-frog-sensor/issues/41) it publishes to the public database. This means that it is not possible to specifically locate the sensor. Additionally, the sensor does not contain or publish any personal data, limiting privacy concerns.

### Is it possible to connect the sensor using an ethernet cord instead of wi-fi?
Yes, this is possible, as there is an ethernet port on the Raspberry Pi carrier board inside. However, we suggest the wifi connection which allows the most flexibility in sensor placement.

### How long is the power cord?
The power cable is 1.5 meters (5 feet) long. An extension cord can easily be added if you need a longer cord.

### How does this more distributed sensor device approach compare to current techniques of monitoring atmospheric CO2 (e.g. from orbit via satellite)?

Atmospheric monitoring from space is an exciting development that has a lot of potential. I'm from an aerospace background, so that was of course where I looked first. However, it's not a magic bullet solution, so I think that the best version of the future is to develop both technologies that can work together:
* Climate tech satellites are the MOST expensive possible solution. For example, [NASA's OCO2, cost $467.7 million.](https://www.jpl.nasa.gov/news/press_kits/oco2-launch-press-kit.pdf) Currently the ground based frog sensors cost ~250 to build and assemble. At those prices, we could build 1868000 ground-based sensors for the cost of one satellite. And as you'll see in the next bullet point, we need more than one.
* The big problem with satellites is that they have a limited number of measurements that they can take in a day. [If you check out the "Approximate usable
daily soundings"](https://en.wikipedia.org/wiki/Space-based_measurements_of_carbon_dioxide#List_of_instruments) you can see how many measurements a day a sat can take. Using the OCO2 example again, it can take about 100,000 1.3 × 2.2 km squares a day. At those rates, it's very difficult to measure a meaningful portion of the earth with any frequency. I believe that having real time constant monitoring of an area is important to help catch peak emission events like a power plant natural gas plant turning on briefly during peak load. It's hard to imagine a cost effective sat solution that could provide that.
* Finally, the satellite data is awesome, but many of the sensing technologies are still unproven. They need a "truth" dataset to validate that the satellites are producing accurate data. A ground based network like Ribbit is an excellent complement to a sat network because it can provide that truth! 
