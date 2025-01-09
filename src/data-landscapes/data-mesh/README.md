# Data Mesh Preset

## Overview

The **Data Mesh** is a decentralized approach to data architecture that emphasizes domain-oriented ownership, self-serve data infrastructure, and treating data as a product. It shifts the responsibility for data management and governance from a centralized data team to the various business domains that generate and use the data.

If you want to delve deeper into the Data Mesh, check the [AgileLab blog](https://www.agilelab.it/blog/tag/data-mesh).

## Installation Guide

From the Practice Shaper settings page, register the following entities in order.
Refer to the [Witboost documentation](https://docs.witboost.com) to learn how to register a Practice Shaper entity in the **Witboost catalog**.

| Name                                                       | Kind            | Description                                                                                                                                                                                                                                                                  |
| ---------------------------------------------------------- | --------------- | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| [Business Domain](../../domain-types/business-domain.yaml) | `DomainType`    | A business domain refers to a distinct area of expertise or activity within an organization, encompassing a specific set of business processes, rules, and knowledge. It represents a particular aspect of the business, focusing on specific goals, functions, and outcomes |
| [Data Mesh](./catalog-info.yaml)                           | `Taxonomy`      | Entity representing the Data Mesh data landscape                                                                                                                                                                                                                             |
| [Data Product](./system-types/data-product.yaml)           | `SystemType`    | A data product is a set of data and related assets that are designed, developed, and managed to provide specific value to its users. It is treated as a product with its own lifecycle, from inception and development to deployment and maintenance                         |
| [Storage](./component-types/storage.yaml)                  | `ComponentType` | Infrastructure used to store and manage the data that forms the foundation of data products within an organization                                                                                                                                                           |
| [Output Port](./component-types/outputport.yaml)           | `ComponentType` | Interface through which the data from a data product is delivered to users, applications, or other systems                                                                                                                                                                   |
| [Workload](./component-types/workload.yaml)                | `ComponentType` | Operational task involved in creating, ingesting, managing, or utilizing data of data products within an organization                                                                                                                                                        |

If you desire to register the whole Data Landscape using a single file, you can register the `data-mesh-landscape.yaml` via the Witboost Catalog API, or by adding it as part of a first installation to the Location Register Startup Action. Refer to the [Witboost documentation](https://docs.witboost.com) for more information.