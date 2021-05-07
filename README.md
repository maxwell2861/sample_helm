
# Sample Helm


> Sample Multiple Helms

```

├── Chart.yaml
├── README.md
├── charts
│   ├── other-service
│   │   ├── Chart.yaml
│   │   ├── templates
│   │   │   └── configmap.yaml
│   │   └── values.yaml
│   └── other-service2
│       ├── Chart.yaml
│       ├── templates
│       │   └── configmap.yaml
│       └── values.yaml
├── templates
│   ├── NOTES.txt
│   ├── _helpers.tpl
│   ├── deployment.yaml
│   └── service.yaml
└── values.yaml

```