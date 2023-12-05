# hello-devstack
Repositório somente para brincar um pouco com a distribuição devstack de openstack.\
Cria um VM com os requisítos mínimos e instancia um script para iniciar a configuração do devstack na VM


## Como rodar?
1. [Instale o VirtualBox](https://www.virtualbox.org/wiki/Downloads)
2. [Instale o vagrant](https://developer.hashicorp.com/vagrant/downloads) 
3. ```vagrant up``` para iniciliar o sistema. O Vagrant fará tudo para você, como baixar a imagem e rodar a imagem no virtualbox
4. Para interagir com a VM via ssh ```vagrant ssh```
5. Para parar a VM ```vagrant halt```
6. Para retomar a execução da VM ```vagrant resume```
7. Para destruir (deletar) a VM ```vagran destroy```

## Informações adicionais
* A pasta raiz do projeto esta dentro de ```/vagrant```, portanto ela serve como _mount_ para o computador host, mas cuidado que mexer nela também mexe na pasta host
* Esta VM está consumindo 60GB de disco e 8GB de RAM, portanto pode ser inviável usá-la em PCs mais fracos
