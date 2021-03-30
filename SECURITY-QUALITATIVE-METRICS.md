---

layout: col-sidebar
title: OWASP Security Qualitative Metrics
site_side: true
tags: security-qualitative-metrics
project: true
level: 2
type: tool
pitch: The OWASP Security Qualitative Metrics is the most detailed list of metrics which evaluate security level of web projects. It shows the level of coverage of OWASP ASVS. 
---

# ![Project Logo](images/logo3_small.png) OWASP Security Qualitative Metrics  
# [![OWASP Flagship](https://img.shields.io/badge/owasp-flagship-blue.svg)](https://owasp.org/projects/)
 [![GitHub license](https://img.shields.io/github/license/Naereen/StrapDown.js.svg)](https://github.com/OWASP/www-project-security-qualitative-metrics/blob/master/LICENSE)

 [![GitHub release](https://img.shields.io/github/release/Naereen/StrapDown.js.svg)](https://github.com/OWASP/www-project-security-qualitative-metrics/releases)
 

## Metrics Related to Highlights of Application Architecture, Design, and Implementation

In the first group, details related to mostly technical decisions are evaluated for a web application software. These decisions may be related to application architecture, design, and implementation. Technical staff including software developers, architects may benefit this list while designing and implementing software.

|     #      |     G    |     Description                                                                                                          |     O     W     A     S     P    |
|------------|----------|--------------------------------------------------------------------------------------------------------------------------|----------------------------------|
|     1      |     A    |     Use   menu structure which suits business requirements groupings and hierarchies                                     |     1.4                          |
|     2      |     A    |     Use   of layered architecture                                                                                        |     1.9                          |
|     3      |     A    |     Using   single-sign-on                                                                                               |     2.1                          |
|     4      |     A    |     Controlling   request based authorization and authenticity control rather than doing only   during menu creation     |     2.1                          |
|     5      |     A    |     Prevent   auto filling of user forms                                                                                 |     2.2                          |
|     6      |     A    |     Rest   service calls based on authentication tokens on server side                                                   |     2.4, 4.9                     |
|     7      |     A    |     Basic   authentication based on always use of https                                                                  |     2.4                          |
|     8      |     A    |     Safe   exception handling, safe failure                                                                              |     2.6, 4.8                     |
|     9      |     A    |     Validation   of user forms for min-max lengths and not null values                                                   |     2.7                          |
|     10     |     A    |     Safe   secondary authentication mechanisms forgot and change password                                                |     2.8, 2.9                     |
|     11     |     A    |     Limit   risky functions to priviledges users (such as close account)                                                 |     2.8                          |
|     12     |     A    |     Safe   logging without sensitive information                                                                         |     2.12                         |
|     13     |     A    |     One   way hashed passwords                                                                                           |     2.13                         |
|     14     |     A    |     Use   of encrypted links and URLs                                                                                    |     2.16, 3.6                    |
|     15     |     A    |     Use   of multi canals during password removal                                                                        |     2.17                         |
|     16     |     A    |     Use   of random generated data during password removal                                                               |     2.17, 2.22                   |
|     17     |     A    |     Authentication   error messages with no authentication information                                                   |     2.18                         |
|     18     |     A    |     Use   of no default passwords                                                                                        |     2.19                         |
|     19     |     A    |     Use   of captcha to prevent brute force attacks                                                                      |     2.2                          |
|     20     |     A    |     Use   of centralized safe authentication data                                                                        |     2.21                         |
|     21     |     A    |     Use   of account soft lock and hard lock mechanism                                                                   |     2.23                         |
|     22     |     A    |     Use   of reliable secret question set for recovery                                                                   |     2.24                         |
|     23     |     A    |     Use   of recently used (last n) old passwords should be prevented                                                    |     2.25                         |
|     24     |     A    |     Use   of two factor authentication for functions with high risks                                                     |     2.26                         |
|     25     |     A    |     Use   of proper password constraints                                                                                 |     2.27                         |
|     26     |     A    |     Authentication   success and failure times should be equal on average                                                |     2.28                         |
|     27     |     A    |     Cleaning   secret codes, API keys and passwords from code                                                            |     2.29                         |
|     28     |     A    |     Use   of two factor authentication or similar strong authentication mechanism                                        |     2.31                         |
|     29     |     A    |     Protection   of administrative interfaces                                                                            |     2.32                         |
|     30     |     A    |     Design   administrative interfaces as a separate web/ intranet application                                           |     2.32                         |
|     31     |     A    |     Disable   of browser autocomplete and/or integration with password managers                                          |     2.33                         |
|     32     |     A    |     Open   new session for new authentication and check the origin of session ids                                        |     3.1, 3.7, 3.10               |
|     33     |     A    |     Proper   log out functions which terminates all user sessions                                                        |     3.2                          |
|     34     |     A    |     Termination   of session automatically after timeout or after a period of inactivity                                 |     3.3, 3.4                     |
|     35     |     A    |     Easy   access to logout functions from all authenticated pages                                                       |     3.5                          |
|     36     |     A    |     Having   a central cookie generator which sets HttpOnly and Secure cookie parameters                                 |     3.12                         |
|     37     |     A    |     Limited   number of active sessions                                                                                  |     3.16                         |
|     38     |     A    |     Visualization   of active sessions                                                                                   |     3.17                         |
|     39     |     A    |     Closing   all active sessions during password change                                                                 |     3.18                         |
|     40     |     A    |     Applying   RBAC principles                                                                                           |     4.1                          |
|     41     |     A    |     Use   data access control                                                                                            |     4.4                          |
|     42     |     A    |     Centralization   of Access Control with protection of access control data                                            |     4.8, 4.10, 4.11              |
|     43     |     A    |     Use   of source control for source code libraries and all kind of resources                                          |     4.11                         |
|     44     |     A    |     Logging   of both access control successes and failures                                                              |     4.12                         |
|     45     |     A    |     Safe   secondary access control for lower value or critical systems                                                  |     4.15                         |
|     46     |     A    |     Context   sensitive authorization                                                                                    |     4.16                         |
|     47     |     A    |     Use   Server Side Validation For Input Fields                                                                        |     5.3, 5.5                     |
|     48     |     A    |     Check   all the file inclusions to prevent remote file inclusions                                                    |     5.13                         |
|     49     |     A    |     Do   not use script codes directly in the web pages                                                                  |     5.14                         |
|     50     |     A    |     Do   not use style codes directly in the web pages                                                                   |     5.14                         |
|     51     |     A    |     Use   of resource files for all string variables                                                                     |     5.15                         |
|     52     |     A    |     Use   of client side validation together with server side validation                                                 |     5.18                         |
|     53     |     A    |     Rest   services have their own validations                                                                           |     5.19                         |
|     54     |     A    |     All   types of inputs such as RSS, Cookie, Batch files should be validated                                           |     5.19                         |
|     55     |     A    |     Use   of servlet filters to clean unstructured data                                                                  |     5.21                         |
|     56     |     A    |     Careful   use of html editors and avoid unnecessary usage                                                            |     5.22                         |
|     57     |     A    |     Use   of HTML sanitization                                                                                           |     5.23                         |
|     58     |     A    |     Use   of safe logout functions                                                                                       |     5.26                         |
|     59     |     A    |     Delete   login information during logout                                                                             |     5.26                         |
|     60     |     A    |     Secure   cryptographic modules which fail safely                                                                     |     7.2                          |
|     61     |     A    |     The   integrity of the cipher text should be checked based on                                                        |     7.2                          |
|     62     |     A    |     Choosing   the secure operating modes of the cryptologic functions                                                   |     7.8                          |
|     63     |     A    |     Enforce   a secure lifecycle for cryptologic keys                                                                    |     7.9, 7.11                    |
|     64     |     A    |     Using   keyless hash functions                                                                                       |     7.9, 7.11                    |
|     65     |     A    |     Using   physical keys                                                                                                |     7.11                         |
|     66     |     A    |     Storing   the user passwords encrypted in database                                                                   |     7.12                         |
|     67     |     A    |     Critical   data should be replaced with 00 when soft deleted                                                         |     7.13                         |
|     68     |     A    |     All   keys and passwords should be replaced at installation                                                          |     7.14                         |
|     69     |     A    |     Do   not log sensitive data (session identifier, password, hash, or API token)                                       |     8.7                          |
|     70     |     A    |     Prevent   log injection by log designs with character encoding for unprintable   characters and fixed file format    |     8.8                          |
|     71     |     A    |     Taking   error messages and user alerts from the property files may prevent log   injection                          |     8.8                          |
|     72     |     A    |     Mark   log entries from external resources such as third-party services by a field                                   |     8.9                          |
|     73     |     A    |     Filter   external originated log entries before automatic processing of log files                                    |     8.9                          |
|     74     |     A    |     Log   all user activities with user Id’s to prevent non-repudiation of events                                        |     8.1                          |
|     75     |     A    |     Use   of soft delete to prevent non-repudiation of user activities                                                   |     8.1                          |
|     76     |     A    |     Keep   log files on a different disk partitions with application files                                               |     8.12                         |
|     77     |     A    |     Use   of common clock among multiple web servers                                                                     |     8.13                         |
|     78     |     A    |     Use   HTTP header parameters and caching to prevent client side caching (Cache   Control, Pragma)                    |     9.1, 9.4                     |
|     79     |     A    |     Make   a list of sensitive data for application e.g. monetary data                                                   |     9.2                          |
|     80     |     A    |     Authorize   a restricted group of users for application parts with sensitive data                                    |     9.2                          |
|     81     |     A    |     Use   secondary authentication for parts with sensitive data                                                         |     9.2                          |
|     82     |     A    |     URL   parameters should never be used to transfer sensitive data                                                     |     9.3                          |
|     83     |     A    |     No   sensitive data outside body section of the HTTP page                                                            |     9.3                          |
|     84     |     A    |     Use   of Captcha in critical query pages                                                                             |     9.8                          |
|     85     |     A    |     Minimum   data retained on the client side and deleted when user session is over.                                    |     9.9                          |
|     86     |     A    |     Keep   the creation and update information for all data tables                                                       |     9.1                          |
|     87     |     A    |     Use   of a structure to store historical access information for critical data                                        |     9.1                          |
|     88     |     A    |     Keep character data in char [] not in String to limit   data life                                                    |     9.11                         |
|     89     |     A    |     Replace   critical data with zeros after usage in memory                                                             |     9.11                         |
|     90     |     A    |     Http Strict Transport Security (HSTS) in HTTP header to   force mandatory use of HTTPS                               |     10.3, 10.11                  |
|     91     |     A    |     TLS   connection failures should be logged                                                                           |     10.4                         |
|     92     |     A    |     No   use of certificated in client side                                                                              |     10.5                         |
|     93     |     A    |     Use   of trusted certificates in the clients                                                                         |     10.5                         |
|     94     |     A    |     Do   not mix TLS and non-TLS pages                                                                                   |     10.6                         |
|     95     |     A    |     Set   Public-Key-Pins HTTP Header prevent MITM attacks                                                               |     10.1                         |
|     96     |     A    |     Define   undesirable HTTP methods in web.xml                                                                         |     11.1                         |
|     97     |     A    |     Define   loggers in Controllers for undesirable HTTP methods                                                         |     11.1                         |
|     98     |     A    |     Include   character set definitions in XHTML codes                                                                   |     11.2                         |
|     99     |     A    |     Use   of authentication token in client application                                                                  |     11.3                         |
|     100    |     A    |     Use   of X-FRAME-OPTIONS for pages that should not be viewed for third parties                                       |     11.4                         |
|     101    |     A    |     No   application version (powered by, server, MVC) in headers                                                        |     11.5                         |
|     102    |     A    |     Check   content and MIME type for requests and responses                                                             |     11.6                         |
|     103    |     A    |     Rest   applications should include response definition type                                                          |     11.6                         |
|     104    |     A    |     Run   content check for service methods with XML, JSON type inputs prior to   processing                             |     11.7                         |
|     105    |     A    |     Enable   X-XSS-Protection header to prevent XSS attacks                                                              |     11.8                         |
|     106    |     A    |     Use   sandbox for codes which may have security problems                                                             |     13.1                         |
|     107    |     A    |     Make sure that the error handling functions work   correctly.                                                        |     13.1                         |
|     108    |     A    |     Make frequent code reviews to ensure critical code is   examined by multiple developers.                             |     13.1                         |
|     109    |     A    |     Use of negative testing                                                                                              |     13.2                         |
|     110    |     A    |     Use of captcha in critical operations against brute   force attacks                                                  |     15.2                         |
|     111    |     A    |     Use of web.xml file to make filters for URL rewriting                                                                |     16.1                         |
|     112    |     A    |     Allow certain files instead of the prohibition during   file uploads.                                                |     16.4                         |
|     113    |     A    |     Do   not allow upload of executable file                                                                             |     16.8                         |
|     114    |     A    |     Remove   UDID, IMEI and similar mobile device data from verification info                                            |     17.1                         |
|     115    |     A    |     Prevent   file downloads from mobile devices                                                                         |     17.2                         |
|     116    |     A    |     Do   not store sensitive data such as key chains and authentication data in mobile   devices                         |     17.3                         |
|     117    |     A    |     Dynamically   generate authentication data (one time passwords, API keys and tokens)                                 |     17.4                         |
|     118    |     A    |     No   sensitive data in mobile applications due to screen capturing                                                   |     17.5                         |
|     119    |     A    |     Authorizations   should be given to small number of assets                                                           |     17.6                         |
|     120    |     A    |     Restricted   file download and uploads in mobile applications                                                        |     17.9                         |
|     121    |     A    |     Use   UTF8 in client and server code                                                                                 |     18.1                         |
|     122    |     A    |     Check incoming content type for Rest services                                                                        |     18.8                         |
|     123    |     A    |     Use payload signing between client and server                                                                        |     18.9                         |
|     124    |     A    |     Isolate external web services and internal service   functions                                                       |     18.9, 18.10                  |
|     125    |     A    |     Use sandbox for multiple applications sharing a   single server                                                      |     19.4                         |
|     126    |     A    |     Include security check flags for all system level   languages                                                        |     19.9                         |
|     127    |     A    |     No application asset (e.g. JavaSript and style sheet   files) should rely on the Internet                            |     19.1                         |


## Metrics Related to Highlights of Technologies

In this second group, details related to the technologies exist. These technologies may be related to development environment, or may be part of the software such as a framework software. This list may be benefited by the technical stuff as well as project manager and the product owner. The provided information may affect proceutions made for the project. These technological decisions may even lead to architectural decisions. While other parts of the Security Qualitative Metrics do not affect by the technology selections, in this part the user may encounter some technology dependent offers. The user may take these offers as is if the selected technology set match the offered ones. Otherwise, the user may check their selected technologies for similar properties and solutions.

|     #      |     G    |     Description                                                                                  |     O     W     A     S     P    |
|------------|----------|--------------------------------------------------------------------------------------------------|----------------------------------|
|     128    |     B    |     Use   Spring Security for centralized security controls                                      |     1.7                          |
|     129    |     B    |     Use   of Spring MVC for clear separation of data, view and controller components             |     1.9                          |
|     130    |     B    |     Use   Spring-MVC to help clearance of client code from secret codes and business   logic.    |     1.1                          |
|     131    |     B    |     Using   bug free technologies having reliable references                                     |     1.11                         |
|     132    |     B    |     Be   skeptical to newly emerged technologies, libraries, third party tools etc.              |     1.11                         |
|     133    |     B    |     Using   Spring anti-CSRF tokens to protect from CSRF attacks                                 |     4.13                         |
|     134    |     B    |     Use   database resource governer to prevent aggregate updates                                |     4.14                         |
|     135    |     B    |     Avoid   using Java Native lib                                                                |     5.1                          |
|     136    |     B    |     Using   JSF or similar framework for central validation                                      |     5.6                          |
|     137    |     B    |     Use   ORM (e.g. Hibernate) to prevent SQL injection                                          |     5.1                          |
|     138    |     B    |     Use   of Spring validator                                                                    |     5.16                         |
|     139    |     B    |     Use   of Spring InitBinder                                                                   |     5.16                         |
|     140    |     B    |     Differentiation   of request params by java Spring framework                                 |     5.17                         |
|     141    |     B    |     Use   of Java Regex for email, telephone or similar fields                                   |     5.2                          |
|     142    |     B    |     Use   of InnerText instead of innerHTML in Javascript                                        |     5.24                         |
|     143    |     B    |     Use   of json.parse instead of eval functions in Javascript                                  |     5.25                         |
|     144    |     B    |     Use   java.security.SecureRandom instead of java.util.random                                 |     7.6, 7.15                    |
|     145    |     B    |     Using   SHA-256/SHA-512, PBKDF2-HMAC rather Bcrypt against FIPS-140-2 or equivalent          |     7.7                          |
|     146    |     B    |     Error   messages should not include sensitive data                                           |     8.1                          |
|     147    |     B    |     Central   error handling mechanism/code                                                      |     8.2                          |
|     148    |     B    |     Hiding   critical central logic by using library files                                       |     8.2                          |
|     149    |     B    |     Log   both success and failures of security related functions                                |     8.3                          |
|     150    |     B    |     Logs   should include necessary data to form a timeline of events                            |     8.4                          |
|     151    |     B    |     Critical   data stored in the database should be protected by unauthorized access            |     9.5                          |
|     152    |     B    |     Use   of TLS for all authenticated connections                                               |     10.3                         |
|     153    |     B    |     Use   of TLS for transfers with sensitive data                                               |     10.3                         |
|     154    |     B    |     Use   of the latest TLS version compatible with the web server                               |     10.16                        |
|     155    |     B    |     Use   of Java SecurityManager                                                                |     13.1                         |
|     156    |     B    |     Use   of mod-rewrite module in Apache Tomcat for custom rewriting rules                      |     16.1                         |
|     157    |     B    |     Use   of URLRewritingFilter to filter URL rewrites                                           |     16.1                         |
|     158    |     B    |     Use   of document management system for external file loading                                |     16.2                         |
|     159    |     B    |     Store   external files as byte arrays instead of disk files                                  |     16.2                         |
|     160    |     B    |     Limit   cross domain resource sharing using Spring                                           |     16.5, 18.7                   |
|     161    |     B    |     Do   not use Flash                                                                           |     16.9                         |
|     162    |     B    |     Do   not use non native Java technologies(e.g. Silverlight)                                  |     16.9                         |
|     163    |     B    |     Install   screen capture prevention for mobile apps                                          |     17.5                         |
|     164    |     B    |     Use   of ASLR technologies on mobile devices                                                 |     17.7                         |
|     165    |     B    |     Check   existence and executability of remote debugging apps in client sides                 |     17.8                         |
|     166    |     B    |     Annotate   web services schema format (e.g. JSON)                                            |     18.3                         |
|     167    |     B    |     Use   Spring input validation                                                                |     18.4                         |
|     168    |     B    |     Do   not use static API keys                                                                 |     18.6                         |
                                                                                            |                             


## Metrics Related to Highlights of Environment

In this third group, 

|     #      |     G    |     Description                                                                                                              |     O     W     A     S     P    |
|------------|----------|------------------------------------------------------------------------------------------------------------------------------|----------------------------------|
|     169    |     C    |     Network   segregation                                                                                                    |     1.8                          |
|     170    |     C    |     Use   of firewall rules                                                                                                  |     1.8, 17.11                   |
|     171    |     C    |     Disable   URL-Rewriting in application/web servers                                                                       |     3.6                          |
|     172    |     C    |     Configuring   a sufficiently long session id(s) in web servers                                                           |     3.11                         |
|     173    |     C    |     Disable   Directory Browsing on web server                                                                               |     4.5                          |
|     174    |     C    |     Do   not store SVN/Git files on web server                                                                               |     4.5                          |
|     175    |     C    |     Use   of static code analysis tools such as SonarQube                                                                    |     5.12, 5.13, 5.14             |
|     176    |     C    |     Use   of trustworthy log viewing software                                                                                |     8.5                          |
|     177    |     C    |     Log   files should be protected against unauthorized access                                                              |     8.6                          |
|     178    |     C    |     Use   physical security for system administration room                                                                   |     8.6                          |
|     179    |     C    |     Non   accessible system room from network devices                                                                        |     8.6                          |
|     180    |     C    |     Achieve   log files in a separate location to prevent unauthorized modification                                          |     8.11                         |
|     181    |     C    |     Trusted   certificates should be installed on the servers                                                                |     10.1                         |
|     182    |     C    |     Check   TLS version for each browser type before production                                                              |     10.8                         |
|     183    |     C    |     Remove   forward secrecy ciphers from web server configuration files                                                     |     10.1                         |
|     184    |     C    |     Enable   proper certificate revocation in web server(OCSP Stapling in Apache)                                            |     10.1                         |
|     185    |     C    |     Consider the warnings given by the IDE.                                                                                  |     13.1                         |
|     186    |     C    |     Use of SonarQube for test coverage analysis                                                                              |     13.1                         |
|     187    |     C    |     URL redirects should be checked or filtered from the   server                                                            |     16.1                         |
|     188    |     C    |     Use antivirus protection in web server for external   file input                                                         |     16.3                         |
|     189    |     C    |     Use   quarantine system as a part of document management                                                                 |     16.3                         |
|     190    |     C    |     Locate   document management system in a separate server                                                                 |     16.6                         |
|     191    |     C    |     Verify   web server is closed to cross domain requests(which is default behaviour)                                       |     16.7                         |
|     192    |     C    |     Prevent   client debugging in clients if there is client side running code                                               |     17.8                         |
|     193    |     C    |     Configure   JVM to often collect to prevent memory data leakage                                                          |     17.1                         |
|     194    |     C    |     Configure   UTF-8 in the IDE                                                                                             |     18.1                         |
|     195    |     C    |     Assign   a web service management team for web service open to third parties                                             |     18.2                         |
|     196    |     C    |     Configure   use of TLS                                                                                                   |     18.5                         |
|     197    |     C    |     Clear deployment paths in the web services prior to   each deploy                                                        |     19.1                         |
|     198    |     C    |     Keep App servers and database servers in the same   network compartment, otherwise encrypt the transform between them    |     19.2                         |
|     199    |     C    |     Give only DML (not DDL) access rights to app server   database users                                                     |     19.3                         |
|     200    |     C    |     Use dedicated server or dedicated virtual servers   for the web applications                                             |     19.4                         |
|     201    |     C    |     Use and automated process and tool for compile,   build and deployment                                                   |     19.5                         |
|     202    |     C    |     System management functions can be accessed by   authorized personnel only                                               |     19.5, 19.6                   |
|     203    |     C    |     Add file integrity checker to automated build/deploy   tool                                                              |     19.6                         |
|     204    |     C    |     Configure web servers to run only signed Jars                                                                            |     19.7                         |
|     205    |     C    |     Use Jar Signer as a part of automated deploy                                                                             |     19.7                         |
|     206    |     C    |     Configure build automation tools to download   third-party libraries from trusted servers                                |     19.8                         |
                                                                                                                          | 
                                                                                                                          
                                                                                                                          
                                              
## Metrics Related to Highlights of Code Generation

In this fourth group, the characterstics related to automatic code generation which are related to the security of the projects are included. Since, details and more detailed security issues would be dependent on the automatic code generator, in this part, only the general principals which matters are included.

|     #      |     G    |     Description                                                     |     O     W     A     S     P    |
|------------|----------|---------------------------------------------------------------------|----------------------------------|
|     207    |     D    |     Automatic   code generation without business logic in client    |     1.1                          |
|     208    |     D    |     Use   of standardized code to eliminate the risk of RFI         |     5.13                         |


## Metrics Related to Highlights of Development Methodologies

In this fifth group, besides automatic code generation, every team adopts some development methodologies, and principals. The metrics in this part are mainly related to top level design decisions. In this part, users may also find items which are related to very initial project management related decisions.

|     #      |     G    |     Description                                                                                    |     O     W     A     S     P    |
|------------|----------|----------------------------------------------------------------------------------------------------|----------------------------------|
|     209    |     E    |     Have   a standardized front end to minimize the # of hidden fields, cookies, and   ajax        |     9.7                          |
|     210    |     E    |     Use of parentheses in automatic code generation                                                |     13.1                         |
|     211    |     E    |     Document   all functions, libraries, and dependencies for better identification of   assets    |     1.1 ,1.2, 1.5                |
|     212    |     E    |     Documentation   of high level architecture                                                     |     1.3                          |
|     213    |     E    |     Prepare   application specific threat model including well-known threats                       |     1.6                          |
|     214    |     E    |     Manual   inspect code before production to clean sensitive information log                     |     8.7                          |
|     215    |     E    |     Decide   data to be destroyed as a part of a retention policy                                  |     9.6                          |
|     216    |     E    |     Selection   responsibility of CA’s by customers                                                |     10.1                         |
|     217    |     E    |     Certified   CA selection by customer for server certification                                  |     10.1                         |
|     218    |     E    |     Submit   the URL to Strict Transport Security domains list maintained for each browser         |     10.2                         |
|     219    |     E    |     Verify   that OCSP Stapling is enabled through digicert                                        |     10.15                        |
|     220    |     E    |     Create a project package structure document                                                    |     19.1                         |
                        
                        
## Metrics Related to Highlights of Business Logic

OWASP points out the importance of business logic related problems.  In this sixth group, security checks which are associated with key business functions that commonly exist in software programs are included.              

|     #      |     G    |     Description                                                                                 |     O     W     A     S     P    |
|------------|----------|-------------------------------------------------------------------------------------------------|----------------------------------|
|     221    |     F    |     Check   transactions related to monetary values                                             |     15.1                         |
|     222    |     F    |     Check   transactions with  date entries                                                     |     15.1                         |
|     223    |     F    |     Check   transactions for sequential events                                                  |     15.1                         |
|     224    |     F    |     Check   transactions related to external users                                              |     15.1                         |
|     225    |     F    |     Check   transactions related to group of users                                              |     15.1                         |
|     226    |     F    |     Check   transactions involving contractual information                                      |     15.1                         |
|     227    |     F    |     Disruption   of business should result with transaction interruption.                       |     15.2                         |
|     228    |     F    |     Incompatible   transactions should be interrupted                                           |     15.2                         |
|     229    |     F    |     Give   file download responsibility to users from mobile devices                            |     17.2                         |
|     230    |     F    |     Use   RBAC restrictions for access file and other important assets from mobile   devices    |     17.2                         |
