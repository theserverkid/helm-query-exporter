## Helm chart for query-explorer
Source Code Repo: https://github.com/albertodonato/query-exporter

### HELM Chart Repo
helm repo add helm-query-exporter https://theserverkid.github.io/helm-query-exporter/

### Chart Installation instructions
helm install helm-query-exporter helm-query-exporter -n {{namespace}}  
helm upgrade helm-query-exporter helm-query-exporter -n {{namespace}}

### Scrape configuration
http://helm-query-exporter.{{namespace}}.svc.cluster.local/metrics



