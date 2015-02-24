jenkins
====

The jenkins image runs [Jenkins](http://jenkins-ci.org/) on top of the
[jleight/phusion-java](https://github.com/jleight/docker-phusion-java)
container.


Usage
-----

You can get a simple Jenkins container up and running by using the following
command:

```bash
$ docker run
  --name jenkins \
  -p 0.0.0.0:8080:8080
  jleight/jenkins
```