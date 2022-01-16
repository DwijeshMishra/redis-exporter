kubectl apply -f redis-exporter.yml

kubectl get svc

curl 10.111.142.253:9121/metrics
