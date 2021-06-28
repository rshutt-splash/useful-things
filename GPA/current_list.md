
## [1 Node Exporter for Prometheus Dashboard EN v20201010](https://grafana.tools.splashdevelop.com/d/lPXzDGk7z/1-node-exporter-for-prometheus-dashboard-en-v20201010?orgId=1)
What are Job and Origin Prom all about?

Otherwise, a good Node graph

Several graphs break at the "Last 15 minutes" time selection.

## Alert - Kubernetes Disk Space

Graphs kubelet mounted storage space in percentage used, per instance (hostname, mountpoint).  Should have predictives.

## Alert - Persistent Volume Claim Disk Space

Graphs PVC percentage used.  Should have predictives.

## Alerts - Kubernetes Cluster (Prometheus)

This first graph, not sure what's going on...   Return is in percentage of 1 format.

Needs more investigation

## Alerts - Kubernetes Nodes and Pods - Unhealthy

This could be replaced and/or augmented with a standardized kube-state-metrics inquiry I believe.

## Alerts / Horizonal Pod Autoscalers

This generates an error when switching to the "alert" in the "Edit" feature.

`Do you want to delete notifier with invalid ID: undefined from the dashboard JSON?

## Amazon Auto Scaling

This dashboard seems broken?  No data sources found?  Region: Default is only choice?

## Amazon Auto Scaling Paulie Special

## Amazon CloudFront

## Amazon CloudWatch Logs

## Amazon EBS

## Amazon EC2

## Amazon ELB Application Load Balancer

## Amazon Lambda

## Amazon RDS

## Amazon RDS Instance

## Amazon RDS Paulie Special

Above AWS dashboards seem not to be working similar to the previous.

## AMER Development Home

Interesting way to use grafana as a portal to other things...

## Argo CD Image Updater (repo)

This seems to be working as intended.  Without better understanding ArgoCD, I have to defer.

## Argp CD Image Updater Alert

This seems to be working as intended.  Without better understanding ArgoCD, I have to defer.

It would be better to alert on awkward changes... big up or big down...

## ArgoCD

Uptime not working.

Health Status (argocd_app_info{namespace, dest_server, health_status, sync_status}) could be an alert - It sort of already is

Sync Status (same) could be an alert - It sort of already is

Controller Telemetry has no data

Git Fetch performance could become an alert (argocd_git_request_total{request_type="fetch",k8s_namespace})

Server Stats (memory) is no data

gRPC tables are no data

## ArgoCD Alerts 

Has the alerts from above

## ArgoCD Static

Not sure what this is about?

## Autoscaling Pods and Kubernetes Nodes

Captuers both HPA and ASG scaling - very splash-specific

I would want to add "rate of change" alerts.  I.e. growing for 10 minutes, grew 100% in X minutes, etc...

## AWS Auto Scaling

Working Dashboard

No alerts

Might consider alerting on rate of scaling

## AWS Elasticache 



