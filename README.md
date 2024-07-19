Deploying a storage account in Azure, specifically a blob type (Azure Blob storage is an object storage solution for the cloud, capable of storing massive amounts of data, such as text or binary data). 

1) First, I go to the home page, click on "Create a resource," select "Storage account" under "Storage" in the left pane of the window, and click on "Create."

2) Then, I configure the storage account I want to deploy.

3) Project details:

3a) I select my subscription, which is Azure Student Subscription to handle my billing, and I created my own resource group named "mygrp" to manage my resources.

4) Instance details:

4a) I name my storage account as "mystorageacc777."

4b) I deploy this storage in the region of East US.

4c) I select the performance as "Standard."

4d) As for redundancy (to replicate data in multiple data centers to ensure high availability in case of a catastrophic disaster or outage), I select "Locally redundant," meaning I create multiple copies of the data in the same datacenter geographically.

5) Advanced settings:

5a) For advanced settings, I check the second box labeled "Allow enabling anonymous access on individual containers," the rest I keep as default.

6) I click on "Review and create," and it displays that my deployment is complete.

7) Now, I navigate to "Resource" and on the same left pane, select "Containers" under "Data Storage." I create a new container and name it "mycont," then click on "Create."

8) Now, my container is successfully created. Upon clicking it, I can upload blobs of data by clicking on "Upload," browsing an image file on my system, and clicking on "Upload." It displays "successfully uploaded."

9) Clicking on the image (blob) and copying its URL in its overview.

10) I paste the URL in the web browser. It's going to display an error due to accessibility settings in the container we created a while ago.

11) I click on "Change access level" from "Private (no anonymous access)" to "Blob (anonymous read access for blobs only)." Click on "OK," and it displays "successfully changed the access level."

12) I changed the access level so I could access my file from the internet. Upon refreshing the previous error-displaying page, my image appears on the display screen.
