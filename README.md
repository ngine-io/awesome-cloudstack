![Build Status](https://github.com/resmo/awesome-cloudstack/actions/workflows/main.yml/badge.svg)

# Awesome Apache CloudStack

> A curated list of bookmarks, projects, tutorials, videos and other cool resources from the CloudStack ecosystem.

## Table of Contents

- [Essentials](#essentials)
- [Installation Guides](#installation-guides)
- [Packages and Images](#packages-and-templates)
- [Command Line Interface Clients](#command-line-interface-clients)
- [Configuration Management Integrations](#configuration-management-integrations)
- [Libraries](#libraries)
- [Operational Extensions](#operational-extensions)
- [Public Cloud Providers](#public-cloud-providers)
- [Videos](#videos)
- [Articles, Tutorials, Blogs, etc.](#articles-tutorials-blogs-etc)
- [Development](#development)
- [Community](#community)

## Essentials

* [Apache CloudStack](https://cloudstack.apache.org/)
* [CloudStack API Reference](https://cloudstack.apache.org/api.html)

## Installation Guides

* [CloudStack Official Installation Guide](https://docs.cloudstack.apache.org/en/latest/installguide/)
* [CloudStack x86_64 Ubuntu KVM Install Guide](https://rohityadav.cloud/blog/cloudstack-kvm/)
* [CloudStack ARM64 Ubuntu KVM Install Guide](https://rohityadav.cloud/blog/cloudstack-arm64-kvm/)
* [Ceph Installation and CloudStack Usage Guide](https://rohityadav.cloud/blog/ceph/)

## Packages and Templates

### Installation Packages

* [Install Packages from Community Repo](https://download.cloudstack.org)
* [Install Packages from ShapeBlue](https://www.shapeblue.com/packages/)

### Templates

* [Pre-Built Instance Templates](http://dl.openvm.eu/cloudstack/)
* [SystemVM Packer](https://github.com/MissionCriticalCloud/systemvm-packer)
* [Instance Templates Packer by Schuberg Philis](https://github.com/MissionCriticalCloud/bubble-templates-packer)
* [Instance Templates Packer by PCextreme](https://github.com/PCextreme/packer-templates)

## Command Line Interface Clients

* [cmk - Apache CloudMonkey (Official Go-based CLI)](https://github.com/apache/cloudstack-cloudmonkey)
* [CloudStack Go-SDK (Official SDK)](https://github.com/apache/cloudstack-go)
* [cs (Python)](https://github.com/ngine-io/cs)
* [cloudstack-cli (Ruby)](https://github.com/niwo/cloudstack-cli)

## Configuration Management Integrations

### Ansible

* [Ansible CloudStack Integration](https://docs.ansible.com/ansible/latest/collections/ngine_io/cloudstack/index.html)
* [Ansible Cloud Infra Role (Advanced Networking)](https://github.com/swisstxt/ansible-role-cloud-infra)

### Kubernetes

* [CAPC - Cluster API Provider for CloudStack](https://cluster-api-cloudstack.sigs.k8s.io/introduction)
* [CloudStack Kubernetes Provider](https://github.com/apache/cloudstack-kubernetes-provider)
* [CloudStack CSI Driver](https://github.com/shapeblue/cloudstack-csi-driver)

### Terraform

* [CloudStack Provider](https://github.com/apache/cloudstack-kubernetes-provider)

### Vagrant
* [Vagrant Cloudstack Provider ](https://github.com/MissionCriticalCloud/vagrant-cloudstack)

## Libraries

* [cs (Python)](https://github.com/ngine-io/cs)
* [go-cloudstack (Go)](https://github.com/xanzy/go-cloudstack)
* [golang-cloudstack-library (Go)](https://github.com/atsaki/golang-cloudstack-library)
* [cloudstack PHP Client (PHP - ACS 4.10 compatible)](https://github.com/myENA/cloudstack-php-client)
* [cloudstack-php (PHP)](https://github.com/PCextreme/cloudstack-php)
* [cloudstack_client (Ruby)](https://github.com/niwo/cloudstack_client)
* [Apache libcloud (Python)](https://libcloud.apache.org/)
* [Apache jclouds (Java)](https://jclouds.apache.org/)
* [apache-cloudstack-java-client (Java)](https://github.com/Autonomiccs/apache-cloudstack-java-client)
* [apache-cloudstack-javascript-client (JavaScript)](https://github.com/Autonomiccs/apache-cloudstack-javascript-client)
* [.NET SDK for CloudStack](https://github.com/richardlawley/cloudstack.net)
* [vhd-util for manipulating Xen VHDs](https://github.com/NuxRo/vhd-util)

## Operational Extensions

### Montitoring and Graphs

* [CloudStack Nagios Monitoring by SWISS TXT](https://github.com/swisstxt/cloudstack-nagios)
* [collectd-cloudstack Plugin](https://github.com/exoscale/collectd-cloudstack)
* [CloudStack Statistics into InfluxDB](https://github.com/niwo/cloudstats)
* [csbench - CloudStack Benchmarking Tool](https://github.com/apache/cloudstack-csbench)

### RealHostIP replacement

* [nip.io - realhostip compatible service](https://github.com/exentriquesolutions/nip.io)
* [powerdns-cloudstack-proxy-dns](https://github.com/terbolous/powerdns-cloudstack-proxy-dns)

### Billing Solutions

* [HostBill (commercial)](http://hostbillapp.com/feature/cloudstack-overview/)
* [Amysta (commercial)](http://www.amysta.com/)
* [Cyclops](https://icclab.github.io/cyclops/)

### Misc

* [Chaotic - Chaos for Clouds](https://github.com/ngine-io/chaotic)
* [Scalr - Autoscaling for Clouds](https://github.com/ngine-io/scalr)
* [Alternative CloudStack-UI by Bitworks Software, Ltd.](https://bwsw.github.io/cloudstack-ui/)

## Public Cloud Providers

* [Ikoula](https://www.ikoula.com/en)
* [LeaseWeb](https://www.leaseweb.com/)
* [PCextreme](https://www.pcextreme.com/)

## Videos

* [Introduction to Apache CloudStack by David Nalley](https://www.youtube.com/watch?v=1MDLg-wxB6g)
* [CloudOps Channel](https://www.youtube.com/channel/UC0FMV0TSW6jvSRGC26r4-Gw)

## Articles, Tutorials, Blogs, etc

* [Wikipedia Article](https://en.wikipedia.org/wiki/Apache_CloudStack)
* [ShapeBlue Blog](https://www.shapeblue.com/blog/)
* [Remi Bergsma's blog](https://blog.remibergsma.com/tag/cloudstack-2/)
* [shankerbalan.net](https://shankerbalan.net/)
* [Rohit Yadav's Blog](https://rohityadav.cloud)

## Development

### Main

* [GitHub](https://github.com/apache/cloudstack)
* [Apache CloudStack Issue Tracker - GitHub](https://github.com/apache/cloudstack/issues)
* [Apache CloudStack Issue Tracker - Jira (retired)](https://issues.apache.org/jira/browse/CLOUDSTACK)
* [Hackerbook](https://github.com/shapeblue/hackerbook) - Guide to CloudStack Development

### Development Environment

* [mbx](https://github.com/shapeblue/mbx) - build dev and QA environments on KVM
* [Apache CloudStack Simulator as Docker Container](https://hub.docker.com/r/apache/cloudstack-simulator)
* [CloudStack Simulator Container](https://github.com/ansible/cloudstack-test-container)

### Continuous Integrations

* [Trillian](https://github.com/shapeblue/Trillian)
* [bubble-blueprint](https://github.com/MissionCriticalCloud/bubble-blueprint)
* [GitHub CI CloudStack Service Workflow](https://github.com/apache/cloudstack-terraform-provider/blob/main/.github/workflows/acceptance.yml)

### Build with Docker

* [RPM Builder](https://github.com/khos2ow/cloudstack-rpm-builder)
* [DEB Builder](https://github.com/khos2ow/cloudstack-deb-builder)

## Community

* [Mailing Lists](http://cloudstack.apache.org/mailing-lists.html)
* IRC: `irc://irc.libera.chat/cloudstack`
* [Slack](https://apachecloudstack.slack.com)

## Contributing

Found an awesome project, blog, video etc.? Send me a pull request!

### Guidelines

* Please make an individual pull request for each suggestion
* Make sure the TravisCI tests pass on your pull request
* Use the following format for links: \[Resource\]\(URL\)
* New categories or improvements to the existing categorization are welcome

## License

[![CC BY 4.0](https://licensebuttons.net/l/by/4.0/88x31.png)](https://creativecommons.org/licenses/by/4.0/)

Awesome CloudStack is licensed under a [Creative Commons Attribution 4.0 International License](https://creativecommons.org/licenses/by/4.0/).
