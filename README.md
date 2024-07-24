# FOUND-2025

Spec:

Develop a Java app by using Java17.

Create /helloworld endpoint

With Github actions and helm charts. Publish the Java image to Artifactory 

Deploy the app to foundations-dev

/helloworld should be accessible from  <appname>.foundations-eun1-dev-1.eks.schibsted.io/helloworld and should return a response with “hello back”

Track down the logs in HUMIO and the metric in GRAFANA.


I encourage continuous experimenting after these requirements.

Connecting the app to sqs or dynamodb when deployed

The resources should be created in a new competence building IAC project
