# NGINX Reverse Proxy Deployment

Use Case: Have services that cannot be hosted in Kubernetes and want to be able to route traffic there

In this case this deployment deploys ubuntu/nginx:edge image, with a service exposing ports 80/443 with a LoadBalancer IP, you will then configure youre DNS infra to point to the LoadBalancer IP provisioned by Kubernetes and everything should just work
