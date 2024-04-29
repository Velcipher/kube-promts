To run YAML config file use the command below:
```sh
kubectl apply -f <FILE_PATH>.yaml
```

| NAME | PROMPT | DESCRIPTION | EXAMPLE |
|:----:|:------:|:-----------:|:-------:|
|app.yaml| Simple POD parameters |Run POD with simplest configs  | [app.yaml](yaml/app.yaml)|
|app-livenessProbe.yaml| Manifest with liveness probe | Create livenessProbe with period 20s snd failure 4 times | [app-livenessProbe.yaml](yaml/app-livenessProbe.yaml)  |
|app-readinessProbe.yaml| Manifest with readiness probe | Readiness probe  | [app-readinessProbe.yaml](yaml/app-readinessProbe.yaml) |
|app-volumeMounts.yaml| Manifest with volume mount | Configure a Pod to use a Volume for storage |[app-volumeMounts.yaml](yaml/app-volumeMounts.yaml) |
|app-cronjob.yaml| Cron Job manifest | Performing regular scheduled actions such as backups, report generation, and so on. |  [app-cronjob.yaml](yaml/app-cronjob.yaml) |
|app-job.yaml | Job manifest | Creates one or more Pods and will continue to retry execution of the Pods until a specified number of them successfully terminate | [app-job.yaml](yaml/app-job.yaml) |
|Multicontainer Application| Multicontainer POD manifest | Create POD with 2 containers | [app-multicontainer.yaml](yaml/app-multicontainer.yaml)|
|app-resources.yaml|Simple resources manifest | Resources configuration | [app-resources.yaml](./yaml/app-resources.yaml)|
|app-secret-env.yaml| Simple secret mount manifest | Stores environment variables and files |[app-secret-env.yaml](./yaml/app-secret-env.yaml) |