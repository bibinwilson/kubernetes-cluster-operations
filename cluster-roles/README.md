### Get Bearer Token

<pre>kubectl -n kube-system describe secret $(kubectl -n kube-system get secret | grep admin-user | awk '{print $1}')</pre>

### Clusteradmin Creation

<pre>kubectl create clusterrolebinding admin-user --clusterrole=cluster-admin --user=ecoursedealss@gmail.com</pre>
