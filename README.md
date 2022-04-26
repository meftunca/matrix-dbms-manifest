# matrix-dbms-manifest
Matrix data storage manifest based on ((a,b),(c,d)) where each data pairs with subdata blocks in all index probability.


Over time, databases deviate from desired features and performance. Any action to remedy this situation will one day turn primitive techniques into a costly deception to advance. As a result, I am sharing the manifesto of a data management system that has been re-planned beyond the techniques and developments made in the past, is dependent on the development of humanity, and will respond to all kinds of needs in line with endless possibilities.

Before we move on to the manifesto, we need to talk about the problems. These problems are:
- Inability to use large chunks of data as desired
- Preventing data integrity as a result of central data storage insistence
- Inability to collect required data for IoT and AI as desired
- Expensive data storage and lack of parallel data flow
- Unpredictable query times
- Indexing and searching slowness of 2D databases
- And the sub-titles of these titles...

# What is the Matrix Database model?

Simply put, a matrix database (n to n) over (n to n)... is a data structure that is the result of properly parallel clustering of infinite data blocks. It should be noted that the value of n is not an estimated value. The length of strings parallel to the data block derived by the system based on the data. Each block represents a submatrix containing subblocks. And indexed data structures are available in blocks.

## Constants

### Cluster:
Clusters are systematic portals containing hierarchical data blocks. The purpose of these portals is to make data transactions quickly thanks to double-sided transitions. In this way, high-function querying can be made based on a timeless or timed calculation of the upstream and downstream flow. Clusters can recursively repeat themselves in the blocks under them, thanks to portals.

### Portal:
Up and down data ports for fast switching between datasets, blocks, and indexes. Their purpose is to establish data connections as the basis for fast data flow and, if necessary, to support augmentation functions as an intermediary. With this acquisition, databases can create temporary clusters by providing the desired transformations.

### Block:
Blocks can actually be compared to collections in NoSQL or tables in SQL. However, the important difference here is that it can be connected with non-kinship upper blocks. This feature indicates that evolution of uniq data blocks into computed temporary blocks can be achieved. In this case, each block indicates that other blocks can be both a parent and a child, and can also manifest itself in a different form as a result of the request.
