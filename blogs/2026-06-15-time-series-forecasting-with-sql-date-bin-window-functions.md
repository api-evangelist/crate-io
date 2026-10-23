---
title: "Time Series Forecasting with SQL: DATE_BIN, Window Functions, and Rolling Aggregations"
url: "https://cratedb.com/blog/time-series-forecasting-sql"
date: "2026-06-15"
author: "CrateDB"
feed_url: "https://cratedb.com/blog/rss.xml"
---
Every time series feature pipeline has the same shape: readings land in the database, a job exports a CSV or DataFrame to Python, pandas computes rolling means and standard deviations, and the result is written back as a training dataset. That loop adds latency, adds a failure point, and runs on a schedule rather than on live data. The aggregations (bucketing, rolling averages, deviation scoring) are SQL operations.
