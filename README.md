# s3-plus-plus
S3++ is a high-performance file storage server that supports file indexing and elastic expansion and contraction.

#Fetures
##Access Layer
Use the standard S3 protocol.

##Control Layer
Use the built-in structured engine to index objects for efficient querying. //like postgresql
Use 1-n structure to achieve high concurrent reading and writing and elastic expansion and reduction. //like es

##Storage Layer
Use mmap technology to achieve low-cost file reading and writing. //like kafka
Compress objects that have not been accessed for more than a threshold.


#Issues to be resolved
How to achieve storage balance and horizontal storage expansion while ensuring file integrity.  **IMPORTANT
