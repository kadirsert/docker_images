Build image:

**docker build -t \<username\>/centos6_cups .**

Start container:

**docker run --privileged -d -p 631:631 --name \<containername\> centos6_cups**
