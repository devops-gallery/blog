+++
title = 'Platform KPIs Utilization'
date = 2023-11-18T13:42:33+01:00
draft = true
+++
# Average Utilization

Average Platform Utilization can represent how fully allocated resources are used.

| Measurement | Measurement method | Comments |
| --- | --- | --- |
| Total Average cpu, memory, filesystem utilization across all nodes | Prometheus metrics | Will depict platform utilization degree|
| Pods restarts by termination reason (oom / error) | Prometheus metrics | Could be an indicator how healthy apps are tuned |
| Node pod average density | Prometheus metrics | Will depict the state of average load distribution (how balanced pod distribution is) |
| Average application deployment frequency | Prometheus metrics | Will represent how active applications are developed |

Prometheus metrics are the best way to collect and represent data.
Probably some new recording rules should introduced to limit tool load especially
for long ranges like 6 months or a year.
