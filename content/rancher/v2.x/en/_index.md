---
title: "Pre-Versioned Docs from 2.0-2.5.6 (Formerly 2.x)"
shortTitle: "Rancher 2.5-2.5.6"
description: "Rancher adds significant value on top of Kubernetes: managing hundreds of clusters from one interface, centralizing RBAC, enabling monitoring and alerting. Read more."
metaTitle: "Rancher 2.x Docs: What is New?"
metaDescription: "Rancher 2 adds significant value on top of Kubernetes: managing hundreds of clusters from one interface, centralizing RBAC, enabling monitoring and alerting. Read more."
insertOneSix: false
weight: 2
ctaBanner: 0
---

> We are transitioning to versioned documentation. The Rancher v2.5 docs are [here.]({{<baseurl>}}/rancher/v2.5/en/) The Rancher v2.0-v2.4 docs are [here.]({{<baseurl>}}/rancher/v2.0-v2.4/en/) We recommend using the versioned docs because they are easier to read and navigate.
>
> This section, also called 2.x, contains information for versions v2.0-2.5.6. This section is still on the Rancher website so that search results won't return 404 errors, but it will no longer be maintained.

Rancher was originally built to work with multiple orchestrators, and it included its own orchestrator called Cattle. With the rise of Kubernetes in the marketplace, Rancher 2.x exclusively deploys and manages Kubernetes clusters running anywhere, on any provider.

Rancher can provision Kubernetes from a hosted provider, provision compute nodes and then install Kubernetes onto them, or import existing Kubernetes clusters running anywhere.

One Rancher server installation can manage thousands of Kubernetes clusters and thousands of nodes from the same user interface.

Rancher adds significant value on top of Kubernetes, first by centralizing authentication and role-based access control (RBAC) for all of the clusters, giving global admins the ability to control cluster access from one location.

It then enables detailed monitoring and alerting for clusters and their resources, ships logs to external providers, and integrates directly with Helm via the Application Catalog. If you have an external CI/CD system, you can plug it into Rancher, but if you don't, Rancher even includes [Fleet](http://fleet.rancher.io/) to help you automatically deploy and upgrade workloads.

Rancher is a _complete_ container management platform for Kubernetes, giving you the tools to successfully run Kubernetes anywhere.