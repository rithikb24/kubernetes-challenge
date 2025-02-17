# Kubernetes challenge

Deploy this application to [Minikube](https://github.com/kubernetes/minikube) and customise the environment variable to display your name.

```
$ curl $(minikube ip)
Hello Dan!
```

## Instructions

- Fork this repo
- Build the Docker image
- Write yaml files for a deployment, service, ingress and configmap
- Deploy your application to Minikube
- You should be able to `curl` Minikube's ip and retrieve the string `Hello {yourname}!`
- Commit your files to Github

## Notes

There's no need to push the Docker image to a Docker registry. You should be able to build and use the image from within Minikube.

You can expose Minikube's Docker daemon with:

```shell
$ eval (minkube docker-env)
```

Answer - 
Deployment, Service And Ingress file are in K8s folder. 

To use the ingress host, run 'minikube ip' and add the ip and hostname to /etc/hosts.

![image](https://user-images.githubusercontent.com/48003177/153744526-20234899-a0a5-45b1-a66f-61678e1e398e.png)
