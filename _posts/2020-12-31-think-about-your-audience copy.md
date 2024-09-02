---
layout: post
title:  "blog 3: The Audience"
date:   2021-01-01
categories: outreachy
---

----
{: data-content=" who Fedorans are "}

The Fedora Project is an independent project to co-ordinate the development of [Fedora Linux](https://getfedora.org), a Linux kernel-based operating system.
Fedora is built and maintained by a community of Open-source enthusiasts who are inclusive, welcoming, and open-minded. If you want to create a world where everyone benefits from free and open-source software then you'll fit right in with the Fedora project.

----
{: data-content=" the problem & the solution "}

The fedora docs site receives a lot of contributions from open-source enthusiasts around the globe. These contributions need to be reviewed by some members of the community before being merged. Due to the size of the docs site, the process of building the Antora docs site in the local development environment can be tedious. The goal of the internship is to solve this problem by creating an automated build preview environment in Openshift, that automatically runs when pull requests are opened against the repo responsible for building the website.

We're am working on enabling CI/CD for the Fedora documentation [website](docs.fedoraproject.org). This can be accomplished in more than one way. We've decided to go with using the Jenkins automation server to build and deploy the application. The principal technology used in this project is [Openshift](https://www.openshift.com). Openshift is built around Docker containers orchestrated and managed by Kubernetes on a foundation of Red Hat Enterprise Linux. So one should at least have a fair bit of knowledge about Containers and Kubernetes to be successful in the task.

----
{: data-content=" how it's going... "}

Working on this project is both challenging and exciting. DevOps is *uncharted waters* for me and I am happy to add this to my software development skillset. While I did have some basic knowledge about the technologies and platforms used for this project, I have learned in-depth and still learning about Openshift, containers, Kubernetes and Jenkins.

Bis Später!

---------------------------------------
{% include share-buttons.html %}