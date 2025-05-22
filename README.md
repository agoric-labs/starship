## Usage

[Helm](https://helm.sh) must be installed to use the charts.  Please refer to
Helm's [documentation](https://helm.sh/docs) to get started.

Once Helm has been set up correctly, add the repo as follows:

  helm repo add starship https://agoric-labs.github.io/starship

If you had already added this repo earlier, run `helm repo update` to retrieve
the latest versions of the packages.  You can then run `helm search repo
starship` to see the charts.

To install the devnet chart:

    helm install my-devnet starship/devnet

To uninstall the chart:

    helm uninstall my-devnet
