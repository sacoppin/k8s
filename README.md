# k8s


kubectl apply -f [filename]     => apply configuration file
kubectl delete -f [filename]    => delete configuration file
kubectl get pod
kubectl describe pod [podname]  => get info about pod
kubectl get deployment
kubectl logs        => lo to console
kubectl exec -it    => get interactive terminal



## The mission

Today we are going to learn about two different and very important concepts when deploying applications with k8s which are Stateless versus Stateless deployments.

Basicaly you will have to ask yourself the following question : <br>
Does the application I'm deploying need to keep its datas (the state)? if yes, it means that you will have to perform a Statefull deployment. On the other hand, if your application doesn't need to keep it's datas (state) it means that you will need a Stateless deployment.

In order to help you implement these two types of deployments, your mission is to follow the two following tutorials:

* Stateless: [Deploying PHP Guestbook application with Redis](https://kubernetes.io/docs/tutorials/stateless-application/guestbook/)
* Statefull: [Deploying WordPress and MySQL with Persistent Volumes](https://kubernetes.io/docs/tutorials/stateful-application/mysql-wordpress-persistent-volume/)

