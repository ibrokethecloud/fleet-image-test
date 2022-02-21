# Sample of using fleet-image-scan

A sample app using fleet image scan to update and release new versions of an app using the semver matching of tags on container images.

The gitrepo-cr directory contains the sample GitRepo definition. The repo uses ssh keys for authenticating against the repo, and creating subsequent commits. 

The image-scan-example directory contains the sample manifests rolled by the GitRepo CR.
