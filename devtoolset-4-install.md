# Red Hat Developer Toolset 4.1 Installation
- Install a package with repository for your system
    * RHEL 6: `$sudo yum-config-manager --enable rhel-server-rhscl-6-rpmss`
    * RHEL 7: `$sudo yum-config-manager --enable rhel-server-rhscl-7-rpms`
    * $sudo yum install centos-release-scl
- Install the collection
    * $sudo yum install devtoolset-4-perftools devtoolset-4-toolchain
- Start using software collections
    * $source scl_source enable devtoolset-4
    