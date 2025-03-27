
«Применение принципов IaaC в работе с виртуальными машинами» - «Бычков Денис Вячеславович»      
    
--- 
Задача 1

vm1@vm1:~/Загрузки$ vboxmanage --version
6.1.38_Ubuntur153438
vm1@vm1:~/Загрузки$
vm1@vm1:~/Загрузки$ vagrant -v
Vagrant 2.2.6
vm1@vm1:~/Загрузки$
vm1@vm1:~/Загрузки$ terraform --version
Terraform v1.5.0-alpha20230504
on linux_amd64
vm1@vm1:~/Загрузки$
vm1@vm1:~/Загрузки$ ansible --version
ansible 2.9.6
  config file = /etc/ansible/ansible.cfg
  configured module search path = ['/home/vm1/.ansible/plugins/modules', '/usr/share/ansible/plugins/modules']
  ansible python module location = /usr/lib/python3/dist-packages/ansible
  executable location = /usr/bin/ansible
  python version = 3.8.10 (default, Mar 13 2023, 10:26:41) [GCC 9.4.0]
vm1@vm1:~/Загрузки$


Задача 2

wget https://app.vagrantup.com/bento/boxes/ubuntu-20.04/versions/202401.31.0/providers/virtualbox/amd64/vagrant.box
vagrant box add bento/ubuntu-20.04 vagrant.box
vagrant box list
nano Vagrantfile
vagrant up

