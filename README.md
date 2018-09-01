# Vagrant CentOS Hadoop

# Downloads
* Virtual Box 5.2.6+   	https://download.virtualbox.org/virtualbox/5.2.6/
* Vagrant 2.0.1+       	https://www.vagrantup.com/downloads.html
* Putty					https://www.putty.org/


# Vagrant vbguest
Após a instalação do vagrant, acesse seu terminal e instale o plugin vbguest, que irá evitar que erros de montagem aconteçam no ambiente
```
vagrant plugin install vagrant-vbguest
vagrant vbguest
```

# Iniciando o Vagrant

Criar um diretorio na raiz c:\vagrant
executar no prompt de comando

cd c:\vagrant
vagrant box add CentOS https://github.com/tommy-muehle/puppet-vagrant-boxes/releases/download/1.1.0/centos-7.0-x86_64.box

executar o comando 
vagrant init CentOS
para criar os arquivos de confiração do Vagrant

https://www.vagrantbox.es/

# Introdução 
Projeto vagrant para provisionamento de ambiente com as seguintes ferramentas Apache:
 

 
