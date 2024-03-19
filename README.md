WIP demonstrating different ways to install operators using OLM.

Current examples:

1. All-In-One deployment with namespace, operatorgroup, subscription and custom resource in one Application
2. App-of-App that splits namespace, operatorgroup and subscription into one Application and the custom resource in a second orchestrated by App-of-Apps
3. Another App-of-App but deploying multiple operators, one Application deploys the namespace and operatorgroup, the remainder deploy the operators
