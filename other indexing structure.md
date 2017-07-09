reference by primary key in other records
secondary index

## storing values within the index
cluster/non-cluster/covering

## multi column index
- concatenated index
- r tree

## full text search and fuzzy index

## keep everything in memory
the data structures discussed have all been answers to the limitation of disks, 

counterintuitively the performance advantage of in memory databases is not due to the fact that they don't need to read from disk,even a disk based storage doesn't need to read from disk if you have enough memory, because the OS caches the recent used disk block in memory anyway, rather they can be faster because they can avoid encoding data structure in memory in a form that can be written to disk.

