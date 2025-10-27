d:\helm\microservices-demo>helm template microservices-demo .

d:\helm\microservices-demo>helm upgrade microservices-demo . --install --namespace microservices-demo


helm list -n microservices-demo


helm history microservices-demo -n microservices-demo

helm rollback microservices-demo 1 --namespace microservices-demo
helm rollback microservices-demo --namespace microservices-demo

Parent value always override subchart value!