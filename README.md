# fiserv-accelerator

## Need a new namespace in your cluster?
Click [here](https://github.com/cdelashmutt-pivotal/gbs-gitops/new/main?filename=config/new-namespace.yaml&message=New%20Developer%20Namespace&value=apiVersion%3A%20v1%0Akind%3A%20Namespace%0Ametadata%3A%0A%20%20labels%3A%0A%20%20%20%20apps.tanzu.vmware.com%2Ftap-ns%3A%20%27%27%0A%20%20name%3A%20new-namespace) to add a new namespace for development.

## Getting access to environment
Click [here](https://fiservesf.tmc.cloud.vmware.com/clusters) to download your kube.config file for enabling access to the development environment.

## Register your app with the TAP Catalog
Copy the URL to your [catalog/catalog-info.yaml](catalog/catalog-info.yaml), and paste the URL into the page at https://tap-gui.tap.nvcodes.net/catalog-import