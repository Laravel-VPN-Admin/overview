# Laravel VPN Admin

<img src="./schema.jpg">

## Software Stack
* Docker
* Laravel/Symfony
* VueJS
* OpenVPN
* L2TP

## Technical requirements
* Required to create a modular structure of containers that would work independently from root server
* It should be composition of Docker containers which possible to run on popular OS
* OAuth2 authorization support
* It should be pure API server with GraphQL
* Groups of users
* Should be possible to create multiple VPN servers with different groups of users
* LDAP support
* Ability to generate SSL certificates for different servers
* Monitoring and statistics of usage
* Containers with VPN servers should self announced on API server
* Self testing of everything on build stage
