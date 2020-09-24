# Design Doc: https://sfdc.co/sustainWater

I made this app to track:

- water consumption (withdrawal and discharge)
- any compliance/regulatory fines

This is an unofficial, unsupported package. We are looking for feedback!

# Installation:
I included an unmanaged package in the docs above but I HIGHLY recommend you use DX to install the metadata instead. If you don't know how, here's a trailhead:

[App Development with Salesforce DX](https://trailhead.salesforce.com/content/learn/modules/sfdx_app_dev) module

Scratch Org:

1. use the included config/project-scratch-def.json to spin up sustainability cloud
2. install the latest sustainability cloud package
3. push this repo into the scratch org

Dev/Production/Sandbox:

1. install sustainability cloud
2. connect to DX
3. install the linked package or push this repo into the org
