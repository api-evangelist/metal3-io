---
title: "Deploying OCI Container Images to Bare Metal with a Custom IPA Hardware Manager"
url: "https://metal3.io/blog/2026/02/01/Deploying_OCI_Images_with_Custom_IPA_Hardware_Manager.html"
date: "2026-02-01"
author: "Serhii Ivanov"
feed_url: "https://metal3.io/feed.xml"
---
What if you could deploy any OCI container image directly to bare metal, without building traditional disk images? Back in 2021, Dmitry Tantsur implemented custom deploy steps for Ironic, enabling alternative deployment methods beyond the standard image-based approach. This feature powers OpenShift’s bare metal provisioning with CoreOS, yet it remains surprisingly unknown to the broader Metal3 community. This post aims to change that by providing an example implementation of a custom IPA hardware manager that deploys Debian-based container images with EFI boot, LVM root filesystem, and optional RAID1 mirroring.
