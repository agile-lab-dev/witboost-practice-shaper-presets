# Business Intelligence Preset

## Overview

The **Business Intelligence (BI) data landscape** encompasses the ecosystem of data and tools used to analyze and visualize business data to support decision-making.
## Installation Guide

From the Practice Shaper settings page, register the following entities in order.
Refer to the [witboost documentation](https://docs.witboost.agilelab.it) to learn how to register a Practice Shaper entity in the **witboost catalog**.

| Name                                                       | Kind            | Description                                                                                                                                                                                                                                                                  |
| ---------------------------------------------------------- | --------------- | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| [Business Domain](../../domain-types/business-domain.yaml) | `DomainType`    | A business domain refers to a distinct area of expertise or activity within an organization, encompassing a specific set of business processes, rules, and knowledge. It represents a particular aspect of the business, focusing on specific goals, functions, and outcomes |
| [Business Intelligence](./catalog-info.yaml)               | `Taxonomy`      | Entity representing the Business Intelligence data landscape                                                                                                                                                                                                                 |
| [BI Project](./system-types/biproject.yaml)                | `SystemType`    | Structured initiative aimed at leveraging data analytics and reporting tools to gather, process, analyze, and visualize data for the purpose of making informed business decisions                                                                                           |
| [Consumer View](./component-types/consumerview.yaml)       | `ComponentType` | View through which end-users or stakeholders perceive and interact with insights, reports, and data-driven information provided by BI systems                                                                                                                                |
| [Dashboard](./component-types/dashboard.yaml)              | `ComponentType` | Visual representation of key performance indicators (KPIs), metrics, and data points that provide an overview of an organization's performance and help stakeholders make informed decisions                                                                                 |


