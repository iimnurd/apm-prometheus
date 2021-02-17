# APM (Application Performance Management)

[![N|Solid](https://cldup.com/dTxpPi9lDf.thumb.png)](https://nodesource.com/products/nsolid)

## Definition
APM is acronym from  Application Performance Management but some people maybe familiar with Application Performance Monitoring, it’s okay because only little bit  difference between them. Monitoring is a term used when you are collecting data and presenting it to the end user. Management is when you have the ability to take action on your monitored systems such as restarting, change configuration, etc. Back to the topic,  on the Cloud Native era, an application cluster maybe have dozens (or maybe hundred) pods, its hard to monitor and get visibility manually, so the main idea of APM tools is getting visibility and availability of our applications in real time, easily and less effort.


## Why APM is Important
1. **Make sure availability of our applications is up and running well** 
Using APM, we can monitor our application is running well or not easily. A standard feature of APM is notification, we can set up a notification with basic or custom parameters. When something bad happen on our application or maybe our application not running well, APM will send us notification (maybe email, push notification, etc) as soon as possible.



2. **Make sure our application to meet a certain criteria**
Sometimes, we have some criteria for our application, such as if we want to make sure our performance application good, we setup a criteria all of response time of each service under 200 ms. Using APM, we can monitor it to make sure our application meet these criteria or not. And the best part is, we can set up a notification too.



3. **Tracing, troubleshooting and make right decision in the future**
When an incident happen to our system, we don't want it happen in the future. APM tools help us to find the root cause problem. We can collect usefull data such as incident time, application log, APM reporting, etc.




## Keys to Consideration to Build or Buy APM

Feature
First thing (and maybe most important i think) is identify the feature of the APM. Many APM have different feature, plus and minus, so our job is identify the most feature we need and choose the most suitable APM for company.

Cost
We need to define how much cost if we buy APM such as monthly/yearly cost? how much application or cluster will be covered?, etc. And if we choose to build own APM, how much license cost software (if any)? how much cost we hire person to build, maintain and monitor our APM ?

Technology & Implementation
We need to make sure what is the technlogy behind the APM, such as how the APM collect data? push data or pull data? how to implement to our system?. Some APM need requirement to implement on a system, it's important thing before we choose APM.

Support & SLA
Before we choose to buy or build APM, we need to know how its support works? how about the SLA? it is important thing because related about our bussiness. Good support and good SLA will improve company

## Prometheus and Grafana

You can follow this tutorial to build your own APM using prometheus and grafana [Prometehus](https://github.com/iimnurd/apm-prometheus/blob/master/Prometheus.md)















