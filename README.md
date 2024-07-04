# flux-operator

flux-operator/
├── hub/
│   ├── flux-instance.yaml
│   └── kustomization.yaml
├── spokes/
│   ├── spoke-1/
│   │   ├── flux-instance.yaml
│   │   ├── kustomization.yaml
│   │   ├── apps/
│   │   │   ├── app/
│   │   │   │   ├── deployment.yaml
│   │   │   │   ├── service.yaml
│   │   │   │   └── kustomization.yaml
│   │   └── infrastructure/
│   │       ├── infra/
│   │       │   ├── namespace.yaml
│   │       │   └── kustomization.yaml
│   │       ├── app-namespace/
│   │       │   ├── namespace.yaml
│   │       │   └── kustomization.yaml

