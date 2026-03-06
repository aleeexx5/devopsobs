As general idea, there will be an application, for instance a web application. Metrics and logs will be exposed to Vector, who will transform them and send them to Elasticsearch / Victoria Metrics. Then with Grafana, we will read the metrics (and presumably the logs, if we finally integrate them with VM) from VM and we will be able to create dashboards and so on.

As of now, only metrics are exposed, from vector itself. Logs are dummy logs that go into Elastic, being parsed previously by Vector
