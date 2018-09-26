---
services: Monitor
platforms: java
author: hovsepm
---

## Getting Started with Monitor - Security Breach Or Risk Activity Log Alerts - in Java ##


  This sample shows examples of configuring Activity Log Alerts for potential security breach or risk notifications.
   - Create a storage account
   - Setup an action group to trigger a notification to the security teams
   - Create an activity log alerts for storage account access key retrievals
   - List Storage account keys to trigger an alert.
   - Retrieve and show all activity logs that contains "List Storage Account Keys" operation name in the resource group for the past 7 days for the same Storage account.
 

## Running this Sample ##

To run this sample:

Set the environment variable `AZURE_AUTH_LOCATION` with the full path for an auth file. See [how to create an auth file](https://github.com/Azure/azure-libraries-for-java/blob/master/AUTH.md).

    git clone https://github.com/Azure-Samples/monitor-java-activitylog-alerts-on-security-breach-or-risk.git

    cd monitor-java-activitylog-alerts-on-security-breach-or-risk

    mvn clean compile exec:java

## More information ##

[http://azure.com/java](http://azure.com/java)

If you don't have a Microsoft Azure subscription you can get a FREE trial account [here](http://go.microsoft.com/fwlink/?LinkId=330212)

---

This project has adopted the [Microsoft Open Source Code of Conduct](https://opensource.microsoft.com/codeofconduct/). For more information see the [Code of Conduct FAQ](https://opensource.microsoft.com/codeofconduct/faq/) or contact [opencode@microsoft.com](mailto:opencode@microsoft.com) with any additional questions or comments.