![KIX logo](http://www.kixdesk.com/files/layout/logo.png)

# kix-openshift
KIX template for the PaaS platform OpenShift from Red Hat.

KIX is a web-based open source servicedesk. The software is a fork of OTRS 5 created in 2015. The first release was in early 2016. KIX supports your organization in managing and organizing your IT service, technical service, maintenance and repair and customer service.

**PLEASE NOTE**  
At the moment, the Liveness and Readiness probes are missing but will be added in the future. There's a simple bash script `/readiness.sh` in the container which you can use for the Readiness probe.

**FURTHER INFORMATION**  
This template is based on the official docker image for KIX: https://hub.docker.com/r/capeit/kix/.
Please have a look for further information about usage and limitations.
