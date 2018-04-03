# Helm-Plugins
Helm plugins to scale a helm release

       Accepts two parameters :  helm release name and replica count and scales.


$ helm scale
Scale Helm Chart Release
Lets you scale the helm release given the replica count.

  scale   scales the replicas set,statefulsets,deployments and job scalars
Available options:
  -help   look for usage
  -r      helm release name
  -rp     replicacount
Example:
  helm scale -r helm-release-name -rp repliacount

Do Helm list to get the release name
$ helm scale -r wandering-bunny -rp 5
helm scale -r wandering-bunny -rp 5
its a valid helm release name
no depoyment found in the release to scale
statefulset "wandering-bunny-cmdb" scaled


