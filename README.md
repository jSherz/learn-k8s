# learn-k8s

This is a repo of Kubernetes experiments that are definitely not production
ready!

## minecraft

I wanted to try out StatefulSets and see how easy it is to have a long-lived
volume backing a game server like Minecraft. The initial world backup is
downloaded and extracted when the pod/volume are first created. On subsequent
runs, the volume is used as-is.
