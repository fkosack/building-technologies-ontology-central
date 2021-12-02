# Building Technologies - Ontology Central

Ontology central the open source building technologies **ontology model repository** for **commercial buildings**.

## Overview

Welcome to ontology central - the DTDL open source ontology repository for commercial buildings!

The repository contains ontology models for commercial buildings. Models are organized in a folder structure of the owner organizations, a organization use their reversed Internet domain name for the folder name e.g. `com.bosch`. For example, the models from Bosch Building Technologies can be found in the folder `com/bosch/bt`. The folder structure for each model is `{model-name}/{version}`. Each model consists of a set of *Azure Digital Twins models* (see <http://aka.ms/ADTv2Models>) and a `MANIFEST.json` file. The manifest file (`MANIFEST.json`) describes the name and dependencies to other ontology models.

## Repository Content

> The ontology models (version 2.0) in this repository are currently being updated to stay in sync with the recent ("groundbreaking") implementation of the first consuming services. All changes to the models are described by tickets. Any change to the existing models is made by a pull request. See also [CONTRIBUTING.md](./CONTRIBUTING.md).

The repository contains the following ontology models:

Ontology | Version | Description
:-- | :-- | :--
:notebook: [**Foundation Ontology**](./com/bosch/bt/Foundation/2.0.0) | **2.0** | Ontology model defines common concepts like the space topology structure, assets, data points, etc.
:notebook: [**Fire Alarm Systems Ontology**](./com/bosch/bt/fire-alarm-systems/2.0.0) | **2.0** | Ontology model to describe a fire alarm system, consisting of panels, modules, detectors, etc.
:notebook: [**HVAC Systems Ontology**](./com/bosch/bt/hvac-systems/2.0.0) | **2.0** | Ontology model for HVAC systems to describe entities like AHU, VAV, chiller, etc.

## Usage

To use the models an Azure Digital Twins (ADT) instance is needed. The models can be deployed with the ADT explorer (see [quickstart azure digital twins explorer](https://docs.microsoft.com/azure/digital-twins/quickstart-azure-digital-twins-explorer)) and in the samples folders of the models you can find some demos (see [Foundation Samples](./com/bosch/bt/Foundation/2.0.0/samples/README.md)).

## Contribute

Please refer to the [CONTRIBUTING.md](./CONTRIBUTING.md) for a quick read-up about what to consider if you want to contribute.

## Contributors

Contact details of the **authors** and **contributors** see [NOTICE](NOTICE).

## License

Building Technologies - Ontology Central is open-sourced under the `Apache-2.0` license. See the [LICENSE](./LICENSE) and [NOTICE](./NOTICE) file for details.
