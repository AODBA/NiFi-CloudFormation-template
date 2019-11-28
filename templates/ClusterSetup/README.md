# NiFi-CloudFormation-template


Order of execution should be: 

1 - build-network.yml
    build-registry.yml (not required but nice to have)
2 - build-zookeeper.yml
3 - build-nifi-cluster.yml

Note:
 - review security groups to restrict access. 
