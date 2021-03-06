---
title: DOPI
description: Pattern Detector code help page
---

# DOPI {#dopi}

Deprecated Ordered Property Index

## Background {#background}

`DOPI` identifies the use of ordered property index definitions (`primaryType=oak:QueryIndexDefinition` AND `type="ordered"`), which have been deprecated since 6.1 and were removed in 6.2.

## Possible implications and risks {#implications-and-risks}

* Some queries may not respond.
* Customer functionality might work incorrectly.
* Traversal warnings or even errors and significant performance penalties as the deprecated indexes have no effect.

## Possible solutions {#solutions}

* Modify the index definition to become, or replace the index with, a supported index definition. (See [Oak Queries and Indexing](https://docs.adobe.com/content/help/en/experience-manager-65/deploying/deploying/queries-and-indexing.html)).
* Please reach out to our [AEM Support Team](https://helpx.adobe.com/enterprise/using/support-for-experience-cloud.html) to get clarifications or to address concerns.
