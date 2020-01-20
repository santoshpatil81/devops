# Challenge
Below is the DevOps challenge. 

## Background
A development team has created a Java web app that is ready for a limited
release (with reduced availability and reliability requirements). If the limited
release is successful the app will be rolled out for worldwide
use. Once fully public, the application needs to be available 24/7 and must
provide sub second response times and continuity through single server
failures

## Basic Problem
You need to create two environments one for training and one for
production. You should prepare the production environment for the limited
release and plan for the scale out during fully public release.
Assumptions

• You have free rein to incorporate any software tools and hardware you
need to streamline application deployment and infrastructure
provisioning & configuration as long as they are Free/Libre/Open
Source software (FLOSS). We request that you use Linux.
• The development team has a continuous integration build that
produces two artifacts:
• a .zip file with the image and stylesheet used for the application
• a .war file with the dynamic parts of the application

• You should deploy the static assets to a web server and the .war file to
a separate application server. Any compatible servers are acceptable.
• The app (companyNews) uses Prevayler for persistence. Prevayler
essentially persists data to a file. The dev team chose this to simplify the
development effort, rather than having to deal with an RDBMS.

# Solution
