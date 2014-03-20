nepho-example
=============

This is a basic cloudlet for [nepho](http://github.com/huit/nepho) that deploys a single host to various cloud providers. A quick way to get started with a single host installation, or as a first step to more complex deployments.

For more details on developing cloudlets see the `nepho-example` cloudlet here:

- https://github.com/cloudlets/nepho-example

Details
=======

This cloudlet curerntly contains three blueprints, each of which deploy a single host, but on different prpviders or in different ways.

### vagrant-single-host

This blueprint deploys a CentOS 6 using [vagrant](http://vagrantup.com) locally on your client machine, then bootstraps some basic steps. I does port forwarding for SSH compatible with vagrant, as well as forwarding the standard web ports locally to ports 8080 and 8443.

### aws-single-host

This bluepirint starts up a instance (micro by default) in Amazon EC2 based on Amazon Linux, which is mostly compatbiel with CentOS and RHEL.

### 