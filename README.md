# Documentation

See: http://bearded-avenger.readthedocs.org

# Getting Started
## Vagrant (Ubuntu14/Virtualbox)
```
$ make vagrant
$ vagrant ssh
$ mkvirtualenv cif && workon cif
$ cd /vagrant && bash ./helpers/develop.sh
$ supervisord
```

## Ubuntu 14.04 (clean install)
```
$ make ubuntu14
$ mkvirtualenv cif && workon cif
$ bash helpers/develop.sh
$ supervisord
```
## Docker
```
$ make docker
```

# Getting Involved
There are many ways to get involved with the project. If you have a new and exciting feature, or even a simple bugfix, simply [fork the repo](https://help.github.com/articles/fork-a-repo), create some simple test cases, [generate a pull-request](https://help.github.com/articles/using-pull-requests) and give yourself credit!

If you've never worked on a GitHub project, [this is a good piece](https://guides.github.com/activities/contributing-to-open-source) for getting started.

* [How To Contribute](contributing.md)  
* [Mailing List](https://groups.google.com/forum/#!forum/ci-framework)  
* [Project Page](http://csirtgadgets.org/collective-intelligence-framework/)

# COPYRIGHT AND LICENCE

Copyright (C) 2015 [the CSIRT Gadgets Foundation](http://csirtgadgets.org)

Free use of this software is granted under the terms of the GNU Lesser General Public License (LGPLv3). For details see the files `COPYING` included with the distribution.


