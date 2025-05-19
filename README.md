# k8id-config

## Kube Prometheus Mixins

You can enable/disable any support mixins from your cluster jsonnet file (k8id-config).
You will to run the build script manually to update the yaml file

```sh
./build/kube-prometheus/build.sh /path/to/k8id-config/k8s/<cluster-name>
```

Now you can do the git add/commit/push and sync it the kube-prometheus app on argocd
Remember to select "Prune" in argocd when you are deleting any mixins
