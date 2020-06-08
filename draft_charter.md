# BGIN Identity & Privacy Enhancement Working Group DRAFT Charter

## 1) Working Group name:
IAM and Privacy Working Group (IPWG)

## 2) Purpose
The goal of IPWG is to provide guidance and good practice documents that describe  

M* Identity (including keys) and Access management for access to crypto-currency exchange; 
* Identity (including keys) and Access management using Blockchain/DLT for Online resource access;
* Privacy considerations to be taken into account for the above. 

Both private and public sector use-cases are to be considered. 

## 3) Scope
### In Scope
The group will document 

### Out of scope:
IDM and Credential Management that does not involve BC or DLT. 

## 4) Proposed Deliverables
The group proposes the following Specification deliverables:



## 5) Anticipated audience or users
The following stakeholders are conceived as the audience of the deliverable of this WG: 

* Crypto-currency Exchanges; 
* Distributed identity management deployers; 
* Management, architects, and implementers of IAM and claims transfer systems for blockchain/DLT access or the system that utilizes blockchain/DLT systems. 

## 6) Language
English

## 7) Method of work:
Online forums and issue tracking system with regular Video meetings and occasional face to face meetings. 

## 8) The basis for determining when the work is completed:
The work will be completed once it is apparent that maximal consensus on the draft has been achieved, consistent with the purpose and scope. Where applicable, it shall have more than three running code that is interoperable. 

# Background information
As we are painfully aware, identity and access management to crypto-currency exchanges 
In many cases, Fintech services such as aggregation services uses screen scraping and stores user passwords. This model is both brittle and insecure. To cope with the brittleness, it should utilize an API model with structured data and to cope with insecurity, it should utilize a token model such as OAuth [RFC6749, RFC6750].

There are some examples of API models such as OFX, but it uses SOAP/XML model. However, SOAP/XML model has grown unpopular among the developers. Also, the OFX does not deploy the token model but uses user password, causing insecurity.

This working group aims to rectify the situation by developing a REST/JSON model protected by OAuth.

## Related work:

## Proposers

## Anticipated contributions:
