Apache JMeter
=======
The Apache JMeter™ application is open source software, a 100% pure Java application designed to load test functional behavior and measure performance. It was originally designed for testing Web Applications but has since expanded to other test functions.

Read the documentation and more at http://jmeter.apache.org/

#  Apache JMeter for e301
This repository is for Jmeter performance testing relating to e301 for use on AWS and internal infrastructure.

## Setup / Prerequisite's
Notes: Solution leverages https://github.com/kulya/jmeter-gradle-plugin
To find out more goto https://github.com/kulya/jmeter-gradle-plugin/wiki
### 1) - Gradle 
  go to https://gradle.org/ and download/install gradle 
### 2) - Clone this repository
```
  git clone *<this repo>*
```
### 3) - Customise the 'jmeter.properties' to your liking
```
  cp jmeter.properties.example jmeter.properties
  vim jmeter.properties
```
### 4) - Customise the 'jmeter.properties' to your liking
```
  cp jmeter.properties.example jmeter.properties
  vim jmeter.properties
```
### 5) - Customise the 'testplans.xml' to your liking
```
  cp jmeter.properties.example jmeter.properties
  vim jmeter.properties
```
## Ansible Plays for AWS EC2 instances
provision_ec2_jmeter.yml - Configure a jmeter stack 
