# ytt-k8s-registry
ytt templates for a Docker registry

#### Deploy

1. copy or adjust `sample-values.yml` # see templates/values.yml for reference
2. `ytt -f templates -f sample-values.yml | kapp deploy -a registry --diff-changes -f - -y`
