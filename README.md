# Cloud Foundry Walkthrough

## Fetch and build the example source code
* Install Homebrew and Java (if necessary):
  ```
  /usr/bin/ruby -e "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install)"
  brew update && brew cask install java
  ```
* Fetch "Articulate" code:
  ```
  git clone https://github.com/pivotal-education/pcf-articulate-code.git
  ```
* Fetch "Attendee Service" code:
  ```
  git clone https://github.com/pivotal-education/pcf-attendee-service-code.git\
  ```
  
* Compile code:
  ```
  cd [PATH_TO]/pcf-articulate-code && ./mvnw clean package
  cd [PATH_TO]/pcf-attendee-service-code && ./mvnw clean package
  ```

## I've always wondered ...
1. Vitual Machines and Containers?
1. Immutable, Ephemeral, Polyglot, and Idempotent?
1. Networks, Gateways, Internal/External IP Addresses?
1. IaaS, PaaS and SaaS?

## Cloud Native Primer
1. [Why Cloud Native](https://content.enablement.pivotal.io/spring-cloud-services/why-cloud-native)
1. [12 Factor App](https://content.enablement.pivotal.io/spring-cloud-services/68-cloud-native-design.pdf)
1. Spring Cloud Services (The Netflix OSS)?

## Cloud Foundry Intro
1. Open Source CF
1. PWS
1. PCF
1. PCFDev
1. Pivotal Network
1. Operations Manager (PCF)
1. Apps Manager (PCF & PWS)
1. The CF cli (all CFs)
   1. [Installing the CF cli](https://console.run.pivotal.io/tools)
   1. cf login -a https://api.run.pivotal.io -u USER -o apm-pivotal-org -s USER
   1. cf help -a
   1. cf stacks
   1. cf buildpacks
   1. cf marketplace
   1. cf orgs
   1. cf spaces
   1. cf target
   1. cf create-service
   1. cf services
   1. cf push (--no-start | --random-route)
   1. cf apps
   1. cf bind-service
   1. cf env
   1. cf start/stop/restart
   1. cf logs
   1. cf scale
   1. cf create-app-manifest
   1. cf plugins
   1. cf ssh
   1. [cftunnel](https://github.com/pivotal-education/public-tools/tree/master/cftunnel) :-)
1. [Logging, Scale & HA](https://content.enablement.pivotal.io/zzz-pivotal-cloud-foundry-administrator/platform-app-delivery-unit/logging-scale-ha/slides.pdf)
1. [BOSH](https://content.enablement.pivotal.io/zzz-pivotal-cloud-foundry-administrator/troubleshooting-unit/bosh-troubleshooting/slides.pdf)
1. [Deployment Topologies](https://content.enablement.pivotal.io/zzz-pivotal-cloud-foundry-administrator/operations-unit/deployment-topologies/slides.pdf)

## Questions

Fire away ...

### Shhhhh!
* user:   ???????
* passwd: ????????????
