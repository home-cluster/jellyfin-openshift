# Jellyfin on OpenShift

This project contains the required resources to deploy Jellyfin into
OpenShift.

## Kubernetes resources

The `deploy/` directory contains some `PersistentVolumeClaim`s , a `Deployment`, `Service`, and `Route` to deploy Jellyfin
into OpenShift. For Kubernetes, everything except the `Route` should work. You will likely need to edit the 
`PersistentVolumeClaim`s to fit your environment.
