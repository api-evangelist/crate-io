---
title: "How to Ingest OPC-UA and MQTT Data into SQL with Telegraf and CrateDB"
url: "https://cratedb.com/blog/opcua-mqtt-telegraf-cratedb"
date: "2026-06-04"
author: "CrateDB"
feed_url: "https://cratedb.com/blog/rss.xml"
---
OPC-UA and MQTT are the two protocols that move data off industrial equipment and IoT devices. Getting those readings into a SQL database without writing a custom integration layer is where most setups stall. This tutorial shows how Telegraf bridges that gap: OPC-UA or MQTT on the input side, CrateDB on the output, and standard SQL from the moment the first reading lands.
