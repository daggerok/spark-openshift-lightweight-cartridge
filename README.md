spark-openshift-lightweight-cartridge
=====================================

Runs [Spark Framework](http://sparkjava.com/) on [OpenShift](https://www.openshift.com/) using downloadable cartridge support. To install to OpenShift from the CLI, run:

```fish
rhc app create daggerok diy --from-code=https://github.com/daggerok/spark-openshift-lightweight-cartridge.git
```

For deploy new app on server, just put new `server.jar` into root directory and push it.

Java version 1.8.0_92.
