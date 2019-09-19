## A sonobuoy plugin to capture tcpdump on kubernetes nodes

## How to run
```
sonobuoy run -p tcpdump.yaml
results=$(sonobuoy retrieve)
mkdir -p results && tar -xf $results -C results
```
