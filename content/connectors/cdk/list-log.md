---
title: List & Logs
weight: 60
---
##### Prerequisites

This section assumes that CDK is [installed]({{< ref "install" >}}) and `my-connector` project has been [generated]({{< ref "generate" >}}).

After you [start your connectors]({{<ref "/connectors/cdk/start-shutdown#connector-start">}}), you can review the list of all connectors, and view their logs with these commands

### List

%copy first-line%
```bash
$ cdk deploy list                              
 NAME                            STATUS  
 my-my-connector-test-connector  Running
```

### Log

%copy first-line%
```bash
$ cdk deploy log my-my-connector-test-connector
Starting my-connector source connector with CustomConfig { foo: "bar" }
```

1. [Install CDK]({{< ref "install" >}})
2. [Generate a SmartConnector]({{< ref "generate" >}})
3. [Build and Test]({{< ref "build-test" >}})
4. [Start and Shutdown]({{< ref "start-shutdown" >}})
5. **[List and Logs]({{< ref "list-log" >}})**
6. [Publish to SmartConnector Hub]({{< ref "publish" >}})