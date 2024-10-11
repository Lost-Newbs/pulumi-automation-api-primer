# pulumi-automation-api-primer
A primer on Pulumi's Automation API

Pulumi Automation API is a nifty way to invoke Pulumi diretly from code without using the command line, which opens up a hoard of possibilities with [infrastructure as software](https://www.pulumi.com/what-is/what-is-infrastructure-as-software/).
## Prereqs
Start with the [primer on Pulumi](https://github.com/Lost-Newbs/pulumi-primer) if you're new to Pulumi or need a quick refresher.
## Languages
We're going to use Python, but PAAPI is available in other languages (as is Pulumi).

(If you're able to contribute in another language, please do!)
## Infra to Deploy
We're going to cover two deployments, the basic infrastructure from the `Pulumi primer` and an advanced one, deploying the [webhook + serverless infrastructure](https://gitlab.com/money-marathon/cloudacious/cloudacious-iac/-/blob/08f8b3acccbc317c265a73189eac20ccfdda3bf9/src/cloudaciousIAC/WebhookHandler.py) for our own [Lost Newbs Discord/chat bot](https://gitlab.com/lost-newbs/lost-newbs-bot) using object-oriented Pulumi Infrastructure as Code from [Cloudacious](https://cloudacious.io/).
## Deployment
