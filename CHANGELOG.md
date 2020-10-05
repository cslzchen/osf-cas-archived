# Changelog

We follow the CalVer (https://calver.org/) versioning scheme: YY.MINOR.MICRO.

20.1.0 (10-05-2020)
===================

OSF CAS second release to support staging3 deployment

* Disabled SSL and removed keystore
* Factored settings out into local and server ones
* Updated server, network, security, database and authn settings
* Improved branded sign-in for Preprints and Registries
* Updated message.properties for staging3 deployment

20.0.0 (09-02-2020)
===================

OSF CAS first release with basic authentication features for OSF

* Username and password login
* Username and verification key login
* Two-factor authenticaion
* Long-term authentication
* ORCiD login

Technical details

* JSON service registry
* JPA ticket regisrtry with PostgreSQL
* JPA PostgreSQL authentication backend
* Customized login web flow and authentication including:
  * OSF credential and metadata populator
  * OSF non-interactive authentication action
  * OSF PostgreSQL authentication handler
  * Pac4j authentication delegation
  * Two-factor authentication using time-based one-time password
  * Customized authentication exception handling
  * Customized user interface

