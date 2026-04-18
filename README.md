# kube-syncthing

Simple manifests that configure the `syncthing` container inside of kubernetes:

- namespace: `syncthing`
- LoadBalancer for networking service
- local storage for pvc
- deployment with liveness and readiness probes using health check endpoint
