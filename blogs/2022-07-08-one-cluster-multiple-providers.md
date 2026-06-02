---
title: One cluster - multiple providers
url: https://metal3.io/blog/2022/07/08/One_cluster_multiple_providers.html
date: '2022-07-08'
author: Lennart Jern
feed_url: https://metal3.io/feed.xml
---
Running on bare metal has both benefits and drawbacks. You can get the best performance possible out of the hardware, but it can also be quite expensive and maybe not necessary for all workloads. Perhaps a hybrid cluster could give you the best of both? Raw power for the workload that needs it, and cheap virtualized commodity for the rest. This blog post will show how to set up a cluster like this using the Cluster API backed by the Metal3 and BYOH providers.
