## Accessing the Cluster Portal and what it's used for

The cluster portal is a location where a dedicated admin has access to view high level information about all the OpenShift Dedicated clusters they own. 

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

5. More metrics will be displayed as in the below images

![Cluster Details](/images/ClusterDetails1.png)
![Cluster Details](/images/ClusterDetails2.png)

6. Information is presented about core usage, memory, storage, node names, OpenShift version, Docker version, etc..

7. You will also see links to core parts of the cluster such as the Web Console, Logs, API, and Registry.

![Cluster Links](/images/ClusterPortalLinks.png)

8. At the bottom there are also sections for seeing if any subscriptions will be expiring soon as well as any upcoming maintenance events.

![Cluster Sub Maint](/images/ClusterSubMaint.png)
