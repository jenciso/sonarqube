## Sonarqube Server

![](https://www.sonarqube.org/logos/index/sonarqube-logo-white.png)

### Intro

Provision a sonarqube server via ansible

### Prerequisites

* A host server with 4GB RAM and 2 Vcpus
* docker daemon >= 19.03
* docker-compose >= 1.25

### Installation

* Via ansible

```shell
export SONAR_ADMIN_PASSWORD=mypassword
cd ansible && ansible-playbook -i inventory site.yml
```
> This repository has a `.gitlab-ci.yml` file to automate this process

### Maintenance

Team: Arquitetura
Owner: [Juan Enciso](mailto:juan.enciso@unicred.com.br)
