## Portfolio of yaml manifests for Kubernetes

| NAME                   | PROMPT               | DESCRIPTION                                                                   | EXAMPLE  |
|------------------------|----------------------|------------------------------------------------------------------------------|----------|
| app.yaml               | Kubernetes Manifest | General YAML format manifest for deploying an application in Kubernetes.     |          |
| app-livenessProbe.yaml | Liveness Probe       | Manifest defining a livenessProbe for the application container.              |          |
| app-readinessProbe.yaml| Readiness Probe      | Manifest defining a readinessProbe for the application container.             |          |
| app-volumeMounts.yaml  | Volume Mounts        | Manifest describing mounted volumes in the application container.            |          |
| app-cronjob.yaml       | CronJob              | Manifest for creating a CronJob in Kubernetes to run tasks on a schedule.     |          |
| app-job.yaml           | Job                  | Manifest for creating a Job in Kubernetes to execute one-off tasks.           |          |
| app-multicontainer.yaml| Multi-Container      | Manifest for deploying multiple containers within a single Pod.               |          |
| app-resources.yaml     | Resources            | Manifest specifying resource (CPU, memory) allocations for the application container. |          |
| app-secret-env.yaml    | Secret Environment   | Manifest using Kubernetes secrets for environment variables.                 |          |
