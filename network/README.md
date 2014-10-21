# Network Infrastructure

* Physical Infrastructure
  * bandwidth, utilization of individual links
  * CoS/QoS rate/drops
  * L2/L2 protocol health
  * churn
  * reachabality
* Per port:
  * packets/sec
  * packet size
  * buffer utilization
  * perf flow into:
    * app injection BW
    * app injection rate
    * app consumption rate
    * app consumption BW
* Component:
  * links
  * errors
  * latency
  * utilization
* Topology:
  * app to app latency
  * app to app low
  * symmetry
* Top Talkers Report
  * Information about which backend services are the busiest
  * Details about which external peers you transit with the most (broken down by egress port or ASN)
* Internet Convergence Reporting
  * BGPlay - http://bgplay.routeviews.org/
  * BGPmon - http://bgpmon.netsec.colostate.edu/
