# Devops-Tech-talk : CHEF
---------------
Team Members:
----
- Ashwin Bharadwaj Lakshmi Venkataramanan (alakshm6)
- Gaurav Aradhye (garadhy)
- Stuti Nanda (snanda)

#About the Tool:
-----------

Chef is a Configuration Management tool which automates how the infrastructure is configured, deployed and configured across networks on machines which could be physical, on cloud or virtual. The use of such a tool helps in ensuring that the files, softwares, packages and services are present on the respective machines and are working as required.  
  
The need for such tool arises from the fact that the real world applications require management of multiple server machines each performing a different function. Manual management of operations and configuration in such an environment can be a daunting task and hence this calls for tools like Chef which provide Infrastructure as Code.

## What is chef?

- Library for configuration management
- Configuration management system 
- System integration platform 
- An Api 

##Some links: 
- [Chef](https://www.chef.io/chef/)
- [Tutorials](https://learn.chef.io/tutorials/)

#Key Features:
------------
-
-
-
-


#Advantage
-------------
Chef is an established community with a good user base contributing to the community. This makes it easier for navigating through any related issues. Furthermore, chef recipes can be shared, for example, a recipe for deploying LAMP stack could be shared on the marketplace and someone looking for LAMP stack could pick it up and use it for their use case. It has weathered a lot since its inception and hence is technologically more mature than many CM alternatives.  

Chef is Idempotent and hence any un-intended changes made to the nodes can be fixed within a short span, which happens using the pull mechanism, wherein it observes a difference between the contents on the server and on the node and fetches the server copy.

# Disadvatage:
--------------
The biggest disadvantage Chef poses for people adopting it newly is the learning curve it has in learning Ruby. Chef requires writing out the recipes in Ruby and hence non-developers might not find it an easy adoption. Chef has a complex environment and in comparison to Ansible it seems pretty bulky in performing the same tasks. Although, the pull mechanism and idempotence form a good feature, enough damage could be inflicted when the time period for successive pull's is high. In addition to that, sometimes a change on the server will not lead to immediate change on the nodes owing to the absence of push mechanism and hence there is a lag between deploying something to the chef server and the same being reflected on the nodes.  

#Our Take/verdict:
--------------
Adoption of such tools is always very use case specific and as we have observed throughout our experience with Chef, it is a tool which could be used when someone has a good experience with programming, a plus if Ruby is known, and the use case requires managing a complex infrastructure which could require support through online community. In addition to that Chef provides idempotence and hence presence of multiple users and possibly some of them having access to nodes directly could prevent the distortion of configuration by way of ensuring consistency with chef server. Also that chef market place has multiple recipes available online which could be plugged in to the requirements and hence reduce time of development.
But if the use case is pretty simple with not much of a infrastructure to manage and if the infrastructure management is done by sysadmins then Ansible being a light weight tool might be a better option.


#Installation Instructions:
--------------


# Simple Example
-----------------
The following are the links to the sample example:


#DEMO
--------------
#### Screencast

![DEMO Screencast](link)
