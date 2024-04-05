# Chapter 4 Cloud Data Analytics
# Cloud Storage
* Stores the data in the cloud and supports data operations for various applications such as data search, data analytics, IoT, etc
## Benefits of Cloud Storage
* Accessibility and redundancy
    * Data can be automatically replicated for data backup/recovery
* Elastic Volumes
    * Storage space can be expanded based on demand
* On-demand Pay-Per-Use
    * Can specify storage types, volume, storage duration
* Other service offering
    * Enables other features like data encryption, sync up methods, etc
## Temporary vs Persistant Storage
* ### Temporary Storage
    * Short term storage data stored will be **lost on redeployment**
        * E.g. AWS instance storage
* ### Persistant Storage
    * Data stored will be available through reboots, start/stop, or other lifecycle events
        * AWS EBS
## Examples
![](ImageAssets/Cpt4.1.png)
## Object Storage vs Block Storage
### How to update a file
* ### Object Storage
    * An entire object must be updated
* ### Block Storage
    * Individual blocks can be modified
    