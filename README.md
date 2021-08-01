#How to use#
L'idée est de lancer l'installation du server avec :
``
ansible-playbook install-nfs-server.yml -- hosts --extra-vars "nfs-server=X.X.X.X"
``
lancer l'installation du client
``
ansible-playbook install-nfs-client.yml -- hosts --extra-vars "nfs-client=X.X.X.X"
``

