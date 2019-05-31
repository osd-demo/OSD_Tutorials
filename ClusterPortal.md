# OpenShift Dedicated Cluster Portal


The OpenShift Dedicated Portal can be accessed at https://dedicated.openshift.com using a Red Hat account. A designated admin can manage users that have access to specific cluster dashboards and data.
The OpenShift Dedicated Portal provides the following:
- A cluster overview for all OpenShift Dedicated clusters owned by a single customer.
- A cluster dashboard for each OpenShift Dedicated cluster, containing cluster usage information, cluster component lists, node status and usage, and subscription information.
- A user management section, where an admin can add, edit, and remove users who can access the OpenShift Dedicated Portal or individual cluster dashboards.
- A maintenance scheduling section, where admins can select or modify maintenance windows for planned upgrade and maintenance events.

The OpenShift Dedicated Portal is also used by Operations for change management. All maintenance events are scheduled and logged through the Portal, and the event log is available for audit at any time.

## Accessing the Cluster Portal and what it's used for

1. Go to https://dedicated.openshift.com

2. Click "Log in with Red Hat" and proceed to enter in your credentials

![Cluster Portal](/images/ClusterPortalLogin.png)

3. Once logged in you will see all the clusters assocaited with your account as well as some high level metrics about the resources each cluster has:

- Total vCPU
- Total RAM
- Total Storage
- Total Network Quota

![Clusters Available](/images/ClustersAvailable.png)

4. Click on one of the cluster tiles to get a more detailed view of that clusters metrics.  Then click on one of the top tiles stating one of the node statistics.  This will bring a dropdown showing you the correct CLI command to use to get this value.

![ClusterInfoCommand](/images/ClusterInfoCommand.png)

5. Information is presented about core usage, memory, storage, node names, OpenShift version, Docker version, etc..

![Cluster Details](/images/ClusterDetails1.png)
![Cluster Details](/images/ClusterDetails2.png)

6. You will also see links to core parts of the cluster such as the Web Console, Logs, API, and Registry.

![Cluster Links](/images/ClusterPortalLinks.png)

7. At the bottom there are also sections for seeing if any subscriptions will be expiring soon as well as any upcoming maintenance events.

![Cluster Sub Maint](/images/ClusterSubMaint.png)
