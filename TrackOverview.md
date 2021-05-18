# FutureHack Track Overview

## The Low Code, No Code

The _Low Code, No Code_ track is perfect for business analysts, techops pros, and spreadsheet wizards who want to use New Relic to understand their business metrics better.

**The challenge:** Build your most impactful New Relic Dashboard. Share your dashboard, the NRQL queries, APIs, and instrumentations you used to create it, and how it helps you better understand your system or service.

## Build on New Relic

The _Build on New Relic track_ is perfect for skilled Data Nerds and New Relic practitioners who are ready to push their organization’s dashboards beyond all limits.

**The challenge:** Use the New Relic One SDK to build a custom visualization and add it to a dashboard. Share how you'd use it, along with other widgets in your dashboard, and how it would benefit your users.

## Hack for Good

The _Hack for Good_ track is perfect for every coder, developer, or engineer that wants to hack with minor restrictions and make a difference.

**The challenge:** Build a kick-ass project for the good of other developers, your local or personal community, or the world. Choose your cause. Choose your tech stack. And deliver the most innovative project you can. Then, explain how your project impacts those people. (Bonus points will be awarded for New Relic instrumentation and dashboards.)

## Student Challenge

The _Student Challenge_ track is for students to learn about New Relic in a real-world environment and take their first step into the world of software Observability.

**The workshop:** Attend the _Error in Prod_ workshop, where you'll become the lead SRE for the hottest, techiest store—Urban Nerdfitters. In the workshop, you'll get a guided walkthrough of New Relic One and get hands-on to help us better understand our system.

**The challenge:** Help us solve the issue with our Urban Nerdfitters production environment. The first student to complete all the challenges wins this part of the challenge. Based on what you’ve learned, develop your most impactful Urban Nerdfitters New Relic Dashboard. Share a walkthrough with the details and impact of your dashboard. Explain the NRQL queries you used to create it and how it helps you better understand your system.

## Reli Hack

The _Reli Hack_ track is for internal Relics only. The focus of this track is to build contributions for the New Relic ecosystem and expanding our customer value.

**The challenge:** Create a new custom visualization, observability pack, or new entity type contribution to New Relic open source. Provide documentation about your contribution explaining the technology, getting started criteria, and the value a customer gains by deploying their contribution into their New Relic account.

More info can be found below on how to get started.

### Custom Visualizations
**What?**
A custom visualization is a visualization built outside of New Relic that you can import and use on the NR1 platform. This leverages the ability for you to build your own visualization and be able to query not only New Relic data but data outside of New Relic too!  

**Why contribute?**
Today there is a gap between the visualizations that are offered in New Relic and how customers want to see their data. By contributing, you can help us improve the visualizations that we offer to our customer and allow the a more robust ecosystem of options to get them up and going quicker!

**How to get started?**
[Getting Started with Custom Visualizations](https://docs.google.com/document/d/1sh_yctUnhMHIVFqSVM_QD-0aqIwS99g-8TYqA-UIcjM/edit?usp=sharing).  
 
### Entity Types
**What?**
* Entity type definitions are a mapping between the telemetry ingested to New Relic and the entities (objects) that users can interact with in New Relic UI. If you have telemetry from any source that is not supported out of the box in New Relic, you can propose a mapping to light up the New Relic experience.  

**Why contribute?**
* Entities power the experiences in New Relic by grouping all telemetry data under a familiar object such as a container, a MySQL node or an Open Telemetry service. Once a new entity type is defined; all telemetry data corresponding to the rule will get powerfull observability tools such as [Navigator](https://newrelic.com/blog/nerdlog/new-relic-explorer-simple-intuitive-observability), [Lookout](https://newrelic.com/blog/nerdlog/new-relic-explorer-simple-intuitive-observability) or [Workloads](https://docs.newrelic.com/docs/new-relic-one/use-new-relic-one/workloads/workloads-isolate-resolve-incidents-faster/).  
 
**How to get started?**
* Create your first entity type by following the [definitions guidelines](https://github.com/newrelic-experimental/entity-synthesis-definitions#guidelines).
 
**Looking for inspiration?** 
* Add the [Prometheus node exporter](https://github.com/prometheus/node_exporter) definition to get an out of the box experience for servers and VMs. 
* Define the entity type for your favorite [Flex integration](https://github.com/newrelic/nri-flex/tree/master/examples)
* Create the [Hashicorp Vault](https://www.vaultproject.io/) entity type. You can collect (Vault telemetry](https://www.vaultproject.io/docs/internals/telemetry) through [New Relic Prometheus integrations](https://docs.newrelic.com/docs/integrations/prometheus-integrations/get-started/send-prometheus-metric-data-new-relic/). 

### Observability Pack
**What?** 
* An observability pack contains the observability needs for a specific technology or use case in 1 package. This currently includes dashboards, alerts and instrumentation dependencies.

**Why contribute?**
* Observability Packs provide a high-quality out-of-the-box experience to New Relic users who are looking to monitor their stack
* It will soon be possible to discover these observability packs inside New Relic One and the goal is to launch with a high-quality set of initial packs

**How to get started?** 
* Create your first observability pack by following the [Getting Started guide](https://github.com/newrelic/newrelic-observability-packs)

**Looking for inspiration?**
* Extend the basic dashboard of a New Relic [on-host integrations](https://docs.newrelic.com/docs/integrations/host-integrations/host-integrations-list/) and add alerts
* Build an observability pack for a more complex technology stack (such as a LAMP, MEAN, .NET or JAVA stack)
* Create a dashboard and alerts for one of the [New Relic Flex examples](https://github.com/newrelic/nri-flex/tree/master/examples)
