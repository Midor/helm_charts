## Usage

[Helm](https://helm.sh) must be installed to use the charts.  Please refer to
Helm's [documentation](https://helm.sh/docs) to get started.

Once Helm has been set up correctly, add the repo as follows:

  helm repo add midor https://midor.github.io/helm-charts/

If you had already added this repo earlier, run `helm repo update` to retrieve
the latest versions of the packages.  You can then run `helm search repo
midor` to see the charts.

To install the cert-manager-webhook-inwx chart:

    helm install cert-manager-webhook-inwx midor/cert-manager-webhook-inwx

To uninstall the chart:

    helm uninstall cert-manager-webhook-inwx
