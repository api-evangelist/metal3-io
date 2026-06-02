---
title: Introducing Baremetal Operator end-to-end test suite
url: https://metal3.io/blog/2024/12/13/Introducing-BMO-E2E.html
date: '2024-12-13'
author: Lennart Jern
feed_url: https://metal3.io/feed.xml
---
In the beginning, there was metal3-dev-env. It could set up a virtualized “baremetal” lab and test all the components together. As Metal3 matured, it grew in complexity and capabilities, with release branches, API versions, etc. Metal3-dev-env did everything from cloning the repositories and building the container images, to deploying the controllers and running tests, on top of setting up the virtual machines and the networks, of course. Needless to say, it became hard to understand and easy to misuse.
