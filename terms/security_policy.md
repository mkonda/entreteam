---
layout: terms
permalink: security_policy.html
title: "SecuritySignal.io Security Policy"
---

Last Updated:  11/6/2018

## SecuritySignal.io Security Policy 

SecuritySignal.io is built by Jemurai.  Jemurai has the following open, published security policies that apply across the firm including the teams building and supporting SecuritySignal.io:  [https://github.com/jemurai/policy](https://github.com/Jemurai/policy).  

This policy set includes the following: 

* Privacy Policy
* Asset Management Policy
* Identity and Access Management Policy
* Acceptable Use Policy
* Data Classification, Confidentiality and Encryption Policy
* Network Security Policy
* Application Security Policy
* Systems Security Policy
* Partner Security Policy
* Physical Security Policy
* Business Continuity Policy
* Risk Assessment and Management Policy
* Incident Response Policy

## SecuritySignal.io Specific Security Policy

In addition to the above policies, SecuritySignal.io has some specific data security requirements that we can provide specific security policy direction for.

### SecuritySignal.io Data Protection

The SecuritySignal.io system contains data that we consider the highest tier of criticality per our Data Classification Policy.  Specifically, all of the following are considered SECRET and must be encrypted at rest and in transit.
1. User's passwords
1. Client AWS credentials
1. SecuritySignal.io client encryption keys

This explicitly means that: 
* All communication to SecuritySignal.io must be over TLS (HTTPS)
* All databases are encrypted
* Any transmission of client credentials is encrypted with a client specific key
* All encryption is reviewed by industry experts

### SecuritySignal.io Access Controls
* SecuritySignal.io will only ever request read access to client environments.
* Only specific operational leads have access to deploy SecuritySignal.io or manage the production environment.
* Only specific research team members have access to read a client's specific findings in SecuritySignal.io and only for the purpose of providing support and remediation assistance.

### SecuritySignal.io Logging and Auditing
* Access to SecuritySignal.io functions and privileged actions are written to audit tables for visibiltiy and review.
* Access controls are verified through log review.
