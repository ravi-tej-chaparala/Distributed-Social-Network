# Distributed Social Media Platform

## Project Overview

This project implements a distributed social media platform using both SQL and NoSQL databases. The platform is designed to handle large-scale data efficiently by leveraging distributed systems techniques such as fragmentation, replication, distributed transaction management, and query optimization.

### Key Features
1. **Database Schema**: A distributed schema with tables such as `UserProfile`, `Post`, `Comment`, and `Friendship` to model social media interactions.
2. **Data Fragmentation & Replication**: 
   - **Horizontal and Vertical Fragmentation** to optimize storage and query performance.
   - **Replication** ensures fault tolerance by duplicating data across multiple nodes using a master-slave architecture.
3. **Distributed Transactions**: ACID-compliant transaction management ensures data consistency and integrity across distributed nodes.
4. **Query Optimization**: Techniques such as distributed indexing and query optimization using PostgreSQL enhance performance.
5. **NoSQL Implementation**: MongoDB was used for NoSQL implementation, with features like master-slave replication, CRUD operations, and data distribution to handle posts in the platform.

### Implementation Details
- **Part 1**: Database schema design and data distribution across multiple child databases.
- **Part 2**: Horizontal and vertical fragmentation and replication strategies for scalability and performance.
- **Part 3**: Query optimization and indexing strategies to improve query execution times.
- **Part 4**: Distributed transaction management using ACID principles and concurrency control.
- **Part 5**: Implementation of a NoSQL database system using MongoDB for handling posts with replication and consistency management.

### Technologies Used
- **PostgreSQL**: For SQL-based distributed database implementation.
- **MongoDB**: For NoSQL-based distributed data storage.
- **Apache Ignite**: For distributed transaction management and caching.

### Conclusion
This distributed social media platform ensures scalability, fault tolerance, and high performance through the use of distributed database techniques. By implementing both SQL and NoSQL systems, the platform is well-suited for managing large-scale social media data while maintaining consistency and efficiency.

