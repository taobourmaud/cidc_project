## Documentation CICD 


## Build docker 

docker build -t ``image_name`` .
docker run -d -p ``port:port`` --name ``container_name`` ``image_name``


## 



kubectl port-forward service/frontend-service 3000:3000
kubectl port-forward service/db 27017:27017
kubectl port-forward service/user-service 3001:3001
kubectl port-forward service/order-service 3002:3002 