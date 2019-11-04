
# Javier Fontán Muiños

## Profile

* **Birth date**: August 8th, 1979
* **Email**: jfontan@gmail.com
* **GitHub**: jfontan
* **Path**: /Spain/Madrid

I'm an energetic geek that likes to tinker with technology. Since young I found that I liked graphics programming but as time went by I moved to systems. One of the things I like the most is making tools to automate or manage things, as you will find in the experience section.


## Experience

**2019 - Lead Software Developer, Source{d}, Madrid, Spain**

The data retrieval team was split in two at the start of 2019 and I was appointed lead if it. We had to implement new tools to download and archive git repositories in a more efficient way. These are the projects we've been working on:

* go-borges: Git storage layer that supports transactions, snapshots and repository deduplication. This was used by both the downloader and the git repository processor. This layer made possible to update repositories while they were being processed and stored repository forks in an efficient way transparent to software using it. https://github.com/src-d/go-borges
* gitcollector: Software to download all repositories from GitHub organizations. It uses go-borges as its storage layer and detects forks using the initial commit. For repository discovery it uses the GitHub API to retrieve the list of all the organization repositories. https://github.com/src-d/gitcollector
* data-retrieval: Spiced up version of gitcollector. This is a client / server application that can be deployed in several computers to download repositories. It is meant to be used with several big organizations. It does data distribution between nodes and disks and maintains snapshots of updates to be able to access data in a coherent way. This project is private to the company.

**2017-2018 - Senior Software Developer, Source{d}, Madrid, Spain**

As a member of data retrieval team I helped maintaining and creating several projects to download and extract insights from a pool of git repositories. Part of my duties were improving performance to some of our software. Some projects I've been involved in:

* go-git: Library to deal with git repositories. https://github.com/src-d/go-git
* borges: Tool to download and archive public repositories. https://github.com/src-d/borges
* gitbase: SQL interface to git repositories. https://github.com/src-d/gitbase
* go-billy: Filesystem abstraction. https://github.com/src-d/go-billy
* go-billy-siva: Filesystem over an append only archive, used to store repositories. https://github.com/src-d/go-billy-siva

Aside from the pure development work I've been helping on setting to work them in production in our Kubernetes infrastructure.

**2010-2017 - Founder/Engineer, OpenNebula Systems, Madrid, Spain**

I am one of the founders of the OpenNebula Systems Company. This company develops and gives commercial support for OpenNebula Open Source project. This is a small company and I have a wide spectrum of roles:

* Software development:
  * Command line interface
  * General driver development (the part of the software that glues the main daemon with the underlying technology)
  * Ruby API
  * Virtual Machine drivers (KVM, Xen and vCenter)
  * Storage drivers (plain files, qcow2, gluster and lvm)
* Software packaging:
  * Description files for each distribution packages
  * Ruby gems installation scripts
* Testing infrastructure:
  * Jenkins jobs configuration
  * Glue scripts to spin up micro environments where to run tests
  * Ansible playbooks to configure the micro environments
* Installation of OpenNebula in customer's infrastructure
* Provide support in the customer's ticketing systems
* Give tutorials and speeches to customers or the community
* Community engaging

**2007-2013 - Distributed Systems Researcher, Complutense University, Madrid, Spain**

My role there started as developer of a grid computing tool (GridWay) and System Administrator of the Distributed Systems Architecture group clusters.

Early in my stay, we also started researching and developing OpenNebula, a Virtual Machine manager (initially KVM and Xen) that enables people to create IaaS type clouds. I'm one of the three developers that created this software (http://opennebula.org). Some of the tasks done for this project were:

* Development of the ruby library used to communicate external components with the main daemon
* Creating the build system for the project using scons build tool
* Base driver engine that spawns remote actions when needed
* Transfer manager, clone, link, delete VM images
* VM manager, manage VMs in KVM and Xen

**2004-2006 - Grid Technician, CESGA, Santiago de Compostela, Spain**

Contracted by a European Funded research project called EGEE (Enabling Grids for E-science) I assumed the role of Systems Administrator of our grid machines. I deployed and maintained grid infrastructure in our site and also global monitoring and web collaboration tools.

**2001-2004 - Systems Technician, CESGA, Santiago de Compostela, Spain**

My roles at CESGA (Galicia Supercomputing Center) were maintaining UNIX clusters destined to Scientific research and helping the rest of the technical staff with Linux and programming matters. During my stay there I supervised the rendering of a CGI film, started a protein visualization program using OpenGL, optimizing of applications for speed, Systems Administration and R&D in Grid technologies. I also took part in a european funded grid project called CrossGrid where we worked on making interactive and parallel programs run in grid environment where I assisted and participated in various conferences and work meetings.


## Education

**1999-2001 - Systems Administration, Vocational Education, IES Chan do Monte, Spain**

I studied Systems Administration in a Technical School but most of my technical knowledge was self-taught.

**1989-1999**

Started programming Basic in a Spectrum at the age of 9 and later in Pascal and x86 Assembly programming at the age of 14.


## Skills

* Programming:
  * Go
  * Ruby
  * Shell Scripting
* System Administration level in Linux
* Basic Kubernetes usage and Helm charts creation
* Languages:
  * Galician - Native
  * Spanish - Native
  * English - Fluent
  * Portuguese - can read and understand it


## Projects

* [Cangallo](https://github.com/jfontan/cangallo). A tool to create and manage Virtual Machine images in qcow2 format. It also allows you to create a repository similar to docker where an image is composed of deltas.

* Server code for [glslsandbox](http://glslsandbox.com/). A shading language editor and gallery.


## Hobbies

* I am now learning go and crystal as I want to go back to lower level systems programming. These last years I've been mainly using ruby and shell script glue code.

* From 1995 to 2005 I've been into the [demoscene](https://en.wikipedia.org/wiki/Demoscene) as programmer and musician. I did a lot of graphics programming but the part that I liked the most was programming low level: at first doing libraries to interact with the peripherals like graphics or sound cards and later doing asm optimization.






