# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/mifisignal/argocd-example-apps
# cd into the cloned directory
git checkout 1efd3769dda38ecf95121cd3762cd7f6fdd5d4f0
helm template . --name-template development-helm-guestbook --namespace development --include-crds
```
