---
title: Apache Aries
subtitle: The Aries project consists of a set of pluggable Java components enabling an enterprise OSGi application programming model.
layout: page
---

# Apache Aries

The Aries project consists of a set of pluggable Java components enabling
an enterprise OSGi application programming model. This includes
implementations (and extensions) of the following Enterprise OSGi specifications:

  - [**Asynchronous Services**](https://osgi.org/specification/osgi.enterprise/7.0.0/service.async.html) and [**Promises Specification**](https://osgi.org/specification/osgi.enterprise/7.0.0/util.promise.html)
  - [**Blueprint Specification**](https://osgi.org/specification/osgi.cmpn/7.0.0/service.blueprint.html)
  - [**CDI Integration Specification**](https://osgi.org/specification/osgi.enterprise/7.0.0/service.cdi.html)
  - [**JAX-RS Whiteboard Specification**](https://osgi.org/specification/osgi.enterprise/7.0.0/service.jaxrs.html)
  - [**JMX Management Model Specification**](https://osgi.org/specification/osgi.enterprise/7.0.0/service.jmx.html)
  - [**JNDI Services Specification**](https://osgi.org/specification/osgi.enterprise/7.0.0/service.jndi.html)
  - [**JPA Service Specification**](https://osgi.org/specification/osgi.enterprise/7.0.0/service.jpa.html)
  - [**JTA Transaction Services Specification**](https://osgi.org/specification/osgi.enterprise/7.0.0/service.jta.html)
  - [**Push Stream Specification**](https://osgi.org/specification/osgi.enterprise/7.0.0/util.pushstream.html)
  - [**Remote Service Admin Service Specification**](https://osgi.org/specification/osgi.enterprise/7.0.0/service.remoteserviceadmin.html)
  - [**Service Loader Mediator Specification**](https://osgi.org/specification/osgi.enterprise/7.0.0/service.loader.html)
  - [**Subsystem Service Specification**](https://osgi.org/specification/osgi.enterprise/7.0.0/service.subsystem.html)
  - [**Transaction Control Service Specification**](https://osgi.org/specification/osgi.enterprise/7.0.0/service.transaction.control.html)

The specifications are defined in the OSGi Alliance Enterprise Expert Group (EEG) for deployment to a variety of OSGi
based runtimes. The OSGi R7 Enterprise Specification can be found here:

[OSGi Enterprise Release 7](https://osgi.org/specification/osgi.enterprise/7.0.0/)

## Additional projects

Additionally, Apache Aries provides the following projects:

  - **Component DSL** - an embedable, micro, functional-style component DSL for working with OSGi services and configuration
  - **Container Management** - API and implementations of the Apache Aries Container Management subcomponent
  - **Proxy** - a library for working with object proxies in OSGi
  - **Util** - a library containing reusable bits of functionality in OSGi


To understand the complete scope of the Aries project, see the Aries
proposal document on the [incubator wiki](http://wiki.apache.org/incubator/AriesProposal).

<a name="Index-BuildingandUsingAriesComponents"></a>

To understand how to _use_ Aries Blueprint components, take a look at the [BlueprintHelloWorldTutorial](documentation/tutorials/blueprinthelloworldtutorial.html)
 pages which guides you through how to build the Aries code, provides
sample applications and describes how to set up an environment in which to
run the consuming application.
