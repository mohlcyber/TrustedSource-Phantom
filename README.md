# TrustedSource-Phantom
[![License](https://img.shields.io/badge/License-Apache%202.0-blue.svg)](https://opensource.org/licenses/Apache-2.0)

This integration provides the ability to lookup the McAfee TrustedSource service to support key threat investigation tasks.

The app supports the following actions:

1. **test connectivity** - validate the asset configuration and tests access to the TrustedSource service
2. **lookup url** - check the url categorization and risk level

## Component Description

**Phantom** is a community powered security automation and orchestration platform. https://www.phantom.us/

**McAfee TrustedSource** is an online reputation service for URL categorization and risk level determination

## Prerequisites

Phantom Platform tested with version 3.5.210

## Configuration
Download the Latest release, open the Phantom Platform and and go to Apps. Under Apps click install app and upload the tgz file.

<img width="1313" alt="screen shot 2018-06-20 at 13 09 05" src="https://user-images.githubusercontent.com/25227268/41654888-2a1b90b8-748b-11e8-8c04-9560b8ecc157.png">

Configure a new asset and provide an asset name. 
Click test connectivity to test access to the TrustedSource service.

<img width="903" alt="screen shot 2018-06-20 at 13 10 21" src="https://user-images.githubusercontent.com/25227268/41654966-652af75c-748b-11e8-9296-f42c8af3b233.png">

## Usage

In the mission control / playbook you can lookup a domain / url categories including the risk level.

<img width="1046" alt="screen shot 2018-06-20 at 13 14 01" src="https://user-images.githubusercontent.com/25227268/41655078-f9bacce4-748b-11e8-861b-aded47da96c2.png">
