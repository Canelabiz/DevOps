# Roadmap/Study path to DevOps

> _"DevOps is a way to deliver software with shared pain and responsibility"_

---

## Table of Contents

* [Foundation](#Foundation)
  * [AWS](#Amazon_Web_Services)
* [Pillars of Real World Skills](#Pillars_of_Real_World_Skills)
  * [Configure](#Configure)
  * [Version](#Version)
  * [Package](#Package)
  * [Deploy](#Deploy)
  * [Run](#Run)
  * [Monitor](#Monitor)
* [Links](#Links)

---

## Foundation layer

Prio|OS|Programming|Cloud service
:-|-|-|-
1|Linux|Python|[AWS](https://aws.amazon.com/)
2||Golang|Google Cloud
3|||Microsoft Azure

---

### [Amazon Web Services](https://aws.amazon.com/)

### [AWS Training & Certification](https://www.aws.training/)

* VPC
* EC2
  * ELB
* IAM
* S3
* CloudWatch
* Security Groups

---

## Pillars of Real World Skills

Prio|Configure|Version|Package|Deploy|Run|Monitor
:-|-|-|-|-|-|-
1|[Terraform](https://www.terraform.io/)|[Git](https://git-scm.com/) + [GitHub](https://github.com/)|[Docker](https://www.docker.com/)|[Jenkins](https://www.jenkins.io/)|[ECS](https://en.wikipedia.org/wiki/Entity_component_system)|[ELK Stack](https://www.elastic.co/what-is/elk-stack)
2|[Ansible](https://www.ansible.com/)|[GitLab](https://about.gitlab.com/)|[Lambda](https://aws.amazon.com/lambda/)|[CodeDeploy](https://aws.amazon.com/codedeploy/)|[Kubernetes](https://kubernetes.io/)|[Prometheus](https://prometheus.io/)
||[Mastering Ansible](https://www.packtpub.com/product/mastering-ansible/9781784395483)||||[Mastering Kubernetes](https://www.packtpub.com/product/mastering-kubernetes/9781786461001)|
||||||[DevOps with Kubernetes](https://www.packtpub.com/product/devops-with-kubernetes/9781788396646)

Book Links

* [Practical Network Automation](https://www.packtpub.com/networking-and-servers/practical-network-automation)
* [Mastering Kubernetes](https://www.packtpub.com/virtualization-and-cloud/mastering-kubernetes)
* [Mastering Ansible](https://www.packtpub.com/virtualization-and-cloud/openstack-administration-ansible-2-second-edition)
* [DevOps with Kubernetes](https://www.packtpub.com/virtualization-and-cloud/devops-kubernetes)
* [Effective DevOps with AWS](https://www.packtpub.com/application-development/effective-devops-aws)
* [Getting Started with Kubernetes, Second Edition](https://www.packtpub.com/virtualization-and-cloud/getting-started-kubernetes-second-edition)
* [Mastering Docker](https://www.packtpub.com/virtualization-and-cloud/mastering-docker-second-edition)
* [OpenStack Administration with Ansible 2](https://www.packtpub.com/virtualization-and-cloud/openstack-administration-ansible-2-second-edition)
* [DevOps for Networking](https://www.packtpub.com/networking-and-servers/devops-networking)
* [Automate it!](https://www.packtpub.com/application-development/automate-it)
* [Puppet 5 Beginner's Guide](https://www.packtpub.com/networking-and-servers/puppet-5-beginner%E2%80%99s-guide-third-edition)
* [Learning Continuous Integration with Jenkins](https://www.packtpub.com/virtualization-and-cloud/learning-continuous-integration-jenkins-second-edition)
* [Continuous Delivery with Docker and Jenkins](https://www.packtpub.com/networking-and-servers/continuous-delivery-docker-and-jenkins)
* [Deployment with Docker](https://www.packtpub.com/virtualization-and-cloud/deployment-docker)
* [Docker and Kubernetes for Java Developers](https://www.packtpub.com/virtualization-and-cloud/docker-and-kubernetes-java-developers)

### Configure

1. Write up the desired infrastructure state in Terraform / Chef / Puppet / Ansible / CFEngine / Salt / CloudFormation / ${whatever},
2. Store it in source code control,
3. Go through a formal pull request process to solicit feedback,
4. Test it,
5. Execute to provision all the resources needed.

### Version

Git

1. Fork a repo
2. Create Branches
3. Merge changes from upstream and back
4. Create Pull Requests

GitHub/GitLab

* Learn git
* Contribute everything you've learned on Git-Hub/Lab
* Leverage #1 and #2 as a showcase of all the things you have learned thus far
* Profit!

[GitOps](https://queue.acm.org/detail.cfm?ref=rss&id=3237207) (?)

### Package

> _"operating system level virtualization"_

* Process isolation
* Deployment
  > Docker allows not only for full preocess isolation but also for full dependency isolation. It is entirely possible and common to have multiple containers running side by side, on the same OS, each with its own and conflicting libraries and packages
* Runtime Management
  > Single, unified management interface that allows us the start, monotor and centralize logs, stop and restart many different kinds of applications

### Deploy

* Jenkins
* AWS CodeDeploy
* GitLab CI
* GitHub Actions

### Run

### Monitor

---

## Links

* [How To Become a DevOps Engineer In Six Months or Less, Part 1: Foundations](https://medium.com/@devfire/how-to-become-a-devops-engineer-in-six-months-or-less-366097df7737)
* [How to Become a DevOps Engineer In Six Months or Less, Part 2: Configure](https://medium.com/@devfire/how-to-become-a-devops-engineer-in-six-months-or-less-part-2-configure-a2dfc11f6f7d)
* [How to Become a DevOps Engineer In Six Months or Less, Part 3: Version](https://medium.com/@devfire/how-to-become-a-devops-engineer-in-six-months-or-less-part-3-version-76034885a7ab)
* [How to Become a DevOps Engineer In Six Months or Less, Part 4: Package](https://medium.com/@devfire/how-to-become-a-devops-engineer-in-six-months-or-less-part-4-package-47677ca2f058)
[How to Become a DevOps Engineer In Six Months or Less, Part 5: Deploy](https://medium.com/@devfire/how-to-become-a-devops-engineer-in-six-months-or-less-part-5-deploy-83e790545c23)
* [The Twelve-Factor App](https://12factor.net/)
* [Terraform](https://www.terraform.io/)
* [Ansible](https://www.ansible.com/)

* [Git](https://git-scm.com/)
* [GitHub](https://github.com/)
* [GitLab](https://about.gitlab.com/)

* [Docker](https://www.docker.com/)
* [Lambda](https://aws.amazon.com/lambda/)

* [Jenkins](https://www.jenkins.io/)
* [CodeDeploy](https://aws.amazon.com/codedeploy/)

* [ECS](https://en.wikipedia.org/wiki/Entity_component_system)
* [Kubernetes](https://kubernetes.io/)

* [ELK Stack](https://www.elastic.co/what-is/elk-stack)
* [Prometheus](https://prometheus.io/)
