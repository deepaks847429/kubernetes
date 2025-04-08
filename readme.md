# command of kubernetes(Kind)
- kind create cluster --name <name>
- kind delete cluster -n <name>


# kubectl commands
- kubectl get nodes
- kubectl get pods
-  kubectl run nginx --image=nginx --port=80
- kubectl describe pod nginx
- kubectl logs mongo-pod
- kubectl delete pod mongo
- kubectl delete pod nginx
- kubectl apply -f rs.yml
- kubectl run nginx-pod --image=nginx --labels="app=nginx"
-  kubectl delete rs nginx-deployment-576c6b7b6
- kubectl get rs
- kubectl get pods
-  kubectl rollout history deployment/nginx-deployment(History of deployment)
- kubectl rollout undo deployment/nginx-deployment(undo the last deployment)
- kubectl get pods -owide
-----BEGIN RSA PRIVATE KEY-----
MIIEpAIBAAKCAQEAvgp5jKpqy4+9cbXuFXLVtrbtP+WCrVoZrcjsV3OD0EAEnNci
CAHGyIGhQPtf2VHNh8/farRRCyOUwI+hL2HBWIKxKnFNlijdHD79s3ACxd8liAUw
7DR3A9EUiFp9+IfALZAK6GMnEnLDR58gjsrOZccGtCzWboxR+eXgK8qYE1e0yqqP
Qst7qYLYq2zH3aJvOO2mUqrCQsBdL1AR8gqMRpcttNoT34UJtLmktBnB9GJK2NlG
W8gxxXVo+WnPGRoZOUKw6gTnzUoD3NSOTRcl0uaadz/W7P3zr4r/iKuwcB9uJoHW
hz7mx/dqssiNXADa5dAeGpHyoHHgFE7yW2h4eQIDAQABAoIBABfadLtFQLZgSmUV
ctbaXRzcBRd6FVbw8jwv9gpcA3WGM44EKs9aebr9GmJvqu46KFQdsWtRSsLdKnSp
EpBB8uTLMrWjFxv78RT0ix+UtaRkh+90x1k+lJm0CqG6ygkB8QtHAzd8CpF0OjKp
NIr3xcRcoOjIn/msPzXgtqyId2Il7qZhsYb3j1pkEVtgr6KIRx4WXRnC+Lzvm9Yg
wkazSEt5sUuOen9cXglQYsCvAYJf6sZ4klzofmzEijF8Z/EAmOI7FH+awRFW1Qvs
onuLrt0bZ0/j7d4vWcRJG3zLSnjsVw8lBquH7Yty4HJtirGHxqEW/bGFr0S8RXJD
dD892SECgYEA6J5EnGjEI23wbL//VTmANRsRjPcPCq68RKYyXyd31u1zCotAqa6Q
18T4s9FN4rGM4K4ygaqE4iOrDaVDKvDoUh2tDXTikN3ehtkIB/cUZI6AsdmYD/0h
4xx4J6qeVmTjnEIjxSL/0sgi6qu7fGpyIWaJOVAdieQR/M6WChDz5eUCgYEA0SSb
erRmoG9AJVrWuq3YmyPZ4jUz8dbaTsGc6GXxKQgqRnoVtbIEJc8wKi1ekdoJWcjz
zC14fHgO+rqVA3epCU6fsu82nAVFEr6oiVFmVDH3WroPqn0sK9kBjA9itTilEjQo
m6zdI3RlRwkq6EQzKYFXvKEFaFlstDN1HD2xXwUCgYEA2Ylo0HyJMDjX5luHBMRJ
SWCPASzqPCs8lVZ3NNVMFQrp0qp3Rjeh7KafjknmdGFmRZeiU/CLZI/Gn3Q1ZCr2
mBR4iWUNnDxgperAv/IoeAFsCOZcdldbIXC2TSIaAOFImhCgMvOQGiZfwOXo52kE
YofpPFfXx+QpjioD1lYUQKECgYATvnv7IorJvJb2r9OzvfPD+ad5JoKn4xuq8bZJ
bk5NDFtJWf8wrwSbOSsX4D6cUFQvqLvzW5uTTJZFb1XgBOztVwHWl6S1J/40XdF1
XTzm1+y9IPGXq8d+wDbYLR+pchaLWGc5AyHBVhy1jxUA5mdaFL7erOjgyAhuHqmA
qAZVrQKBgQDd7K/H6LpWTLJxCtqlG1mPlgjNrlcvW7PlmZ53FwMub5KGtYWAH8QD
yjE7PlzKr8ZGribgv+zmjwHR8plTdS1Ul/Pv1X/N2ZRdfnK7PDs/DGoUDKPuFmsy
xSjq09n27Aj19uZOz8p1+x2tR5xpvtRN52wSvqeFCYYOGY+vfJeGXw==
-----END RSA PRIVATE KEY-----
