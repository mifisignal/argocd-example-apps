# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/mifisignal/argocd-example-apps
# cd into the cloned directory
git checkout 5f447ee2995c2287a1c3d67fe338e43dbfc1972e
helm template . --name-template prod-helm-guestbook --namespace prod --include-crds
```
