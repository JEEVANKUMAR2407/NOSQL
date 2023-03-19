Masala detail in cassandra
Cassandra is a free and open-source, distributed, wide-column store, NoSQL database management system designed to handle large amounts of data across many commodity servers, providing high availability with no single point of failure. Cassandra offers support for clusters spanning multiple datacenters, with asynchronous masterless replication allowing low latency operations for all clients. Cassandra was designed to implement a combination of Amazon's Dynamo distributed storage and replication techniques combined with Google's Bigtable data and storage engine model.
This Masala schema includes two tables:
        1)powder detail
 The Masala detail table stores information about each masala
                 ... regno text PRIMARY KEY,
                 ... name text,
                 ... mrp int,
                 ... expdate int,
                 ... orgn text
