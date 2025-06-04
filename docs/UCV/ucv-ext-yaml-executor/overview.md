
# YAML Executor - Overview

The YAML Executor plug-in is automatically installed and configured without manual configuration. You can apply the YAML file under **Settings>External Config Pipeline** to initiate the YAML Executor plug-in integration process.


## Compatability

This plug-in requires DevOps Velocity version 4.0.12 and later.

## Versions

DevOps Velocity plug-in images are located in DockerHub. To
view available versions, see the [UrbanCode DockerHub](https://hub.docker.com/r/urbancode/ucv-ext-yaml-executor/tags).


## History

### Version 0.0.11

* **Feature enhancement**: Added a new parameter, appEnvOrder, within the attributes section of the configuration. This parameter enables users to explicitly specify the sequence in which environments are created, ensuring that the environment creation process adheres to the defined order.

### Version 0.0.8

* **Improvisation** : Plug-in synchronization has been optimized to align with scheduled events, with particular emphasis on the end time. Additionally, failure scenarios related to pipeline creation and value stream processing have been resolved.

### Version 0.0.6

* Started using timeSpan for Initial Sync date.

### Version 0.0.5

* Initial release

|Back to ...||Latest Version|YAML Executor |||
| :---: | :---: | :---: | :---: | :---: | :---: |
|[All Plugins](../../index.md)|[Velocity Plugins](../README.md)|[0.0.11-File 1 ](https://raw.githubusercontent.com/UrbanCode/IBM-UCV-PLUGINS/main/files/ucv-ext-yaml-executor/ucv-ext-yaml-executor%3A0.0.11.tar.7z.001)[and 0.0.11-File 2](https://raw.githubusercontent.com/UrbanCode/IBM-UCV-PLUGINS/main/files/ucv-ext-yaml-executor/ucv-ext-yaml-executor%3A0.0.11.tar.7z.002)|[Readme](README.md)|[Steps](steps.md)|[Downloads](downloads.md)|
