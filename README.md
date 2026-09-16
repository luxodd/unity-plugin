# Luxodd Unity Plugin

The Luxodd Unity Plugin provides integration for Unity WebGL arcade games with the Luxodd platform.

## Requirements

- Unity 2022 LTS or newer
- WebGL Build Support
- Unity 6+ is supported

## Installation

1. Download the `.unitypackage` from the [`Plugin/`](./Plugin/) directory.
2. In Unity, select **Assets > Import Package > Custom Package**.
3. Select the downloaded package and import it.
4. Follow the [official installation guide](https://docs.luxodd.com/docs/arcade-launch/unity-plugin/installation).

Before upgrading, back up any customized `Assets/WebGLTemplates/LuxoddTemplate` files so they can be reviewed or merged after import.

## Documentation

See the [official Luxodd Unity Plugin documentation](https://docs.luxodd.com/docs/category/unity-plugin) for setup, configuration, testing, and API reference information.

## Package

Release packages are stored under [`Plugin/`](./Plugin/).

Example:

`Plugin/LuxoddGamePlugin_v_1.2.0.unitypackage`

## Supported Platforms

WebGL arcade games are the primary target. The included WebGL template and browser integration are intended for Unity WebGL builds.
