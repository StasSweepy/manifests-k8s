## Portfolio of yaml manifests for Kubernetes

| NAME                   | PROMPT               | DESCRIPTION                                                                   | EXAMPLE  |
|------------------------|----------------------|------------------------------------------------------------------------------|----------|
| app.yaml               | Kubernetes Manifest | General YAML format manifest for deploying an application in Kubernetes.     |     [Click](https://github.com/StasSweepy/manifests-k8s/blob/main/yaml/app.yaml)     |
| app-livenessProbe.yaml | Liveness Probe       | Manifest defining a livenessProbe for the application container.              |     [Click](https://github.com/StasSweepy/manifests-k8s/blob/main/yaml/app-livenessProbe.yaml)     |
| app-readinessProbe.yaml| Readiness Probe      | Manifest defining a readinessProbe for the application container.             |      [Click](https://github.com/StasSweepy/manifests-k8s/blob/main/yaml/app-readinessProbe.yaml)    |
| app-volumeMounts.yaml  | Volume Mounts        | Manifest describing mounted volumes in the application container.            |     [Click](https://github.com/StasSweepy/manifests-k8s/blob/main/yaml/app-volumeMounts.yaml)     |
| app-cronjob.yaml       | CronJob              | Manifest for creating a CronJob in Kubernetes to run tasks on a schedule.     |     [Click](https://github.com/StasSweepy/manifests-k8s/blob/main/yaml/app-cronjob.yaml)     |
| app-job.yaml           | Job                  | Manifest for creating a Job in Kubernetes to execute one-off tasks.           |      [Click](https://github.com/StasSweepy/manifests-k8s/blob/main/yaml/app-job.yaml)    |
| app-multicontainer.yaml| Multi-Container      | Manifest for deploying multiple containers within a single Pod.               |     [Click](https://github.com/StasSweepy/manifests-k8s/blob/main/yaml/app-multicontainer.yaml)     |
| app-resources.yaml     | Resources            | Manifest specifying resource (CPU, memory) allocations for the application container. |     [Click](https://github.com/StasSweepy/manifests-k8s/blob/main/yaml/app-resources.yaml)     |
| app-secret-env.yaml    | Secret Environment   | Manifest using Kubernetes secrets for environment variables.                 |      [Click](https://github.com/StasSweepy/manifests-k8s/blob/main/yaml/app-secret-env.yaml)    |
