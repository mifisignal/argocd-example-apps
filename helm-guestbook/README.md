# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/mifisignal/argocd-example-apps
# cd into the cloned directory
git checkout 4ff4592e220d679d061495042951548acefb29b6
helm template . --name-template staging-helm-guestbook --namespace staging --include-crds
```
