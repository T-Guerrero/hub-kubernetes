# Hub USP Inovação Kubernetes Deploy

With a minikube cluster running, load both hub_solus and hubuspinovacao/backend:development images from Docker images using the following commands:

```bash
$> minikube load image <image_name>
```

## Important commands

minikube kubectl -- apply -f <filename> `Apply config file`

minikube service <service_name> `get external URL of a external service`
