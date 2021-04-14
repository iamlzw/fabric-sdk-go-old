# Hyperledger Fabric Client SDK for Go

when I use fabric-sdk-go to develope,I meet some error which cause by fabric-protos-go,so I replace fabric-protos-go with fabric/protos

# how to use 

clone 
```
git clone https://
```

modify go.mod

```
# add this content on your go.mod
replace github.com/hyperledger/fabric-sdk-go vx.x.x => ../the path of fabric-sdk-go registry

```
