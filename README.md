# Open Source at Open Raven
This is the main README for open source projects at [Open Raven](https://www.openraven.com). The majority of the engineering here is done by our Corvus Security Research team, a full-time research and development team that focuses on cloud and data security. 

We run an active Slack Workspace that is open to everyone to discuss, ask questions or share ideas. You can join our Slack [here](https://join.slack.com/t/open-raven-research/shared_invite/zt-np27xiev-N5rL4AcTmrQt8YkE81BIaw)

We encourage and welcome [community contributions](CONTRIBUTING.md). 

You operate with a [community code of conduct](CODE_OF_CONDUCT.md)

## The roadmap
You can find the roadmap for all of our projects [here](https://github.com/openraven/open-raven/projects/1). 
Every item on the roadmap is an issue, with a label that indicates each of the following:

- **project** that maps to the specific project.

- **feature area** that indicates the area of the project to which the item belongs. For a list of current project areas, see below.

- **environments** such as AWS, GCP or Azure.

Once a feature is delivered, the **shipped** label will be applied to the roadmap issue and the issue will be closed.

## Roadmap stages

The roadmap is arranged on a project board to give a sense for how far out each item is on the horizon. Every tools or feature is added to a particular project board column according to the quarter in which it is expected to ship next.

## Release phases

Releases are set in each project at the repo level. A release includes the planned feature along with the planned release date. These are all best guess dates given in good faith and should not be relied on. 

## Feature Areas

The following is a list of our current project areas:

- **cloud discovery** - discovering and tracking assets and services running in AWS, GCP and Azure
- **cloud security posture management** - security configurations of cloud providers and their services such as AWS S3
- **data store security posture management** - security configurations of databases, data warehouses and data lakes
- **attack surface management** - discovering and tracking assets that are exposed to attackers such as on the perimeter or those open to the Internet 
- **application and data store identification** - techniques to identify technologies deployed in cloud environments such as non-native data stores
- **shadow account detection** - discovering cloud accounts that are outside of corporate control.
- **data generation** - tools to generate 'impotent' sensitive data that can be safely used for development and testing
- **compliance:** - security compliance with regulations such as GDPR and PCI

## Licenses and Code Contributions

We release all open source code under an [Apache 2.0 license](https://choosealicense.com/licenses/apache-2.0/) unless the individual tool repo states otherwise. Any code contributions that are accepted are bound by the license.
