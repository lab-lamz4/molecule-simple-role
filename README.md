# molecule-simple-role

Simple role for molecule demo 

**Requirement:** 

*Ubuntu 18.04 LTS*
*Vagrant*
*Virtualbox*

## Install pyenv (optional)

https://github.com/pyenv/pyenv-installer

## Python 3.7

show versions for python 3.7.x

```bash
pyenv install -l
```

Install python 3.7

```bash 
pyenv install 3.7.6
```

Set to use installed python version

```bash
cd project
pyenv local 3.7.6
cd ../project
```

Verify version

```bash
python -V
```

## Ansible install

You can use newer ansible, but tested in 2.8

```bash
pip install ansible==2.8
```

## Molecule install 

```bash
pip install molecule==2.22
```

## Clone repo

```bash
git clone https://github.com/lab-lamz4/molecule-simple-role.git
```

## Install Vagrant 

https://www.vagrantup.com/docs/installation/

```bash
wget https://releases.hashicorp.com/vagrant/2.2.7/vagrant_2.2.7_x86_64.deb
sudo dpkg -i vagrant_2.2.7_x86_64.deb
pip install python-vagrant
```

## Install VirtualBox

Get & Install 

https://www.virtualbox.org/

```bash
wget -q https://www.virtualbox.org/download/oracle_vbox_2016.asc -O- | sudo apt-key add -
wget -q https://www.virtualbox.org/download/oracle_vbox.asc -O- | sudo apt-key add -
echo 'deb [arch=amd64] https://download.virtualbox.org/virtualbox/debian bionic contrib >> /etc/apt/sources.list'
sudo apt-get update
sudo apt-get install virtualbox-6.1
sudo /sbin/vboxconfig
```




