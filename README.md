# redis-trb
redis-trb.rb of redis v4.0.14 for redis-cluster.  
If you want to use other versions, please modify the redis version number in the dockefile.

### Useage:  
docker run --name redis-trb -id redis-trb  
docker exec -ti redis-trb bash  
redis-trib \<command\> \<options\> \<arguments ...\>

### Examples:  
redis-trib.rb create --replicas 1 10.254.3.102:7001 10.254.3.103:7002 10.254.3.118:7003 10.254.3.102:6001 10.254.3.103:6002 10.254.3.118:6003
