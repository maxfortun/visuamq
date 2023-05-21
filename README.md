# VisuAMQ
Visual path and timing tracking of messages through ActiveMQ 

## Background
[ActiveMQ](https://activemq.apache.org) is a wonderful message broker that, especially in concert with [Camel](https://camel.apache.org), makes creating data processing pipelines something of a dream come true. ActiveMQ is performant, scalable, easy to configure and enhance. VisuAMQ is a quick and dirty visualization tool for ActiveMQ that was thrown together to track breadcrumbs through the ActiveMQ destinations and map out the routes that messages take with the hopes to quickly pinpoint bottlenecks and routing issues. 

## Broker
Make sure your broker has [WebSockets](https://activemq.apache.org/websockets) enabled.

## Usage
VisuAMQ is a browser-only application and does not require any backend services.  
You can fork this repo and point your browser to it.  
Or, if you do not want to install it, just go [here](https://maxfortun.github.io/visuamq/) and put in your broker information.  
Watch as messages traverse the topics of your broker.  







