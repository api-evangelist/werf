---
title: "Server-Side Apply instead of 3-Way Merge: How werf 2.0 solves Helm 3 challenges"
url: "https://blog.werf.io/ssa-vs-3wm-in-helm-werf-nelm-4d7996354ebe?source=rss----c71afb15ed00---4"
date: "2024-07-25"
author: "Flant staff"
feed_url: "https://blog.werf.io/feed"
---
In werf 1.2, a mechanism called 3-Way Merge (3WM) was used for updating Kubernetes resources. It was inherited from Helm 3 since we used its fork in werf. While 3-Way Merge solved some of the 2 -Way Merge issues, many of the challenges that caused incorrect resource updates remained unaddressed.
