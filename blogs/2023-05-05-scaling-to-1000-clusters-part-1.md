---
title: Scaling to 1000 clusters - Part 1
url: https://metal3.io/blog/2023/05/05/Scaling_part_1.html
date: '2023-05-05'
author: Lennart Jern
feed_url: https://metal3.io/feed.xml
---
We want to ensure that Metal3 can scale to thousands of nodes and clusters. However, running tests with thousands of real servers is expensive and we don’t have access to any such large environment in the project. So instead we have been focusing on faking the hardware while trying to keep things as realistic as possible for the controllers. In this first part we will take a look at the Bare Metal Operator and the test mode it offers. The next part will be about how to fake the Kubernetes API of the workload clusters. In the final post we will take a look at the issues we ran into and what is being done in the community to address them so that we can keep scaling!
