
# How to generate all CNI binaries if Needed

In case you have to build CNI binary please use following steps:

```bash
cd /root/q-k8s/mac-kind
git clone https://github.com/containernetworking/plugins.git
cd plugins
# this will build the CNI binaries in bin/*
./build_linux.sh
```