Download the [latest binary release](https://github.com/kubernetes/kubernetes/releases/latest) and unzip it. 
Server binary tarballs are no longer included in the Kubernetes final tarball, so you will need to locate and run ./kubernetes/cluster/get-kube-binaries.sh to download the client and server binaries. 
Then locate `./kubernetes/server/kubernetes-server-linux-amd64.tar.gz` and unzip that. 
Then, within the second set of unzipped files, locate `./kubernetes/server/bin`, which contains all the necessary binaries.