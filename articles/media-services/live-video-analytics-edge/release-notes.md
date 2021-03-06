---
title: Live Video Analytics on IoT Edge release notes - Azure
description: This topic provides release notes of Live Video Analytics on IoT Edge releases, improvements, bug fixes, and known issues.
ms.topic: conceptual
ms.date: 04/27/2020

---
# Live Video Analytics on IoT Edge release notes

>Get notified about when to revisit this page for updates by copying and pasting this URL: `https://docs.microsoft.com/api/search/rss?search=%22Live+Video+Analytics+on+IoT+Edge+release+notes%22&locale=en-us` into your RSS feed reader.

This article provides you with information about:

* The latest releases
* Known issues
* Bug fixes
* Deprecated functionality

## July 13, 2020

This release tag for the July 2020 refresh of the module is:

```
     mcr.microsoft.com/media/live-video-analytics:1.0.2
```

> [!NOTE]
> In the quickstarts and tutorials, the deployment manifests use a tag of 1 (live-video-analytics:1). So simply redeploying such manifests should update the module on your edge > devices.

### New features
* You can now create graph topologies that have an asset sink node as well as a file sink node downstream of a signal gate processor node. See [this](https://github.com/Azure/live-video-analytics/tree/master/MediaGraph/topologies/evr-motion-assets-files) for an example.

### Bug fixes
* Improvements to validation of desired properties

## June 1, 2020

This release is the first public preview release of Live Video Analytics on IoT Edge. The release tag is

```
     mcr.microsoft.com/media/live-video-analytics:1.0.0
```

### Supported functionalities
* Analyze live video streams using AI modules of your choice and optionally record video on the edge device or in the cloud
* Use on Linux AMD64 operating systems [supported](../../iot-edge/support.md) by IoT Edge
* Deploy and configure the module via the IoT Hub using Azure portal or Visual Studio Code
* Manage [graph topologies and graph instances](media-graph-concept.md#media-graph-topologies-and-instances) remotely or locally through the following direct method calls

    *	GraphTopologyGet
    *	GraphTopologySet
    *	GraphTopologyDelete
    *	GraphTopologyList
    *	GraphInstanceGet
    *	GraphInstanceSet
    *	GraphInstanceDelete
    *	GraphInstanceList


## Next steps

[Overview](overview.md)
