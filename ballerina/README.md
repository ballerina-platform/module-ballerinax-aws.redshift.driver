## Overview

The AWS Redshift driver provides a reliable and high-performance connectivity to Amazon Redshift data warehouses. It enables efficient execution of SQL queries, updates, and other database operations. The driver is designed to provide a seamless experience for interacting with AWS Redshift, supporting various data types and advanced features of the data warehouse.

### Key Features

- High-performance and reliable database connectivity
- Support for various SQL operations (Query, Execute, Batch)
- Efficient handling of database connections and resources
- Support for database-specific data types and features
- Secure communication with TLS and authentication
- GraalVM compatible for native image builds

## Compatibility

| |   Version    |
|:---|:------------:|
|Ballerina Language | **2201.8.0** |
|Ballerina Language | **2201.11.0** |
|AWS Redshift Driver | **2.1.0.32** |

> The above AWS Redshift drivers are released under the [Apache License 2.0](https://github.com/aws/amazon-redshift-jdbc-driver/blob/master/LICENSE).

## Usage

To add the AWS Redshift driver dependency the project, simply import the module as below,

```ballerina
import ballerina/sql;
import ballerinax/aws.redshift;
import ballerinax/aws.redshift.driver as _;
```

# Useful Links
* Chat live with us via our [Discord server](https://discord.gg/ballerinalang).
* Post all technical questions on Stack Overflow with the [#ballerina](https://stackoverflow.com/questions/tagged/ballerina) tag.
