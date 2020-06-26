# 1. 이미지 사용
```
kubectl run <Deploy명> --image=<DockHub이미지> --port=80
```
# 2. Pod는 20개 사용
```
kubectl scale deployment ubuntu-nginx --replicas=20
```
# 3. Service port는 80번
```
kubectl expose deployment/ubuntu-nginx --type="NodePort" --port 80
``` 
# 4. 사용 예
``` 
kubectl run ubuntu-nginx --image=fulfill2/finaltest --port=80
kubectl get deployments
kubectl expose deployment/ubuntu-nginx --type="NodePort" --port 80
kubectl scale deployment ubuntu-nginx --replicas=20
kubectl get deployments
kubectl describe deployments/ubuntu-nginx

```
