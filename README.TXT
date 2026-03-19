La consigne demande une sauvegarde ETCD, mais le cluster K3s utilisé ne repose pas sur le datastore etcd ; la commande sudo k3s etcd-snapshot save retourne etcd datastore disabled.

j'ai exécuté la commande suivante : "sudo k3s etcd-snapshot save --name sauvegarde-finale"


curl http://api.k3s.cloud-ip.cc/users
curl http://api.k3s.cloud-ip.cc/users/count
