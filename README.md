# redis-trb
redis-trb.rb of redis v4.0.14 for redis-cluster.  
If you want to use other versions, please modify the redis version number in the dockefile.

Useage:  
docker run --name redis-trb -id redis-trb:4.0.14    
docker exec -ti redis-trb sh  
redis-trib \<command\> \<options\> \<arguments ...\>
