# weblogic-operator-scalling
this repo contains all to bring up the autoscalling solution for weblogic operator 3.
this repo has :
-  Prometheus adapter, this helmchart has the configuration used to scale my cluster (i used prometheus adapter to get the metrics but not to scale, because prometheus adapter only works with replicaset , replication controller, deployments ,ettc not with kinds "DOMAIN" )
- An helmchart called scalling-adapter , this helmchart is very important , because in this helmchart i am going to deploy de image provided in the past step.
- wls-exporter.war 

