apiVersion: v1
kind: Pod
metadata:
   name: nginx
   labels:
      env: dev
      app: nginx
   spec:
     containers:
       - name: nginxweb
         image: nginx:latest
         ports:
           - name: nginxport
             containerPort: 80
             protocol: TCP
