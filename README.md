[![Lifecycle:Stable](https://img.shields.io/badge/Lifecycle-Stable-97ca00)](https://github.com/bcgov/repomountie/blob/master/doc/lifecycle-badges.md)
# DTS Backup Configurations

OpenShift templates for non app-specific [backup-container](https://github.com/BCDevOps/backup-container) instances used by the DTS Team.

The configurations are organized by app namespace: each folder in the root of the repository represents a namespace containing a set of backup-container configurations that are shared across multiple apps in that namespace.

The templates use the [openshift-developer-tools](https://github.com/BCDevOps/openshift-developer-tools): to build/deploy an instance, open a shell in the `openshift` folder for the group you want to process and execute the appropriate commands.
