# Luxodd Unity Plugin

The Luxodd Unity Plugin integrates Unity WebGL games with the Luxodd arcade platform. The current release target is **1.2.0**.

## Requirements

- Unity 2022 LTS or newer, including Unity 6+, with WebGL Build Support.
- UGUI (`com.unity.ugui`), TextMeshPro (`com.unity.textmeshpro`) and Newtonsoft JSON (`com.unity.nuget.newtonsoft-json`).
- Unity Input System (`com.unity.inputsystem`) is optional.

## Install

1. Download the package from [GitHub Releases](https://github.com/luxodd/unity-plugin/releases).
2. In Unity, select **Assets > Import Package > Custom Package**, and import the package.
3. If needed, select **Window > TextMeshPro > Import TMP Essential Resources**.
4. Select `LuxoddTemplate` in WebGL Player Settings. Follow the [setup guide](https://docs.luxodd.com/unity/setup/) for configuration and upgrades.

Back up your project and customized `Assets/WebGLTemplates/LuxoddTemplate` before upgrading. For upgrades from before 1.1.0, remove the old `Assets/Luxodd.Game` before importing to avoid stale files. Merge or replace the template carefully, allow compilation to finish, and check scenes and prefabs for missing scripts.

## Version 1.2.0

The SDK includes WebSocket session and score reporting, Fast Restart and Continue support, runtime context and viewport helpers, arcade controls, score-centered leaderboard queries and Merchant Prize integration. Basic WebGL testing covered initial session acceptance, connection, level begin, score update, Profile and Balance on Unity 2021.3.45f2. Other flows require further end-to-end validation; cross-scene persistence is not guaranteed.

See the [release overview](https://docs.luxodd.com/unity/release-1-2-0/), [integration guide](https://docs.luxodd.com/unity/integrate/), [API reference](https://docs.luxodd.com/unity/api-reference/) and [testing guide](https://docs.luxodd.com/unity/test/).
