# Machine Learning Preset

## Overview

The **Machine Learning data landscape** encompasses the ecosystem of data-related components and processes that facilitate the development, training, deployment, and maintenance of machine learning models.
## Installation Guide

From the Practice Shaper settings page, register the following entities in order.
Refer to the [witboost documentation](https://docs.witboost.agilelab.it) to learn how to register a Practice Shaper entity in the **witboost catalog**.

| Name                                                       | Kind            | Description                                                                                                                                                                           |
| ---------------------------------------------------------- | --------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| [Department](../../domain-types/department.yaml)           | `DomainType`    | A department refers to a distinct functional unit within an organization, typically organized based on specific functions or activities (e.g., Data Science department)               |
| [Machine Learning](./catalog-info.yaml)                    | `Taxonomy`      | Entity representing the Machine Learning data landscape                                                                                                                               |
| [ML Sandbox](./system-types/mlsandbox.yaml)                | `SystemType`    | Isolated environment where data scientists and machine learning engineers can experiment, develop, and test machine learning models without affecting live systems or production data |
| [Internal Storage](./component-types/internalstorage.yaml) | `ComponentType` | Storage infrastructure dedicated to storing data, models, configurations, and other resources used within a sandbox                                                                   |
| [Data Preparation](./component-types/datapreparation.yaml) | `ComponentType` | Computational process responsible of cleaning, transforming, and organizing raw data to ensure it is suitable for analysis or use in a ML project                                     |
| [Notebook](./component-types/notebook.yaml)                | `ComponentType` | Interactive computational environment that allows users, typically data scientists or machine learning engineers, to write, run, and iterate on machine learning code and analyses    |

