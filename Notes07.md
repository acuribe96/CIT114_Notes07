Aneissa Uribe

**CIT114 - Notes 07, Storage**

*Amazon Elastic Block Store (EBS)*

- provides persistent block storage volumes
- enables you to create individual storage volumes and attach them to an Amazon EC2 instance

*Object storage*

- entire file must be updates

*Block Storage*

- change one block (piece of the file) that contains the character

*Snapshots*

- point-in-time snapshots
- recreate a new volume at any time

*Elasticity*

- increase capacity

*Volumes*

- persist independetly from the instance

*Amazon Simple Storage (Amazon S3)*

- oject-level storage

*Buckets*


 - logical containers for objects
 - can have multiple in your AWS account

*S3 Pricing*

- 1. Types of storage classes
  2. Amount of storage
  3. Requests
  4. Data transfer

*Amazon ELastic File System (Amazon EFS)*

- a shared file system that uses the Network File System

*Amazon S3 Glacier*

- secure, durable, and low-cost cloud storage service for data archiving and long-term backup

*Amazon S3 lifecycle policies*

- enable you to delete or move objects based on age

**Question 2**

>So you can change from the hard disk drives to solid state drives or increase from a 50 gigabyte volume to a 16 terabyte volume

- It is so easy and quick to change hardware and storage, when before it would take a lot of time and downtime.

>Amazon S3 encrypts each object with a unique key. As an additional safeguard it encrypts the key.

- It fasicantes me how much security is implemented on their applications. Layer after layer.

**Question 4**

- Is it safe to not have an encrypted key, seeing how much security AWS has implemented on their systems?
