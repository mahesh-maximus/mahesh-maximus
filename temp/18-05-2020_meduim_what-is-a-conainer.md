# What is a Container

Containers are a type of operating system virtualization, much like the virtual machines that preceded them. There’s also lesser known types of virtualization such as Application Virtualization, Network Virtualization, and Storage Virtualization. While these technologies have been around since the 1960s, Docker’s encapsulation of the container paradigm represents a modern implementation of resource isolation that utilizes built-in Linux kernel features such as chroot, control groups (cgroups), UnionFS, and namespaces to fully isolated resource control at the process level.

Containers use these technologies to create lightweight images that act as a standalone, fully encapsulated piece of software that carries everything it needs inside the box. This can include application binaries, any system tools or libraries, environment-based configuration, and runtime. This special property of isolation is very important, as it allows developers and operators to leverage the all-in-one nature of a container to run without issue, regardless of the environment it’s run on. This includes developer laptops and any kind of pre-production or production environment.

This decoupling of application packaging mechanism from the environment on which it runs is a powerful concept that provides a clear separation of concerns between engineering teams. This allows developers to focus on building the core business capabilities into their application code and managing their own dependencies, while operators can streamline the continuous integration, promotion, and deployment of said applications without having to worry about their configuration.

At the core of container technology are three key concepts:
* cgroups
* Namespaces
* Union filesystems


[Getting Started with Kubernetes - Third Edition](https://www.oreilly.com/library/view/getting-started-with/9781788994729/7a157169-0cb7-4cf6-ab3b-7fec08693055.xhtml)
