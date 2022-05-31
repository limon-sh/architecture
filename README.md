# Architecture solution

## Introduction

Modern information systems consist of many components that require 
their maintenance and support.

An important part of supporting such systems is monitoring. 

[Monitoring][1] is obtaining information about the state of the system 
and, in particular, information about the use of server resources by 
the system.

Such information is extremely important, since the presence of a 
software error in one of the parts of the system is not as critical 
as the inaccessibility of the entire system.

The problem is that at the moment monitoring systems for small and 
medium-sized companies are quite expensive, difficult to maintain and 
support. Large open source or proprietary monitoring systems are 
[quite difficult][2] to set up and use.

As a solution, it is required to develop a monitoring system that is 
extremely easy to use and maintain.

### Purpose of this document

This document describes the architectural solution of the developed 
monitoring system.

Also in this document, the selected technologies for the 
implementation of the system are described and approaches to the 
development of this system are outlined.

However, this document **does not** describe the functional or 
non-functional requirements for the system. This documentation can 
be found at [this link][3].

### Glossary

- **Organization** - entity to combine products and manage them
- **Product** - entity to combine related projects
- **Project** - entity to combine related resources (machines and 
clusters)
- **Cluster** - entity for the logical association of machines
- **Machine** - minimum logical entity to collect monitoring data
- **Collector** - service for collecting monitoring data from agents
- **Agent** - software for collecting data directly on physical 
machines

### Document organization ???

## Conceptual solution

### Case view

### Logical view

### Process view

### Deployment view

### Implementation view

[1]: https://en.wikipedia.org/wiki/System_monitor
[2]: https://thenewstack.io/will-grafana-become-easier-to-use-in-2022/
[3]: https://github.com/limon-sh/documentation
