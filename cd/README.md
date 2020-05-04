#  Continuous Delivery (CD) & Project demo

## 6. CI / CD ... towards DevOps

#### **Advanced Builds**

Multiple Builds because of

* Debug / Release / ReleaseWithDebug (+Obfuscation)
* Free / Commercial / With Extra Feature
* Release per Branch (eg: 1.4 maintenance, 2.0 new release)
* Release per Platform
* Special Builds
    * Coverage
    * Memory / Leak Checking
    * Thread Checking
 
<br>

#### **CI/CD & Automation towards DevOps** - [ci.pdf](../ci/ci.pdf)

* Jenkins https://jenkins.io/

* * *

## 8. Containers and Virtualization

#### **Why to talk about Virtualization?**

* You need the cloud
* But the cloud is complex
   * Rivaling technologies
    * Different ecosystems (sometimes closed)
    * Multiple levels (as Service Models) https://en.wikipedia.org/wiki/Cloud_computing
        * IaaS - Infrastructure as a Service
        * PaaS - Platform as a Service
        * SaaS - Software as a Service
* Lack of understanding the basics
 
<br>

#### **Why to Virtualize?**

* Multiple small (**guest**) machines on one big (**    **) machine controlled and monitored by a program (**hypervisor**)
* Pros
    * Cost saving
    * Energy saving (Green Computing)
    * Easy inspection and control
    * Automated deployment and shutdown
    * Live migration (Uptime)
* Cons
    * Less stable performance
    * Sharing of resources
    * Time sharing (Response Time)

Here, it is not

* Application Virtualization (from Wine to JVM, Mono)
* Virtual Memory
* Emulation (QEMU, DOSBox, VICE)
 
<br>

<br>

#### **Full Virtualization**

* ...also called Hard Virtualization
* Different guest / host opsys
* Not always possibel -> special CPU instruction set needed
* Performance problems
* **Hardware-assisted** virtualization
* **Paravirtualization** (modified guest)
* KVM, Xen, Virtualbox
 
<br>

#### **Operating-system-level Virtualization**

* ...also called **Containerization**
* ...also called Soft Virtualization
* Multiple user spaces separated by the same kernel
    * jails
    * partitions
    * containers
    * virtual environments
* Low overhead
* Knowledgeable allocation of resources (RAM, storage)
* File system isolation (chroot - 1982)
* Copy-on-write storage (union file systems) -> images (like in Docker)
* LXC, OpenVZ, Docker (deliver app?), LXD (deliver machine?)

<br>

#### **Container Orchestration**

...Ansible, Chef, Puppet...

<br>

#### **Docker**

* ...on Windows: Windows container, or Linux with Hyper-V (Full Virtualization)
* Because OS-level-virtualization is so light, put one app in a container
* Flexible and environment-independent configuration and deployment
* https://docs.docker.com/get-started/