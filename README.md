kubectl apply -f redis-exporter.yml

kubectl get svc

curl 10.111.142.253:9121/metrics

$ kubectl delete secret additional-configs -n monitoring
$ kubectl create secret generic additional-configs --from-file=prometheus-additional.yaml -n monitoring

kubectl get svc -n monitoring

$ curl -X POST "http://10.101.207.170:9090/-/reload"


---------------------------------------------------------------------------------------------------------
curl  https://github.com/helm/charts/blob/master/stable/redis/values-production.yaml
