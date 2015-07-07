# samba

Forked version of samba with ClearOS changes applied

## Update usage
  Add __#kojibuild__ to commit message to automatically build

* git clone git+ssh://git@github.com/clearos/samba.git
* cd samba
* git checkout c7
* git remote add upstream git://git.centos.org/rpms/samba.git
* git pull upstream c7
* git checkout clear7
* git merge --no-commit c7
* git commit
