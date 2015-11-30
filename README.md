<a href="well.io"><img src="https://cloud.githubusercontent.com/assets/818400/11470748/ef5d4c34-9768-11e5-8efc-bff92f837e4d.png" alt="Well" /></a>

___

#Well - Artifical Ingtellegence CMS

Well is a radically simple API-Driven CMS. It handles configuration-management, application deployment, cloud provisioning, ad-hoc task-execution, and multinode orchestration - including trivializing things like zero downtime rolling updates with load balancers.

Read the documentation and more at https://well.io/

Many users run straight from the development branch (it's generally fine to do so), but you might also wish to consume a release.

You can find instructions here for a variety of platforms. If you decide to go with the development branch, be sure to run git submodule update --init --recursive after doing a checkout.

If you want to download a tarball of a release, go to releases.ansible.com, though most users use yum (using the EPEL instructions linked above), apt (using the PPA instructions linked above), or pip install ansible.

#Background

Current needs of CMS systems and it's old. We see so many small startups filling this niche, but we don't see stable product to fill up this niche.

#Proposal

#Design Principles

* Realtime editing


* Manage machines very quickly and in parallel
* Avoid custom-agents and additional open ports, be agentless by leveraging the existing SSH daemon
* Describe infrastructure in a language that is both machine and human friendly
* Focus on security and easy auditability/review/rewriting of content
* Manage new remote machines instantly, without bootstrapping any software
* Allow module development in any dynamic language, not just Python
* Be usable as non-root
* Be the easiest IT automation system to use, ever.

# Marketplace

Well marketplace will be fieled with. Well will act as central point of integrating services directly into your app. This means services as Analytics, Filepicker.io adn etc.

##Modules

Auto content filler
Visotor detection and auto integration with 3rd party CRMs

####AUTOMATED A/B TESTING


#Architecture

The Wll be written in Go Lang ( https://golan.org ).

It will consist witht he following components:


## The Reactor
![The Reactor ](https://cloud.githubusercontent.com/assets/818400/11320976/b7a44bca-90b6-11e5-9e00-7d3bcd9e163d.jpg "Well Reactor")


The reactor is the main power of well.

## Fuel
![Fuel ](https://cloud.githubusercontent.com/assets/818400/11470627/0aa6f950-9768-11e5-9e73-2169bdff7990.png "Well Fuel")

This is the component which is API interface of __Well__

## Control Room
![Control Room ](https://cloud.githubusercontent.com/assets/818400/11470632/11abf0ac-9768-11e5-9a3d-65fd1cd16a76.png "Control Room")

This is the UI interface

#Authors
Ansible was created by Jordan Dim and has contributions from over 1000 users (and growing). Thanks everyone!

#Support us

Please, contributed



#License

Copyright (c) 2013-2016 Well Foundation - Released under the [MIT license](LICENSE).

