# YAML Structure

### POD
![YML Structure](./static/structure.png) 
```yaml
apiVersion: v1
kind: Pod
metadata:
    name: myapp-pod
    labels:
        app: myapp
        type: front-end
spec:
    containers:
        - name: nginx-controller
          image: nginx
```
```
kubectl create -f pod-definition.yml
```

```
kubectl get pods
```

```
kubectl describe myapp-pod
```


### Replication

![rc.png](./static/rc.png) 


### Replicaset

![rc.png](./static/rcset.png) 

### Label
![label.png](./static/label.png) 

![lb2.png](./static/lb2.png) 

### Scale
![lb2.png](./static/scale.png) 

### Scale with out modify file
![lb2.png](./static/scale2.png) 

