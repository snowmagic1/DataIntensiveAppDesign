- scalability
  if your data volume, read or write load grows bigger than a single machine can handle, you can protentially spread the load across multiple machines to handle
- high avaliablility
  if your application needs to continue working even if one machine goes down, you can use multiple machines to give you redundancy. when one fails, another one can take over.
- Latency
  if you have users around the world, you might want to have servers at various location worldwide so that each user can be served from a datacenter that is geographily close to them, that avoid the users have to wait for network packets to travel halfway around the world.
  
- replication
  keeping a copy of same data on different nodes, protentially in different locations. replication provides redundancy - if some nodes become unavaliable, the data can be served from the remaining nodes. replication can also help improve perf.
- partitioning
  spliiting a big dataset into smaller subsets called partitions so that different partitions can be assigned to different nodes.
  
