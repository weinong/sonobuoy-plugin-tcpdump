## A sonobuoy plugin to capture tcpdump on kubernetes nodes

### How to run
```sh
sonobuoy run -p tcpdump.yaml
results=$(sonobuoy retrieve)
mkdir -p results && tar -xf $results -C results
```

### Cleanup
```sh
sonobuoy delete --wait
```
