# WebFront

This is a super simple project that installs apache and puts a html-file in the right place.
It is only used as an example for the Source to Image project OSCP-S2I-Ansible-Builder and
showcase how to use Vagrant as a development environment that automatically sets up the same environment that you will have in a container environment.


For using this with vagrant:
```
  mkdir webfront
  cd webfront
  curl -O  https://raw.githubusercontent.com/mtekkie/WebFront/master/_vagrant/Vagrantfile
  vagrant up
```

For using this with OSCP-S2I-Ansible-Builder: See that project.
