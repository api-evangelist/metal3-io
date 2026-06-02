---
title: Scaling to 1000 clusters - Part 3
url: https://metal3.io/blog/2024/05/30/Scaling_part_3.html
date: '2024-05-30'
author: Lennart Jern
feed_url: https://metal3.io/feed.xml
---
In part 1, we introduced the Bare Metal Operator test mode and saw how it can be used to play with BareMetalHosts without Ironic and without any actual hosts. We continued in part 2 with how to fake workload clusters enough for convincing Cluster API’s controllers that they are healthy. These two pieces together allowed us to run scaling tests and reach our target of 1000 single node clusters. In this final part of the blog post series, we will take a look at the results, the issues that we encountered and the improvements that have been made.
