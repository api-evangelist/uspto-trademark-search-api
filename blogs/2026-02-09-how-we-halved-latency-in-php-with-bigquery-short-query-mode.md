---
title: "How We Halved Latency in PHP with BigQuery Short Query Mode"
url: "https://medium.com/google-cloud/how-we-halved-latency-in-php-with-bigquery-short-query-mode-c29eee204b0a?source=rss-350650c446a8------2"
date: "2026-02-09"
author: "Márton Kodok"
feed_url: "https://martonkodok.medium.com/feed"
---
In the world of web development, especially with “snap-on” PHP applications, latency is the enemy. We extensively use Google BigQuery for our data analytics and search features. While BigQuery is a powerhouse for processing massive datasets, we noticed a significant bottleneck when running small, frequent queries — like returning small amounts of rows from a table.
