+++
title = 'Platform KPIs Incidents'
date = 2023-11-18T13:42:44+01:00
draft = true
+++
# Platform Incident Analysis

Considering growing adoption of Incidentio based approach, to the incidents management it could be interesting to get insights about platform incidents statistics.

|Measurement | Measurement method | Comments |
| --- | --- | --- |
|Platform incident frequency|Incidentio| How intense there are incident generation in platform dimension|
|Platform incident resolution time|Incidentio| How fast context incidents are closed |
|Mean time to understanding (MTTU)|Incidentio| Or any other statistics, provided by incidentio |

How to Measure and Represent

As we are heavily using Prometheus and Grafana, it is reasonable to use them as
first level tools for data collection and representation.

As we are using Incidentio, it is reasonable to use it as a data source,
but there is no available integration between Inidentio and Prometheus/Grafana,
so we need a spike to verify adapter idea.