# Compute in cloud

## Amazon Elastic Compute Cloud (Amazon EC2)

- Flexibility in deployment and termination
- Fair pricing module, only pay what you use, both time and capacity

## EC2 Instance Type

### General Purpose

- balanced of all thing
- Equivalent needs of compute, memory, networking
- small, medium database, application server, gaming server

### Compute optimized

- high performance processor for computing power
- high performance web server, gaming server.

### Memory optimized

- Memory intensitve workload that process large dataset in memory
- preloading large dataset into memory for direct access of CPU
- processing a large unstructured data in real time

### Accelerated Computing

- Hardware acceleration and coprocessor. Usually GPU related computing
- gaming application, streaming and application streaming that required GPU intensive task

### Storage Optimized

- High sequential write and read access to large dataset
- suitable for data warehouse, online transaction processing system

## EC2 Pricing on instances

### on-demand

- no upfront cost, only pay for compute time usage
- Most expensive.
- Good for irregular workload that can't be interrupted

### Reserved

- Apply on-demand for fixed period for **1** or **3** year, with 3 years being the greater cost saver

- #### Standard Reserved

  - limited flexiblity, unable to change the instance type
  - suitable for stable workload with predictable usage
  - cheaper than convertible
  - Need to specify **Instance type and size**, **Platform description** and **Tenancy** (default or dedicated) qualification before initialization

- #### Convertible Reserved

  - flexible, allow modification of instance type, platform/OS, tenancy
  - suitable for 