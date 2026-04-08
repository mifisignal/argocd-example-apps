# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/mifisignal/argocd-example-apps
# cd into the cloned directory
git checkout 20b27f28d05afb520f5f0ff70ba5d038127a3e81
helm template . --name-template staging-helm-guestbook --namespace staging --include-crds
```
