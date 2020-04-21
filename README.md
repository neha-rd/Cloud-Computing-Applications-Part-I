# Cloud-Computing-Applications-Part-I
## Cloud Computing Applications, Part 1: Cloud Systems and Infrastructure coursera quiz solutions


### Week 1 Introduction
### Week 2 

1. Which type of virtualization is feasible for the following scenario? “A service needs to run an unmodified OS on a basic processor.”

:heavy_check_mark: Full virtualization

Para-virtualization

2. Which type of virtualization is feasible for the following scenario? “A service needs to run an unmodified OS on an advanced processor.”

Para-virtualization

:heavy_check_mark:Hardware-assisted

3. Which type of virtualization provides better performance for the following scenario? “Running multiple independent applications sharing same kernel”

Hardware-assisted full virtualization

:heavy_check_mark:Containers

4. Which type of virtualization provides better performance for the following scenario? “Running two independent applications, each needs a different version of a * same driver (kernel module)”

:heavy_check_mark:Full virtualization
        
Containers

5. Which type of virtualization provides better performance for the following scenario? “Multiple application with high number of threads and high memory usage”
    
:heavy_check_mark:Para-virtualization

Hardware-assisted full virtualization
        Containers

6. Which type of virtualization provides better performance for the following scenario? “Application that is easy to migrate to different hardware and operating * system”

Containers

Hardware-assisted full virtualization

:heavy_check_mark:JVM

7. Which type of virtualization is feasible for the following scenario? “Application that needs different custom operating systems (kernels)”

:heavy_check_mark:Hardware-assisted full virtualization

Para-virtualization

Containers

8. Which type of virtualization provides better performance for the following scenario? “One application running on a single piece of hardware”

:heavy_check_mark:No virtualization

JVM

Full virtualization

Containers

9. Which IaaS technology is more suitable for the following scenario? “Run application on an in-house datacenter”

:heavy_check_mark:OpenStack

Google Compute Engine

Azure

AWS

10. Which IaaS technology is more suitable for the following scenario? “Diverse portfolio of infrastructures”

Azure

OpenStack

:heavy_check_mark:AWS

Google Compute Engine

11. Which PaaS technology is more suitable for the following scenario? “Integration with Microsoft technologies”

OpenStack

:heavy_check_mark:Azure

Google Compute Engine

AWS

12. Which PaaS technology is more suitable for the following scenario? “Application that needs supports for mapping and advertisement”

Azure

AWS

:heavy_check_mark:Google Compute Engine

### Week 3

1. Which technology will address the following need?

“Send requests to a remote object” :arrow_right: CORBA

2. Which technology will address the following need?

“Provides storage backend for web applications” :arrow_right: MBaas

3. Which technology will address the following need?

“Human readable representation of data” :arrow_right: JSON

4. Which technology will address the following need?

“Deploy operating systems on a number of machines”:arrow_right: MAAS

5. Which technology will address the following need?

“Deploy applications on a number of machines”:arrow_right: Juju

6. Which technology will address the following need?

“Create, Update, Read, and Remove objects over the web”:arrow_right: REST

7. Which technology will address the following need?

“Data representation for (un)marshalling on different machines and programming languages” :arrow_right: XML

8. Which technology will address the following need?

“Turn a machine on and off remotely independent of OS”:arrow_right: IPMI

9. Which technology will address the following need?

“Connect to an operating system remotely”:arrow_right: SSH

10. Which technology will address the following need?

“Boot arbitrary operating system (image) over network":arrow_right: PXE

11. Which technology will address the following need?

“Server side computation which maintains no state about clients” :arrow_right: AWS Lambda

12. If a server is going down, which technology can still serve the existing customers?

:arrow_right: MaaS

### Week 4

1. Which storage technology is the best for the following scenario? (HIVE, CEPH, SWIFT)

"An application which needs complicated queries on structured data" :arrow_right: HIVE

2. Which storage technology is the best for the following scenario? (Swift, Ceph, HIVE)

"Application needs to update structured data frequently" :arrow_right: Ceph

3. Which is the best filesystem for Map Reduce applications? (Swift, Dropbox, HDFS) :arrow_right: HDFS

4. Which storage technology is the best for the following scenario? (HDFS, Swift, Ceph)

"Store an operating system and application binaries remotely" :arrow_right: Swift

5. Which storage technology is the best for the following scenario? (AWS S3, Swift, HDFS)

"An application which works with 80 GBs of images on in-house data center" :arrow_right: Swift

6. Which storage technology is the best for the following scenario? (Swift, AWS S3, Instance Store)

"An application which works with 2 TBs of sound files for a few weeks" :arrow_right: AWS S3

7. Which storage technology is the best for the following scenario? (AWS S3, Glacier, Instance Store)

"An application which stores 200 GBs of binary data for a few minutes" :arrow_right: Instance Store

8. Which storage technology is the best for the following scenario? (Glacier, Dropbox, AWS S3)

"An application which archive 2,000 TB of data for a year" :arrow_right: Glacier

9. Which storage technology is the best for the following scenario? (Swift, Dropbox, AWS S3)

"Sync files on a few personal devices" :arrow_right: Dropbox

10. Which storage technology is the best for the following scenario? (AWS S3, Glacier, EFS)

"An application which store and query 2,000 TB of binary data for a few weeks" :arrow_right: EFS

11. Which storage technology is the best for the following scenario? (HDFS, AWS S3, Swift)

"Application distributed on multiple nodes, each node reads a certain set of data frequently" :arrow_right: HDFS

12. Which storage technology is the best for the following scenario? (Local hard disk, HDFS, Instance Store)

"Application runs on a single node, needs to store 10GB of data for a few minutes" :arrow_right: Local Hard Disk
