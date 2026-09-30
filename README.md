# Awesome-Data-Management-Platform

## Top Data Management Platform (DMP) Ecosystem

**Curated List of SaaS Products & Open-Source GitHub Projects**

*Focused on Audience Data, Segmentation, Cookie/ID Graphs, Ad Activation & Privacy-Safe Audience Management*

**Last updated: October 2026**



This repository tracks notable **SaaS platforms** and **open-source projects** for **Data Management Platforms (DMPs)**. Traditional DMPs collect, organize, and activate anonymous or pseudonymous audience data for advertising and marketing—often via cookies, device graphs, and second/third-party data.



**Examples** include Lotame, Permutive, Oracle BlueKai, Nielsen Marketing Cloud, Adobe Audience Manager, Salesforce Data Cloud, Treasure Data, Relay42, Commanders Act, and Zeotap (the category leaders and successors).



**Open-source emphasis**: Classic ad-tech DMPs are almost entirely commercial. The open ecosystem is stronger in adjacent **CDP**, **event collection**, and **open data portal** tooling. This section expands those realistic alternatives while noting the commercial gap for full DMP-style activation.



Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.



## Table of Contents

- [SaaS/Hosted Platforms](#saas-products)

- [Open-Source GitHub Projects](#open-source-github-projects)

- [How to Contribute](#how-to-contribute)

- [Disclaimer](#disclaimer)



## SaaS/Hosted Platforms

- **[Lotame](https://www.lotame.com/)**  

  Audience data platform for building, segmenting, and activating first-, second-, and third-party audience data.



- **[Permutive](https://permutive.com/)**  

  Publisher-focused real-time DMP/audience platform optimized for privacy-centric and cookieless environments.



- **[Oracle BlueKai](https://www.oracle.com/)**  

  Legacy Oracle DMP for audience data management and activation (historical category leader; market has shifted toward CDPs).



- **[Nielsen Marketing Cloud](https://www.nielsen.com/)**  

  Marketing and audience data capabilities within Nielsen’s measurement and advertising ecosystem.



- **[Adobe Audience Manager](https://business.adobe.com/products/audience-manager.html)**  

  Adobe’s DMP for audience segmentation and activation, integrated with the Adobe Experience Cloud.



- **[Salesforce Data Cloud](https://www.salesforce.com/data/)**  

  Salesforce’s customer data platform (CDP) that has largely superseded classic DMP use cases within the Salesforce stack.



- **[Treasure Data](https://www.treasuredata.com/)**  

  Enterprise CDP/DMP-style platform for unifying and activating customer and audience data at scale.



- **[Relay42](https://relay42.com/)**  

  Customer data and journey orchestration platform used for audience management and activation.



- **[Commanders Act](https://www.commandersact.com/)**  

  Privacy-centric data and consent platform with audience and activation capabilities for European markets.



- **[Zeotap](https://zeotap.com/)**  

  Customer intelligence and identity platform for building and activating privacy-safe audiences.



## Open-Source GitHub Projects

- **[Apache Unomi](https://github.com/apache/unomi)**  

  Open-source customer data platform reference implementation for profiles, segments, and privacy-aware customer context.



- **[PostHog](https://github.com/PostHog/posthog)**  

  Open-source product analytics and CDP-style platform for event collection, cohorts, and activation pipelines.



- **[Jitsu](https://github.com/jitsucom/jitsu)**  

  Open-source event collection and warehouse-first pipeline often used as a Segment/CDP-style alternative.



- **[Snowplow](https://github.com/snowplow/snowplow)**  

  Open-source behavioral data pipeline for collecting high-quality event data that can feed audience systems.



- **[CKAN](https://github.com/ckan/ckan)**  

  Open-source data management system for publishing and sharing datasets—useful for open data hubs rather than ad DMPs.



- **[RudderStack (source-available core)](https://github.com/rudderlabs/rudder-server)**  

  Warehouse-first customer data pipeline with broad integrations (license terms should be reviewed).



- **[Matomo / open analytics](https://github.com/matomo-org/matomo)**  

  Open-source web analytics that can support first-party audience insights without third-party DMP dependency.



- **[Consent and identity open tools](https://github.com/)**  

  Community projects for consent management and first-party identity that complement privacy-safe audience strategies.



- **[Documentation and open CDP playbooks](https://unomi.apache.org/)**  

  Guides for self-hosting profile stores and building first-party audience pipelines.



- **[Self-hosted audience stack patterns](https://github.com/)**  

  Combining event collectors (Snowplow/Jitsu) + warehouse + open segmentation for first-party activation.



### Additional Strong Open-Source Options

- Building first-party audience pipelines with **PostHog**, **Jitsu**, or **Snowplow** into a warehouse.

- Using **Apache Unomi** as a profile and segment store.

- Accepting that third-party data marketplaces, large-scale ID graphs, cookieless publisher activation, and enterprise ad-tech integrations remain commercial (Lotame, Permutive, Adobe Audience Manager, Treasure Data, Zeotap, etc.).

- Focusing open-source efforts on first-party data ownership and privacy-safe activation.



**Frameworks for building custom systems**: Collect events with Snowplow/Jitsu/PostHog → store profiles in Unomi or warehouse → segment in SQL/dbt → activate via APIs or clean rooms. Suitable for publishers and brands prioritizing first-party data. Traditional multi-party DMP use cases still rely on commercial platforms.



## How to Contribute

1. Fork the repo.

2. Add/edit entries in `README.md` (follow existing format).

3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.

4. Submit PR with a short explanation.



Star the repo if you find it useful!



## Disclaimer

- This is a **community-curated** list — not exhaustive and not an endorsement.

- Audience and advertising data are subject to privacy laws (GDPR, CCPA, etc.). Open-source tools do not replace compliant commercial DMP/CDP programs. This list is not legal or marketing advice.



---

**Made for ad-tech, publisher, and privacy-first data teams.**

Let's keep audience data useful, owned, and as open as practical.
