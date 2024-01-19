# Reference deployment repository structure
## With examples
.
├── local-deployment
│   ├── native
│   │   ├── ansible
│   │   │   ├── playbook.yaml
│   │   │   └── .env-example
│   │   └── powershell
│   │       ├── script.ps1
│   │       └── powershell.env-example
│   └── containerized
│       └── docker-compose
│           ├── Dockerfile
│           ├── docker-compose.yaml
│           └── .env-example
│
└── cluster-deployment
    ├── helm
    │   ├── charts
    │   ├── Chart.yaml
    │   ├── values.yaml
    │   └── templates
    ├── kustomize
    │   ├── kustomization.yaml
    │   ├── base
    │   └── overlays
    └── argocd
        ├── app.yaml
        └── project.yaml
