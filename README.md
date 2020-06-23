- [About Cloud Hypervisor](#about-cloud-hypervisor)
- [Governance](#governance)
  * [Projects](#projects)
  * [Developers](#developers)
    + [Contributors](#contributors)
    + [Maintainers](#maintainers)
    + [Becoming a project maintainer](#becoming-a-project-maintainer)
  * [Architecture Committee](#architecture-committee)
    + [Elections](#elections)

# About Cloud Hypervisor

Cloud Hypervisor is an open source organization and community hosting several
projects aiming at building a modern and innovative cloud virtualization
ecosystem.

# Governance

The Cloud Hypervisor organization is governed according to the
["four opens"](https://governance.openstack.org/tc/reference/opens.html), which
are open source, open design, open development, and open community.

Technical decisions are made by technical contributors and a representative
Architecture Committee.

## Projects

The Cloud Hypervisor organization is composed of several projects, like e.g. the
[cloud-hypervisor](https://github.com/cloud-hypervisor/cloud-hypervisor) or the
[rust-hypervisor-firmware](https://github.com/cloud-hypervisor/rust-hypervisor-firmware)
ones.

A project is the primary unit of collaboration, therefore each project has its
own repository and maintainers team. All projects follow the
[Code of Conduct](CODE_OF_CONDUCT.md).

## Developers

There are two roles relevant to the Cloud Hypervisor projects:

### Contributors

Anyone that contributed to one of the Cloud Hypervisor projects within the
last 12 months is a *Contributor*. Any merged Pull Request is considered a valid
contribution.

Contributions are not limited to code alone. Documentation, tests, tools, project
artifacts are all valuable ways to contribute to a Cloud Hypervisor project.

Project contributions will be reviewed by the project maintainers and should
pass all applicable tests.

### Maintainers

Each project has one or more *Maintainers*. Project maintainers are first and
foremost active *Contributors* to the project and are responsible for:

* Setting technical directions for the project.
* Facilitating, reviewing and merging contributions. They have write access to
  the project repository.
* Creating and assigning project issues.
* Enforcing the [Code of Conduct](CODE_OF_CONDUCT.md)

The list of maintainers for a project is defined by the project
`MAINTAINERS.md` file.

### Becoming a project maintainer

Existing maintainers may decide to elevate a *Contributor* to the *Maintainer*
role based on the contributor established trust and contributions relevance.
This decision process is not formally defined and is based on lazy consensus
from the existing maintainers.

Any contributor may request for becoming a project maintainer by opening an
issue and assigning *all* current maintainers to it.
Maintainers may also pro-actively promote contributors based on their
contributions and leadership track record.

## Architecture Committee

The Architecture Committee is responsible for architectural decisions and
making final decisions if Maintainers for a particular project disagree.
It is comprised of six members, who are elected by Contributors.

The current Architecture Committee members are:

* Liu Jiang       (@jiangliu)      Alibaba
* Liu Wei         (@liuw)          Microsoft
* Michael Zhao    (@michael2012z)  ARM
* Robert Bradford (@rbradford)     Intel
* Samuel Ortiz    (@sameo)         Intel
* Sergio Lopez    (@slp)           Red Hat

### Elections

The Cloud Hypervisor Architecture Committee elections take place yearly, in
April. Three seats are available for renewal at every election.

Any Cloud Hypervisor Contributor can run for a seat and is eligible to vote.
In order to encourage diversity, no more than 2 of the 5 seats can be filled
by any one organization.
