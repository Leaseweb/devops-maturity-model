Automation & Tooling
=============================

Basic Level
-------------

|Automated deployments   |Testing               |Monitoring            |If it moves: graph it |
|------------------------|----------------------|----------------------|----------------------|
|All our code and infra changes are reviewed by at least 1 other team member.|All of our applications can be build in Jenkins and at least they pass a lint check.|All of our products, applications and infrastructure (servers & services) are monitored with basic checks. ( uptime, cpuload, memory usage, high risk functionality) and we receive alerts if anything goes wrong| We have central server & application logging in place and every team member can access them.|
|Our pull requests are only merged after review and we enforce this in Stash.|We have a functional test automation framework in place where time consuming, high risk features can be tested|We have screens which show our monitoring metrics.|We graph basic metrics like bandwidth usage and system load for all systems.|
|We deploy all our applications / infrastructure ourselves (manual or automated)| |We monitor service impacting alerts 24/7| |
|All our code is versioned| | | |


Intermediate Level
-------------

|Automated deployments   |Testing               |Monitoring            |If it moves: graph it |
|------------------------|----------------------|----------------------|----------------------|
|Push button deployment and release of any releasable artifact to any environment.|All of the code we are currently writing has a minimum of 70% good quality unit test coverage|We have trending monitoring, so we can solve issues before they become a incident.|We have a dashboard that shows our current app/infra usage and status (including trends)|
|Our integration test environment is automatically updated after each merge to master branch.|Unit tests run automatically in every Jenkins build and we fix them when they fail.|We monitor based on server and application logging| |
|Pull requests can only be merged after a successful build and we enforce this in Stash.|We have insight into the quality (test coverage, complexity) of the code for each of our apps (sonar).| | |
|We have automatic generation of release notes via the appmgmt portal.|We have fully automated functional regression test of all key features on every release| | |


Target Level
-------------

|Automated deployments   |Testing               |Monitoring            |If it moves: graph it |
|------------------------|----------------------|----------------------|----------------------|
|We have zero touch continuous deployments.|We run automated functional regression, performance and security tests for all apps/infra where this is applicable.|We have monitoring automation in place: servers and service checks are automatically added.|We have dashboards that not only show technical trends but also business trends related to our team (i.e.: incoming orders)|
|We always roll forward, do not rollback|All code we are currently writing has a minimum of 90% good quality unit test coverage| |We can correlate trends in our metrics to events on the platform.|
|Our deployments do not impact our services| | | |

