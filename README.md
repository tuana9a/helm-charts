# helm-charts

tuana9a's helm chart collection - "*Just another helm chart repository*"

## Usage

[Helm](https://helm.sh) must be installed to use the charts.  Please refer to
Helm's [documentation](https://helm.sh/docs) to get started.

Once Helm has been set up correctly, add the repo as follows:

```bash
helm repo add tuana9a https://tuana9a.github.io/helm-charts
```

If you had already added this repo earlier, run `helm repo update` to retrieve
the latest versions of the packages.  You can then run `helm search repo
tuana9a` to see the charts.

To install the <chart-name> chart:

```bash
helm install <chart-name> tuana9a/<chart-name>
```

To uninstall the chart:

```bash
helm uninstall <chart-name>
```
