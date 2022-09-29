# StatefulSets_on_K8s_Cluster
Building a mongodb using statefulsets for efficient database persistence

helm repo add bitnami https://charts.bitnami.com/bitnami

helm install mongodb --values mongodb-values.yaml bitnami/mongodb