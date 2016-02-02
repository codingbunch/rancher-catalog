# Apache Kafka (Experimental)


### Info:

 This template creates, scale in and scale out a multinodes zk (zookeeper) and broker (kafka) clusters on top of Rancher. The configuration is generated with confd from Rancher metadata. 
 Clusters sizes are variable independently after deployment, and get reconfigured if refresh interval > 0.
 
 
### Usage:

 Select Apache Kafka from catalog. 
 
 Enter the number of nodes, mem and refresh interval for the zk and broker clusters. (set refresh data to 0 to disable dinamic config)
 
 Click deploy.
 
 Kafka can now be accessed over the Rancher network. 

