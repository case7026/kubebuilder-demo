# kubebuilder-demo
Just messing around with kubebuilder as a method of generating custom resource definitions for use as controllers or operators!

## Why this tool is useful

### Setting things up for our controller
![alt text](https://github.com/apaz037/kubebuilder-demo/raw/master/hack/images/setting-things-up.png "applying our generated install.yaml")

### Creating a Custom Resource from our CRD
![alt text](https://github.com/apaz037/kubebuilder-demo/raw/master/hack/images/creating-a-custom-resource.png "creating a CR from our CRD")

### Implementing Controller/Operator Functionality quickly and easily
![alt text](https://github.com/apaz037/kubebuilder-demo/raw/master/hack/images/controller_reconcile_function.png "demo of controller reconcile funcion, get's hit when a CR is created from our CRD")

## Links
- [Docker Hub Image](https://hub.docker.com/r/aaronpaz/kubebuilder-demo/)
- [Under The Hood of Kubebuilder](https://itnext.io/under-the-hood-of-kubebuilder-framework-ff6b38c10796)

## Notes
"When simply deploying is not enough is when I start to scratch my head wondering whether its time to start writing a controller or an operator." - Kris Nova

"A controller is a very specific declarative piece of software that reconciles state and an operator is just a domain specific controller." - Joe Beda
