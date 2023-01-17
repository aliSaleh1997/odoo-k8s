# odoo-k8s
kubectl create ns nodoo
kubectl apply -f configmap.yml 
 kubectl apply -f postgres-dep.yml 
 kubectl apply -f svc-postgres.yml 
 kubectl apply -f odoo-dep.yml 