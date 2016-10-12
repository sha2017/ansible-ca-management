## Goal

It's 2016 and to our surpise no one has created a method of good automated CA management for internal use. Our team wants to roll out internal as well as external certifcates. 
Luckily for external perposes Letsencrypt does the job well but internaly we still have no good system. 


## brainstorming method of cert Delivery 
* ACME protocol used internally could be a viable option for automated device renewal of internal servers and VPN connected laptops? 
* Another approach could be having Ansible manage the signing, distribution and renewal of certifcations to internal servers. 


## Brainstorming Useful Features
* CA Management 
* Intermediate CA Management
* Per Device CA Management 
* Revocation of Certificates
* Renewal of Certificates 
* Signing of Certificates with intermediate CA
