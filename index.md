---
layout: default
title: "Christopher Grau"
---

# Synopsis

As a programmer, I have built my career on creating tools to bring joy to
tasks that people once found difficult or dull, freeing them to in turn
improve their own work.

I look at every task and consider how it can be improved. What can—and, more
importantly, should—be automated? Would looking at things from a different
angle open opportunities for simplification? I may find myself streamlining
deployment of an application to a cloud service by creating a full CI/CD
stack, or developing small tools to perform repetitive tasks. Instead of
manually setting the thermostat, a bit of home automation can easily sync the
temperature to match the current solar power generation.

I am constantly seeking opportunities to improve. Nothing pleases me more than
seeing the sense of satisfaction, and sometimes joy, that my work creates in
others.

# Experience

## DevOps Engineer, Flux7/NTT DATA

January 2020—Present

My official title with NTT DATA is Digital Engineering Lead Advisor, but my
role can be thought of as DevOps Engineer and Jack of all Trades. I started my
employment with Flux7, prior to its acquisition by NTT DATA, with the goal of
acquiring experience with cloud computing. At first, this was with AWS
services, but has extended to include Microsoft Azure.

While working with NTT DATA, I have had the opportunity to work on a number of
projects for companies in industries ranging from freight logistics to
electronic design automation to health care. Highlights include,

- Deployment of CI/CD pipelines, Lambda functions, and AWS Step Functions
  using the AWS CDK (Python).
- Development of Terraform modules and templates, and Azure Pipelines, to
  create a greenfield infrastructure in Azure.
- Deployment of IBM Spectrum LSF in AWS using Multicluster and Resource
  Connector to facilitate workload needs beyond on-premises peak capacity.
- Deployment of enterprise automation software to AWS using custom
  CloudFormation templates managed by Azure Pipelines.
- Development of a VPC Factory in AWS Service Catalog, using Serverless
  Transit Network Orchestrator (STNO), NetBox, and a CloudFormation Custom
  Resource.
  - <https://us.nttdata.com/en/case-studies/flexport-aws-solution>

In addition to the aforementioned projects, I have occasionally been a member
of the internal Platforms team. I served both as an individual contributor and
a customer for the Scrum team.

As an individual contributor, I worked on the team's primary product, a custom
Landing Zone for organizations using AWS, in addition to several internal
tools used by the team.

- Contributed to the design and development of the Landing Zone, based on AWS
  Control Tower and custom CloudFormation templates deployed using
  Customizations for AWS Control Tower.
- Implemented an account-agnostic deployment of Cloud Custodian using AWS
  CodePipeline, with pluggable rule sets.

As a customer I guided the team through a series of sprints to implement, for
the first time, code quality metrics and test coverage of the primary product.

## Programmer/IT Engineer, Qualcomm

February 2006—January 2020

I started with Qualcomm as a Senior IT Engineer, eventually working my way up
to Senior Staff Programmer Analyst. With each promotion, my responsibilities
vis-a-vis the batch compute infrastructure grew in scope.

As a Senior IT Engineer with the Engineering Compute organization, I played a
pivotal role in maintaining and enhancing the
[LSF](https://en.wikipedia.org/wiki/IBM_Spectrum_LSF) cluster used by the
Hardware Engineering teams.

- Developed a Perl library on top of the
  [LSF::Base](https://metacpan.org/pod/LSF::Base) and
  [LSF::Batch](https://metacpan.org/pod/LSF::Batch) modules, to provide an
  Abstraction Layer for CAD teams to build workflows.
- Maintained internal forks of the LSF::Base and LSF::Batch modules to support
  new releases of LSF software.
- Developed tools for users and administrators to interact with LSF, allowing
  them to focus on accomplishing their work instead of worrying about the
  intricacies of the batch system.

As a Staff IT Engineer with the Engineering Compute organization, my role and
responsibilities grew in support of the LSF clusters we maintained.

- Designed new installation and maintenance procedures to allow a small team
  to support dozens of LSF clusters around the world.
- Developed custom LSF run-time components (e.g., job starter, modular
  [esub](https://www.ibm.com/docs/en/spectrum-lsf/10.1.0?topic=controls-job-submission-execution),
  modular
  [elim](https://www.ibm.com/docs/en/spectrum-lsf/10.1.0?topic=resources-external-load-indices)).
- Created unique job scheduling solutions to support FPGA-based hardware
  accelerators.
- Designed a distributed caching service for license usage data, alleviating
  significant load on legacy FLEXlm license servers.

The shift in title from IT Engineer to Programmer Analyst was done to better
align my title with the kind of work I did. Unlike a traditional IT Engineer,
I spent the majority of my time writing code to solve problems, rather than
maintaining systems.

- Developed a system to send internal batch computing workloads from LSF to
  Amazon EC2 for processing.
  - This was done as a custom solution prior to the release of LSF Resource
    Connector.
- Developed configuration- and data-driven FLEXlm license management tools,
  saving countless administrator hours and significant licensing costs.
- Implemented new Perl installation and support standards for the global
  AFS-based software environment, extending to general Open Source software
  support guidelines.
- Worked with administrators to create Splunk field extractions, macros,
  Python-based external lookups, and custom data feeds to improve system
  monitoring and incident analysis.
- Developed custom daemons to monitor compute system state, repair it when
  possible, or remove it from the cluster and alert administrators to the
  problem.

With my promotion to Senior Staff Programmer Analyst, my focus shifted from
creating tools to assist others in their work to designing systems to enhance
the compute capabilities of the LSF clusters.

- Developed machine learning models to predict the resources needed by a batch
  job, such as memory and CPU utilization.
- Integrated third party predictive models with the LSF batch job submission
  process as a holistic grid optimization solution.
- Led teams of software developers and systems analysts to fulfill the
  strategic objectives of the organization.

# Education

**University of California, San Diego** \
1995—1999 \
Bachelor of Science, Computer Science \
Minor, Psychology

# Certifications

[AWS Certified Cloud Practitioner](https://www.youracclaim.com/badges/12acb282-6e13-46b5-a713-d5a83b4d142a) \
August 2020—December 2023

[AWS Certified Developer – Associate](https://www.youracclaim.com/badges/28201d54-0ab3-416b-ae3b-35b1d38a8994) \
December 2020—December 2023

[AWS Certified Solutions Architect – Associate](https://www.youracclaim.com/badges/0f3d2c70-893e-48dc-9849-c9eec2616f25) \
October 2020—October 2023

# Personal Projects

## [Home Directory Configuration](https://github.com/sirhc/dotfiles)

Mostly used as a way to keep all of my configuration safe and in one place, I
use this as a showcase of the tools I use to be productive.

## [Vim Profile](https://github.com/sirhc/vim-profile)

I have used Vim for many years and have collected my configuration here, which
I use to help others learn about Vim's features.

## [Home Lab](https://github.com/sirhc/homelab)

A trend among technologists is to self-host services that do not rely on any
one company or cloud provider. I have started with Grafana and a few data
collectors. Eventually, I will replace most of the cloud services I use with
self-hosted applications.
