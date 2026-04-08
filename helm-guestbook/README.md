# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/mifisignal/argocd-example-apps
# cd into the cloned directory
git checkout 7fcffba0f2138ff64a0c0141c5f7bb2a4b7c4290
helm template . --name-template development-helm-guestbook --namespace development --include-crds
```
