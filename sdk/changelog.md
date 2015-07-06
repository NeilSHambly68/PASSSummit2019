## Changes in 1.2.0 : ##
- Changes to support Order By
  - Support for string range indexes
    Allows you to do range operations on string fields. Like WHERE c.stringfield > "something"
    
  - Breaking change in IndexingPolicy to support Order By
    If you have existing code that provisions collections with a custom indexing policy then your existing code will need to be updated to support the new IndexingPolicy class
    If you have no custom indexing policy, then this change does not affect you. 
   
  - LINQ provider support for OrderBy() or OrderByDescending()
  
## Changes in 1.1.0 : ##
- Support for partitioning data by using the new HashPartitionResolver and RangePartitionResolver classes and the IPartitionResolver
- DataContract serialization
- Guid support in LINQ provider
- UDF support in LINQ

## Changes in 1.0.0 : ##
- GA SDK