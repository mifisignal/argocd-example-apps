# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/mifisignal/argocd-example-apps
# cd into the cloned directory
git checkout 16f8519fa99cc00f2098497ac6637907c317afc8
helm template . --name-template staging-helm-guestbook --namespace staging --include-crds
```
