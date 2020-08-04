# Solution Design Demonstration

## Why this design
I would like to demonstrate my ability to learn, adopt company technology and well understand the design principle of adopted platform.

## Background and context of the solution design
This is a replatform and rearchitecure solution to move SAP ITOA into SAP Cloud Platform under SAP HANA toolings. 
SAP ITOA originated as a monolith on-premise product providing SAP HANA monitoring and operation capabilities. The whole product contains various parts, including:
* Monolith analytics application.
* Data Collector application
* etc

The scope of this design document is focusing on moving the data collector components as managed service to SAP cloud platform.

## Solution focus:
* serice scalability
* adoption of SAP Cloud platform, XSA technology and cloud managed service design principle.

## Outcome and impact
* A POC has been developed
* service scalbility confirmed
* multi-tanant support
* automate data collector provisioning

## Solution architect

![Solution architect diagram](images/Adapter-XSA-Service-Design.jpg)


