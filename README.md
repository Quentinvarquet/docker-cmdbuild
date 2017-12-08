
# CMDBuild in Docker (Last version 2.5.0)

![cmdbuild_logo](http://www.cmdbuild.org/logo.png)

### Last update : 07/12/2017 . Add cmdbuild 2.5.0 and update readme
* **From cmdbuild 2.4.0 I will stop adding the docker-compose file with the link option**
* **From 10/2016, I will stop to add the tomcat 6 dockerfiles.**
* **Please open issues on [github](https://github.com/Quentinvarquet/docker-cmdbuild/issues)**

**I recommend to use the latest version of cmdbuild with Tomcat 7**

### You want the last version ?

```bash
docker run --name cmdbuild -p 8080:8080 -d quentinv/cmdbuild:latest
```

### CMDBuild

[CMDBuild](http://www.cmdbuild.org/en) is a web environment in which you can configure custom solutions for IT Governance, or more generally for asset management.

### Docker

[Docker](https://www.docker.com/) allows you to package an application with all of its dependencies into a standardized unit for software development.


### Information

This is the unofficial (updated !) repository with all the versions of cmdbuild. You can choose wich version of tomcat you would like to use for your project.

I will update the repository every time there is a new version of cmdbuild available



### Supported tags and respective Dockerfile links




#### Example

```bash
docker run --name cmdbuild -p 8080:8080 -d quentinv/cmdbuild:t7-2.1.4 
```

* **t7** : Version of tomcat
* **2.1.4** : Version of cmdbuild




#### Tags

**Tomcat 6 with java 8**

** /!\ From cmdbuild 2.4.1, I stopped to add the Tomcat 6 dockerfiles.**

* [```t6-1.4.0.2```](https://github.com/Quentinvarquet/docker-cmdbuild/blob/master/tomcat6-OLD/t6-1.4.0.2/Dockerfile/Dockerfile) | [```t6-1.5.0```](https://github.com/Quentinvarquet/docker-cmdbuild/blob/master/tomcat6-OLD/t6-1.5.0/Dockerfile/Dockerfile) | [```t6-2.0.0```](https://github.com/Quentinvarquet/docker-cmdbuild/blob/master/tomcat6-OLD/t6-2.0.0/Dockerfile/Dockerfile) | [```t6-2.0.3```](https://github.com/Quentinvarquet/docker-cmdbuild/blob/master/tomcat6-OLD/t6-2.0.3/Dockerfile/Dockerfile) | [```t6-2.1.0```](https://github.com/Quentinvarquet/docker-cmdbuild/blob/master/tomcat6-OLD/t6-2.1.0/Dockerfile/Dockerfile) | [```t6-2.1.1```](https://github.com/Quentinvarquet/docker-cmdbuild/blob/master/tomcat6-OLD/t6-2.1.1/Dockerfile/Dockerfile) | [```t6-2.1.2```](https://github.com/Quentinvarquet/docker-cmdbuild/blob/master/tomcat6-OLD/t6-2.1.2/Dockerfile/Dockerfile) | [```t6-2.1.3```](https://github.com/Quentinvarquet/docker-cmdbuild/blob/master/tomcat6-OLD/t6-2.1.3/Dockerfile/Dockerfile)| [```t6-2.1.4```](https://github.com/Quentinvarquet/docker-cmdbuild/blob/master/tomcat6-OLD/t6-2.1.4/Dockerfile/Dockerfile) | [```t6-2.1.5```](https://github.com/Quentinvarquet/docker-cmdbuild/blob/master/tomcat6-OLD/t6-2.1.5/Dockerfile/Dockerfile) | [```t6-2.1.6```](https://github.com/Quentinvarquet/docker-cmdbuild/blob/master/tomcat6-OLD/t6-2.1.6/Dockerfile/Dockerfile) | [```t6-2.1.7```](https://github.com/Quentinvarquet/docker-cmdbuild/blob/master/tomcat6-OLD/t6-2.1.7/Dockerfile/Dockerfile) | [```t6-2.1.8```](https://github.com/Quentinvarquet/docker-cmdbuild/blob/master/tomcat6-OLD/t6-2.1.8/Dockerfile/Dockerfile) | [```t6-2.2.0```](https://github.com/Quentinvarquet/docker-cmdbuild/blob/master/tomcat6-OLD/t6-2.2.0/Dockerfile/Dockerfile) | [```t6-2.2.1```](https://github.com/Quentinvarquet/docker-cmdbuild/blob/master/tomcat6-OLD/t6-2.2.1/Dockerfile/Dockerfile) | [```t6-2.2.2```](https://github.com/Quentinvarquet/docker-cmdbuild/blob/master/tomcat6-OLD/t6-2.2.2/Dockerfile/Dockerfile) | [```t6-2.3.0```](https://github.com/Quentinvarquet/docker-cmdbuild/blob/master/tomcat6-OLD/t6-2.3.0/Dockerfile/Dockerfile) | [```t6-2.3.1```](https://github.com/Quentinvarquet/docker-cmdbuild/blob/master/tomcat6-OLD/t6-2.3.1/Dockerfile/Dockerfile) | [```t6-2.3.2```](https://github.com/Quentinvarquet/docker-cmdbuild/blob/master/tomcat6-OLD/t6-2.3.2/Dockerfile/Dockerfile) | [```t6-2.3.3```](https://github.com/Quentinvarquet/docker-cmdbuild/blob/master/tomcat6-OLD/t6-2.3.3/Dockerfile/Dockerfile) | [```t6-2.3.4```](https://github.com/Quentinvarquet/docker-cmdbuild/blob/master/tomcat6-OLD/t6-2.3.4/Dockerfile/Dockerfile) | [```t6-2.4.0```](https://github.com/Quentinvarquet/docker-cmdbuild/blob/master/tomcat6-OLD/t6-2.4.0/Dockerfile/Dockerfile) | [```t6-2.4.1```](https://github.com/Quentinvarquet/docker-cmdbuild/blob/master/tomcat6-OLD/t6-2.4.1/Dockerfile/Dockerfile)


**Tomcat 7 with java 8**

* [```t7-1.4.0.2```](https://github.com/Quentinvarquet/docker-cmdbuild/blob/master/tomcat7/t7-1.4.0.2/Dockerfile/Dockerfile) | [```t7-1.5.0```](https://github.com/Quentinvarquet/docker-cmdbuild/blob/master/tomcat7/t7-1.5.0/Dockerfile/Dockerfile) | [```t7-2.0.0```](https://github.com/Quentinvarquet/docker-cmdbuild/blob/master/tomcat7/t7-2.0.0/Dockerfile/Dockerfile) | [```t7-2.0.3```](https://github.com/Quentinvarquet/docker-cmdbuild/blob/master/tomcat7/t7-2.0.3/Dockerfile/Dockerfile) | [```t7-2.1.0```](https://github.com/Quentinvarquet/docker-cmdbuild/blob/master/tomcat7/t7-2.1.0/Dockerfile/Dockerfile) | [```t7-2.1.1```](https://github.com/Quentinvarquet/docker-cmdbuild/blob/master/tomcat7/t7-2.1.1/Dockerfile/Dockerfile) | [```t7-2.1.2```](https://github.com/Quentinvarquet/docker-cmdbuild/blob/master/tomcat7/t7-2.1.2/Dockerfile/Dockerfile) | [```t7-2.1.3```](https://github.com/Quentinvarquet/docker-cmdbuild/blob/master/tomcat7/t7-2.1.3/Dockerfile/Dockerfile)| [```t7-2.1.4```](https://github.com/Quentinvarquet/docker-cmdbuild/blob/master/tomcat7/t7-2.1.4/Dockerfile/Dockerfile) | [```t7-2.1.5```](https://github.com/Quentinvarquet/docker-cmdbuild/blob/master/tomcat7/t7-2.1.5/Dockerfile/Dockerfile) | [```t7-2.1.6```](https://github.com/Quentinvarquet/docker-cmdbuild/blob/master/tomcat7/t7-2.1.6/Dockerfile/Dockerfile) | [```t7-2.1.7```](https://github.com/Quentinvarquet/docker-cmdbuild/blob/master/tomcat7/t7-2.1.7/Dockerfile/Dockerfile) | [```t7-2.1.8```](https://github.com/Quentinvarquet/docker-cmdbuild/blob/master/tomcat7/t7-2.1.8/Dockerfile/Dockerfile) | [```t7-2.2.0```](https://github.com/Quentinvarquet/docker-cmdbuild/blob/master/tomcat7/t7-2.2.0/Dockerfile/Dockerfile) | [```t7-2.2.1```](https://github.com/Quentinvarquet/docker-cmdbuild/blob/master/tomcat7/t7-2.2.1/Dockerfile/Dockerfile) | [```t7-2.2.2```](https://github.com/Quentinvarquet/docker-cmdbuild/blob/master/tomcat7/t7-2.2.2/Dockerfile/Dockerfile) | [```t7-2.3.0```](https://github.com/Quentinvarquet/docker-cmdbuild/blob/master/tomcat7/t7-2.3.0/Dockerfile/Dockerfile) | [```t7-2.3.1```](https://github.com/Quentinvarquet/docker-cmdbuild/blob/master/tomcat7/t7-2.3.1/Dockerfile/Dockerfile) | [```t7-2.3.2```](https://github.com/Quentinvarquet/docker-cmdbuild/blob/master/tomcat7/t7-2.3.2/Dockerfile/Dockerfile) | [```t7-2.3.3```](https://github.com/Quentinvarquet/docker-cmdbuild/blob/master/tomcat7/t7-2.3.3/Dockerfile/Dockerfile) | [```t7-2.3.4```](https://github.com/Quentinvarquet/docker-cmdbuild/blob/master/tomcat7/t7-2.3.4/Dockerfile/Dockerfile) | [```t7-2.4.0```](https://github.com/Quentinvarquet/docker-cmdbuild/blob/master/tomcat7/t7-2.4.0/Dockerfile/Dockerfile) | [```t7-2.4.1```](https://github.com/Quentinvarquet/docker-cmdbuild/blob/master/tomcat7/t7-2.4.1/Dockerfile/Dockerfile) | [```t7-2.4.2```](https://github.com/Quentinvarquet/docker-cmdbuild/blob/master/tomcat7/t7-2.4.2/Dockerfile/Dockerfile) | [```t7-2.4.3```](https://github.com/Quentinvarquet/docker-cmdbuild/blob/master/tomcat7/t7-2.4.3/Dockerfile/Dockerfile) | [```t7-2.5.0 (latest)```](https://github.com/Quentinvarquet/docker-cmdbuild/blob/master/tomcat7/t7-2.5.0/Dockerfile/Dockerfile) 


### Docker Compose

I created a docker-compose.yml for every version of cmdbuild. (tomcat + postgresql). 

You can use the following : --link option **(deprecated)** or the network feature (since docker 1.10 and docker-compose 1.6).

#### Docker Compose files

### Links (deprecated)

** /!\  From cmdbuild 2.4.0 I stopped to add the docker-compose file with the link option**

**Tomcat 6 with java 8**


* [```t6-1.4.0.2```](https://github.com/Quentinvarquet/docker-cmdbuild/blob/master/tomcat6-OLD/t6-1.4.0.2/Docker-Compose/Links/docker-compose.yml) | [```t6-1.5.0```](https://github.com/Quentinvarquet/docker-cmdbuild/blob/master/tomcat6-OLD/t6-1.5.0/Docker-Compose/Links/docker-compose.yml) | [```t6-2.0.0```](https://github.com/Quentinvarquet/docker-cmdbuild/blob/master/tomcat6-OLD/t6-2.0.0/Docker-Compose/Links/docker-compose.yml) | [```t6-2.0.3```](https://github.com/Quentinvarquet/docker-cmdbuild/blob/master/tomcat6-OLD/t6-2.0.3/Docker-Compose/Links/docker-compose.yml) | [```t6-2.1.0```](https://github.com/Quentinvarquet/docker-cmdbuild/blob/master/tomcat6-OLD/t6-2.1.0/Docker-Compose/Links/docker-compose.yml) | [```t6-2.1.1```](https://github.com/Quentinvarquet/docker-cmdbuild/blob/master/tomcat6-OLD/t6-2.1.1/Docker-Compose/Links/docker-compose.yml) | [```t6-2.1.2```](https://github.com/Quentinvarquet/docker-cmdbuild/blob/master/tomcat6-OLD/t6-2.1.2/Docker-Compose/Links/docker-compose.yml) | [```t6-2.1.3```](https://github.com/Quentinvarquet/docker-cmdbuild/blob/master/tomcat6-OLD/t6-2.1.3/Docker-Compose/Links/docker-compose.yml)| [```t6-2.1.4```](https://github.com/Quentinvarquet/docker-cmdbuild/blob/master/tomcat6-OLD/t6-2.1.4/Docker-Compose/Links/docker-compose.yml) | [```t6-2.1.5```](https://github.com/Quentinvarquet/docker-cmdbuild/blob/master/tomcat6-OLD/t6-2.1.5/Docker-Compose/Links/docker-compose.yml) | [```t6-2.1.6```](https://github.com/Quentinvarquet/docker-cmdbuild/blob/master/tomcat6-OLD/t6-2.1.6/Docker-Compose/Links/docker-compose.yml) | [```t6-2.1.7```](https://github.com/Quentinvarquet/docker-cmdbuild/blob/master/tomcat6-OLD/t6-2.1.7/Docker-Compose/Links/docker-compose.yml) | [```t6-2.1.8```](https://github.com/Quentinvarquet/docker-cmdbuild/blob/master/tomcat6-OLD/t6-2.1.8/Docker-Compose/Links/docker-compose.yml) | [```t6-2.2.0```](https://github.com/Quentinvarquet/docker-cmdbuild/blob/master/tomcat6-OLD/t6-2.2.0/Docker-Compose/Links/docker-compose.yml) | [```t6-2.2.1```](https://github.com/Quentinvarquet/docker-cmdbuild/blob/master/tomcat6-OLD/t6-2.2.1/Docker-Compose/Links/docker-compose.yml) | [```t6-2.2.2```](https://github.com/Quentinvarquet/docker-cmdbuild/blob/master/tomcat6-OLD/t6-2.2.2/Docker-Compose/Links/docker-compose.yml) | [```t6-2.3.0```](https://github.com/Quentinvarquet/docker-cmdbuild/blob/master/tomcat6-OLD/t6-2.3.0/Docker-Compose/Links/docker-compose.yml) | [```t6-2.3.1```](https://github.com/Quentinvarquet/docker-cmdbuild/blob/master/tomcat6-OLD/t6-2.3.1/Docker-Compose/Links/docker-compose.yml) | [```t6-2.3.2```](https://github.com/Quentinvarquet/docker-cmdbuild/blob/master/tomcat6-OLD/t6-2.3.2/Docker-Compose/Links/docker-compose.yml) | [```t6-2.3.3```](https://github.com/Quentinvarquet/docker-cmdbuild/blob/master/tomcat6-OLD/t6-2.3.3/Docker-Compose/Links/docker-compose.yml) | [```t6-2.3.4```](https://github.com/Quentinvarquet/docker-cmdbuild/blob/master/tomcat6-OLD/t6-2.3.4/Docker-Compose/Links/docker-compose.yml) | [```t6-2.4.0```](https://github.com/Quentinvarquet/docker-cmdbuild/blob/master/tomcat6-OLD/t6-2.4.0/Docker-Compose/Links/docker-compose.yml)


**Tomcat 7 with java 8**

* [```t7-1.4.0.2```](https://github.com/Quentinvarquet/docker-cmdbuild/blob/master/tomcat7/t7-1.4.0.2/Docker-Compose/Links/docker-compose.yml) | [```t7-1.5.0```](https://github.com/Quentinvarquet/docker-cmdbuild/blob/master/tomcat7/t7-1.5.0/Docker-Compose/Links/docker-compose.yml) | [```t7-2.0.0```](https://github.com/Quentinvarquet/docker-cmdbuild/blob/master/tomcat7/t7-2.0.0/Docker-Compose/Links/docker-compose.yml) | [```t7-2.0.3```](https://github.com/Quentinvarquet/docker-cmdbuild/blob/master/tomcat7/t7-2.0.3/Docker-Compose/Links/docker-compose.yml) | [```t7-2.1.0```](https://github.com/Quentinvarquet/docker-cmdbuild/blob/master/tomcat7/t7-2.1.0/Docker-Compose/Links/docker-compose.yml) | [```t7-2.1.1```](https://github.com/Quentinvarquet/docker-cmdbuild/blob/master/tomcat7/t7-2.1.1/Docker-Compose/Links/docker-compose.yml) | [```t7-2.1.2```](https://github.com/Quentinvarquet/docker-cmdbuild/blob/master/tomcat7/t7-2.1.2/Docker-Compose/Links/docker-compose.yml) | [```t7-2.1.3```](https://github.com/Quentinvarquet/docker-cmdbuild/blob/master/tomcat7/t7-2.1.3/Docker-Compose/Links/docker-compose.yml)| [```t7-2.1.4```](https://github.com/Quentinvarquet/docker-cmdbuild/blob/master/tomcat7/t7-2.1.4/Docker-Compose/Links/docker-compose.yml) | [```t7-2.1.5```](https://github.com/Quentinvarquet/docker-cmdbuild/blob/master/tomcat7/t7-2.1.5/Docker-Compose/Links/docker-compose.yml) | [```t7-2.1.6```](https://github.com/Quentinvarquet/docker-cmdbuild/blob/master/tomcat7/t7-2.1.6/Docker-Compose/Links/docker-compose.yml) | [```t7-2.1.7```](https://github.com/Quentinvarquet/docker-cmdbuild/blob/master/tomcat7/t7-2.1.7/Docker-Compose/Links/docker-compose.yml) | [```t7-2.1.8```](https://github.com/Quentinvarquet/docker-cmdbuild/blob/master/tomcat7/t7-2.1.8/Docker-Compose/Links/docker-compose.yml) | [```t7-2.2.0```](https://github.com/Quentinvarquet/docker-cmdbuild/blob/master/tomcat7/t7-2.2.0/Docker-Compose/Links/docker-compose.yml) | [```t7-2.2.1```](https://github.com/Quentinvarquet/docker-cmdbuild/blob/master/tomcat7/t7-2.2.1/Docker-Compose/Links/docker-compose.yml) | [```t7-2.2.2```](https://github.com/Quentinvarquet/docker-cmdbuild/blob/master/tomcat7/t7-2.2.2/Docker-Compose/Links/docker-compose.yml) | [```t7-2.3.0```](https://github.com/Quentinvarquet/docker-cmdbuild/blob/master/tomcat7/t7-2.3.0/Docker-Compose/Links/docker-compose.yml) | [```t7-2.3.1```](https://github.com/Quentinvarquet/docker-cmdbuild/blob/master/tomcat7/t7-2.3.1/Docker-Compose/Links/docker-compose.yml) | [```t7-2.3.2```](https://github.com/Quentinvarquet/docker-cmdbuild/blob/master/tomcat7/t7-2.3.2/Docker-Compose/Links/docker-compose.yml) | [```t7-2.3.3```](https://github.com/Quentinvarquet/docker-cmdbuild/blob/master/tomcat7/t7-2.3.3/Docker-Compose/Links/docker-compose.yml) | [```t7-2.3.4```](https://github.com/Quentinvarquet/docker-cmdbuild/blob/master/tomcat7/t7-2.3.4/Docker-Compose/Links/docker-compose.yml) | [```t7-2.4.0```](https://github.com/Quentinvarquet/docker-cmdbuild/blob/master/tomcat7/t7-2.4.0/Docker-Compose/Links/docker-compose.yml)


### Network

**Tomcat 6 with java 8**

* [```t6-1.4.0.2```](https://github.com/Quentinvarquet/docker-cmdbuild/blob/master/tomcat6-OLD/t6-1.4.0.2/Docker-Compose/Network/docker-compose.yml) | [```t6-1.5.0```](https://github.com/Quentinvarquet/docker-cmdbuild/blob/master/tomcat6-OLD/t6-1.5.0/Docker-Compose/Network/docker-compose.yml) | [```t6-2.0.0```](https://github.com/Quentinvarquet/docker-cmdbuild/blob/master/tomcat6-OLD/t6-2.0.0/Docker-Compose/Network/docker-compose.yml) | [```t6-2.0.3```](https://github.com/Quentinvarquet/docker-cmdbuild/blob/master/tomcat6-OLD/t6-2.0.3/Docker-Compose/Network/docker-compose.yml) | [```t6-2.1.0```](https://github.com/Quentinvarquet/docker-cmdbuild/blob/master/tomcat6-OLD/t6-2.1.0/Docker-Compose/Network/docker-compose.yml) | [```t6-2.1.1```](https://github.com/Quentinvarquet/docker-cmdbuild/blob/master/tomcat6-OLD/t6-2.1.1/Docker-Compose/Network/docker-compose.yml) | [```t6-2.1.2```](https://github.com/Quentinvarquet/docker-cmdbuild/blob/master/tomcat6-OLD/t6-2.1.2/Docker-Compose/Network/docker-compose.yml) | [```t6-2.1.3```](https://github.com/Quentinvarquet/docker-cmdbuild/blob/master/tomcat6-OLD/t6-2.1.3/Docker-Compose/Network/docker-compose.yml)| [```t6-2.1.4```](https://github.com/Quentinvarquet/docker-cmdbuild/blob/master/tomcat6-OLD/t6-2.1.4/Docker-Compose/Network/docker-compose.yml) | [```t6-2.1.5```](https://github.com/Quentinvarquet/docker-cmdbuild/blob/master/tomcat6-OLD/t6-2.1.5/Docker-Compose/Network/docker-compose.yml) | [```t6-2.1.6```](https://github.com/Quentinvarquet/docker-cmdbuild/blob/master/tomcat6-OLD/t6-2.1.6/Docker-Compose/Network/docker-compose.yml) | [```t6-2.1.7```](https://github.com/Quentinvarquet/docker-cmdbuild/blob/master/tomcat6-OLD/t6-2.1.7/Docker-Compose/Network/docker-compose.yml) | [```t6-2.1.8```](https://github.com/Quentinvarquet/docker-cmdbuild/blob/master/tomcat6-OLD/t6-2.1.8/Docker-Compose/Network/docker-compose.yml) | [```t6-2.2.0```](https://github.com/Quentinvarquet/docker-cmdbuild/blob/master/tomcat6-OLD/t6-2.2.0/Docker-Compose/Network/docker-compose.yml) | [```t6-2.2.1```](https://github.com/Quentinvarquet/docker-cmdbuild/blob/master/tomcat6-OLD/t6-2.2.1/Docker-Compose/Network/docker-compose.yml) | [```t6-2.2.2```](https://github.com/Quentinvarquet/docker-cmdbuild/blob/master/tomcat6-OLD/t6-2.2.2/Docker-Compose/Network/docker-compose.yml) | [```t6-2.3.0```](https://github.com/Quentinvarquet/docker-cmdbuild/blob/master/tomcat6-OLD/t6-2.3.0/Docker-Compose/Network/docker-compose.yml) | [```t6-2.3.1```](https://github.com/Quentinvarquet/docker-cmdbuild/blob/master/tomcat6-OLD/t6-2.3.1/Docker-Compose/Network/docker-compose.yml) | [```t6-2.3.2```](https://github.com/Quentinvarquet/docker-cmdbuild/blob/master/tomcat6-OLD/t6-2.3.2/Docker-Compose/Network/docker-compose.yml) | [```t6-2.3.3```](https://github.com/Quentinvarquet/docker-cmdbuild/blob/master/tomcat6-OLD/t6-2.3.3/Docker-Compose/Network/docker-compose.yml) | [```t6-2.3.4```](https://github.com/Quentinvarquet/docker-cmdbuild/blob/master/tomcat6-OLD/t6-2.3.4/Docker-Compose/Network/docker-compose.yml) | [```t6-2.4.0```](https://github.com/Quentinvarquet/docker-cmdbuild/blob/master/tomcat6-OLD/t6-2.4.0/Docker-Compose/Network/docker-compose.yml) | [```t6-2.4.1```](https://github.com/Quentinvarquet/docker-cmdbuild/blob/master/tomcat6-OLD/t6-2.4.1/Docker-Compose/Network/docker-compose.yml)


**Tomcat 7 with java 8**

* [```t7-1.4.0.2```](https://github.com/Quentinvarquet/docker-cmdbuild/blob/master/tomcat7/t7-1.4.0.2/Docker-Compose/Network/docker-compose.yml) | [```t7-1.5.0```](https://github.com/Quentinvarquet/docker-cmdbuild/blob/master/tomcat7/t7-1.5.0/Docker-Compose/Network/docker-compose.yml) | [```t7-2.0.0```](https://github.com/Quentinvarquet/docker-cmdbuild/blob/master/tomcat7/t7-2.0.0/Docker-Compose/Network/docker-compose.yml) | [```t7-2.0.3```](https://github.com/Quentinvarquet/docker-cmdbuild/blob/master/tomcat7/t7-2.0.3/Docker-Compose/Network/docker-compose.yml) | [```t7-2.1.0```](https://github.com/Quentinvarquet/docker-cmdbuild/blob/master/tomcat7/t7-2.1.0/Docker-Compose/Network/docker-compose.yml) | [```t7-2.1.1```](https://github.com/Quentinvarquet/docker-cmdbuild/blob/master/tomcat7/t7-2.1.1/Docker-Compose/Network/docker-compose.yml) | [```t7-2.1.2```](https://github.com/Quentinvarquet/docker-cmdbuild/blob/master/tomcat7/t7-2.1.2/Docker-Compose/Network/docker-compose.yml) | [```t7-2.1.3```](https://github.com/Quentinvarquet/docker-cmdbuild/blob/master/tomcat7/t7-2.1.3/Docker-Compose/Network/docker-compose.yml)| [```t7-2.1.4```](https://github.com/Quentinvarquet/docker-cmdbuild/blob/master/tomcat7/t7-2.1.4/Docker-Compose/Network/docker-compose.yml) | [```t7-2.1.5```](https://github.com/Quentinvarquet/docker-cmdbuild/blob/master/tomcat7/t7-2.1.5/Docker-Compose/Network/docker-compose.yml) | [```t7-2.1.6```](https://github.com/Quentinvarquet/docker-cmdbuild/blob/master/tomcat7/t7-2.1.6/Docker-Compose/Network/docker-compose.yml) | [```t7-2.1.7```](https://github.com/Quentinvarquet/docker-cmdbuild/blob/master/tomcat7/t7-2.1.7/Docker-Compose/Network/docker-compose.yml) | [```t7-2.1.8```](https://github.com/Quentinvarquet/docker-cmdbuild/blob/master/tomcat7/t7-2.1.8/Docker-Compose/Network/docker-compose.yml) | [```t7-2.2.0```](https://github.com/Quentinvarquet/docker-cmdbuild/blob/master/tomcat7/t7-2.2.0/Docker-Compose/Network/docker-compose.yml) | [```t7-2.2.1```](https://github.com/Quentinvarquet/docker-cmdbuild/blob/master/tomcat7/t7-2.2.1/Docker-Compose/Network/docker-compose.yml) | [```t7-2.2.2```](https://github.com/Quentinvarquet/docker-cmdbuild/blob/master/tomcat7/t7-2.2.2/Docker-Compose/Network/docker-compose.yml) | [```t7-2.3.0```](https://github.com/Quentinvarquet/docker-cmdbuild/blob/master/tomcat7/t7-2.3.0/Docker-Compose/Network/docker-compose.yml) | [```t7-2.3.1```](https://github.com/Quentinvarquet/docker-cmdbuild/blob/master/tomcat7/t7-2.3.1/Docker-Compose/Network/docker-compose.yml) | [```t7-2.3.2```](https://github.com/Quentinvarquet/docker-cmdbuild/blob/master/tomcat7/t7-2.3.2/Docker-Compose/Network/docker-compose.yml) | [```t7-2.3.3```](https://github.com/Quentinvarquet/docker-cmdbuild/blob/master/tomcat7/t7-2.3.3/Docker-Compose/Network/docker-compose.yml) | [```t7-2.3.4```](https://github.com/Quentinvarquet/docker-cmdbuild/blob/master/tomcat7/t7-2.3.4/Docker-Compose/Network/docker-compose.yml) | [```t7-2.4.0```](https://github.com/Quentinvarquet/docker-cmdbuild/blob/master/tomcat7/t7-2.4.0/Docker-Compose/Network/docker-compose.yml) | [```t7-2.4.1```](https://github.com/Quentinvarquet/docker-cmdbuild/blob/master/tomcat7/t7-2.4.1/Docker-Compose/Network/docker-compose.yml) | [```t7-2.4.2```](https://github.com/Quentinvarquet/docker-cmdbuild/blob/master/tomcat7/t7-2.4.2/Docker-Compose/Network/docker-compose.yml) | [```t7-2.4.3```](https://github.com/Quentinvarquet/docker-cmdbuild/blob/master/tomcat7/t7-2.4.3/Docker-Compose/Network/docker-compose.yml) | [```t7-2.5.0(latest)```](https://github.com/Quentinvarquet/docker-cmdbuild/blob/master/tomcat7/t7-2.5.0/Docker-Compose/Network/docker-compose.yml)


#### Database configuration

##### Networks

* **Host:** pgsql_container_name
* **Port:** 5432
* **Username:** postgres
* **Password:** your_postgres_password

##### Links

* **Host:** name_of_the_link (**database** in my docker-compose files)
* **Port:** 5432
* **Username:** postgres
* **Password:** your_postgres_password


## Please open issues on [github](https://github.com/Quentinvarquet/docker-cmdbuild/issues)
