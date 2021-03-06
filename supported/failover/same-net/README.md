## Traffic Distribution Type
For failover templates, you choose the way you want traffic distribution and failover to occur. Note that not all options are available for all templates, or may not be available at this time. 

  - **via-api** <br> In Failover via API (via-api) templates, failover is implemented by making API calls (vs. Gratuitous ARP) to read and update resources such as IP mappings (EIPs/NATs), LB/Forwarding Rules, and so on. 

  - **via-lb** <br> In failover via load balancer (via-lb) templates, an upstream load balancing service distributes traffic and determines which instances should receive traffic.
