## How to set up an AWS AMI


### Step 1: Select an AMI
----
The AMI (Amazon Machine Image) is the environment which your Instance will be instantiated with. For example, if you select the Ubuntu 16.04 AMI, your VM will be preloaded with a Xenial machine.

### Step 2: Select an Instance Type
----
The Instance type you select determines a number of factors about the Instance you create. Thses contain things such as the number of CPUs, the amount of memory it has and the rate of data transfer over the network

### Step 3: Configuring instance details
----
Once you have selected the Instance type, you are then able to configure certain aspects of the instance. This includes things such as configuring the network and subnet the instance will run on. It will also allow you to specify the number of instances you wish to run.

### Step 4: Adding storage
----
This section allows you to specify the storage details for your instance. This includes things such as volume size, volume type and encryption settings.

### Step 5: Adding tags
----
This section allows you to add tags to your instance. These tags will aid in searching for your instance in situations where you have a large number of instances

### Step 6: Configure security groups
----
This section allows you to specify the firewall rules which govern the flow of traffic to and from your instance. This gives you options such as specifying port numbers and protocols.

### Step 7: Review
----
This section allows you to check over all of the options you have previously specified, and go back to sections which you may wish to alter. Once all options are confirmed, you can create your AMI.
