ansible-java-packages
=====================

[![Build Status](https://travis-ci.org/lsst-sqre/ansible-java-packages.svg?branch=master)](https://travis-ci.org/lsst-sqre/ansible-java-packages)

Install java using packaging for LSST SQuaRE infrastructure.

Example Playbook
----------------

    - hosts: servers
      roles:
         - { role: lsst-sqre.java-packages }


Variables
---------

`java_packages_use_headless` The default is `yes`. Use the headless JRE package.

`java_packages_use_jdk` The default is `no`. Use the JDK package. Not compatible with `java_packages_use_headless`.

License
-------

The MIT License. See the [LICENSE file](https://github.com/lsst-sqre/ansible-java-packages/blob/master/LICENSE).
