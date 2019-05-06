#OpenShift 4
# OpenShift 4

console URL: https://console-openshift-console.apps.openshift4.openshift-sysdig.net/

choose htpasswd auth method

internal OpenShift grafana: https://grafana-openshift-monitoring.apps.openshift4.openshift-sysdig.net/dashboards

##Remember not to install operators or make editing changes, it will break the demo env for other people!

#Grafana using Sysdig metrics provider
URL: https://grafana.sysdig-demo.zone/dashboards

#Jenkins for OpenShift Container Platform

URL: https://jenkins-ocp.sysdig-demo.zone/

One of the pipelines fails the Sysdig Secure scan, so the image never gets uploaded to the internal OpenShift registry
The other pipeline passes all the security scans and the image get into the internal OpenShift registry

