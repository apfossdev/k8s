az aks create \
--resource-group new-resource-group \
--name annamalaiAKScluster \
--node-count 3 \
--node-vm-size standard_B2pls_v2 \
--generate-ssh-keys \ use this if you have no ssh keys in you .ssh folder and will use the newly generate ones here .ssh/id_rsa, .ssh/id_rsa.pub else use the below flag
--ssh-key-value azure_rsa_key.pub \
--attach-acr annamalaistudentacr

- don't have access in my company account, need to try with the personal or nautilus cluster

