# MERN application automated deployment to Kubernetes
This is a simple helm chart for installing MERN app on `minikube`.

## Requirements
1. Install [minikube](https://minikube.sigs.k8s.io/docs/start/).
2. Install [helm](https://helm.sh/).
3. Install [kubectl](https://kubernetes.io/docs/reference/kubectl/kubectl/).

## Deploy
1. Clone the repo.
```
$ git clone https://github.com/11me/mern-app.git

$ cd mern-app
```
2. Start the script.
```
$ ./start
```
*script asks for root password for modifying /etc/hosts file.*

3. Wait until deployment finishes. It can take up to 3-4 min.

4. Open browser and go to `http://mern-app.local`. If you see an error `Bad gateway`
   just wait a few minutes.

## Cleanup
For cleaning up just run `./clean` script.
