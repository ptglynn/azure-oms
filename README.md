# azure-oms
These files may be used to create a Docker image that listens on UTP/TCP port 514 and forwards properly-formatted syslog messages to a pre-existing Log Analytics workspace in Azure. The logs may then be viewed in Log Analytics or processed by Azure Security Center.

## Pre-requisites
- A Log Analytics workspace in Azure
- The Workspace ID (e.g. 88888888-4444-4444-4444-CCCCCCCCCCCC)
- The Primary Key (e.g. kH62VPnB27B............................................uxN4owCNcg==)
- Docker

## Build
- Place all files into the same directory on the Docker machine
- run "docker build ."

## Run

## Support Policy
The guide in this directory and accompanied files are released under an as-is, best effort, support policy. These scripts should be seen as community supported and Palo Alto Networks will contribute our expertise as and when possible. We do not provide technical support or help in using or troubleshooting the components of the project through our normal support options such as Palo Alto Networks support teams, or ASC (Authorized Support Centers) partners and backline support options. The underlying product used (the VM-Series firewall) by the scripts or templates are still supported, but the support is only for the product functionality and not for help in deploying or using the template or script itself.
Unless explicitly tagged, all projects or work posted in our GitHub repository (at https://github.com/PaloAltoNetworks) or sites other than our official Downloads page on https://support.paloaltonetworks.com are provided under the best effort policy.
