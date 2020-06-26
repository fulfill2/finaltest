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
``
