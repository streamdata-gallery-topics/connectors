---
name: AWS Server Migration Service
description: AWS Server Migration Service (SMS) is an agentless service which makes
  it easier and faster for you to migrate thousands of on-premises workloads to AWS.
  AWS SMS allows you to automate, schedule, and track incremental replications of
  live server volumes, making it easier for you to coordinate large-scale server migrations.
image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AmazonEC2_AMI.png
x-kinRank: "10"
x-alexaRank: ""
tags:
- Stack Network
- Migration
- Database
- Amazon Web Services
created: "2018-03-23"
modified: "2018-03-23"
url: https://raw.githubusercontent.com/streamdata-gallery-topics/connectors/master/_listings/aws-server-migration-service/apis.yaml
specificationVersion: "0.14"
apis:
- name: AWS Server Migration Service API
  description: AWS Server Migration Service (SMS) is an agentless service which makes
    it easier and faster for you to migrate thousands of on-premises workloads to
    AWS
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AmazonEC2_AMI.png
  humanURL: ""
  baseURL: :///
  tags: Connectors
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/connectors/master/_listings/aws-server-migration-service/action-getconnectors-get.md
- name: AWS Server Migration Service API Get Connectors
  description: The get-connectors API returns a list of connectors that are registered
    with the Server Migration Service.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AmazonEC2_AMI.png
  humanURL: https://aws.amazon.com/server-migration-service/
  baseURL: http:://{host}//
  tags: Connectors
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/connectors/master/_listings/aws-server-migration-service/action-getconnectors-get.md
x-common:
- type: x-command-line-interface
  url: http://docs.aws.amazon.com/server-migration-service/latest/userguide/cli_workflow.html
- type: x-documentation
  url: http://docs.aws.amazon.com/ServerMigration/latest/APIReference/Welcome.html
- type: x-faq
  url: https://aws.amazon.com/server-migration-service/faqs/
- type: x-getting-started
  url: https://aws.amazon.com/server-migration-service/getting-started/
- type: x-partners
  url: https://aws.amazon.com/server-migration-service/partners/
- type: x-pricing
  url: https://aws.amazon.com/server-migration-service/pricing/
- type: x-website
  url: https://aws.amazon.com/server-migration-service/
- type: x-command-line-interface
  url: http://docs.aws.amazon.com/server-migration-service/latest/userguide/cli_workflow.html
- type: x-documentation
  url: http://docs.aws.amazon.com/ServerMigration/latest/APIReference/Welcome.html
- type: x-faq
  url: https://aws.amazon.com/server-migration-service/faqs/
- type: x-getting-started
  url: https://aws.amazon.com/server-migration-service/getting-started/
- type: x-partners
  url: https://aws.amazon.com/server-migration-service/partners/
- type: x-pricing
  url: https://aws.amazon.com/server-migration-service/pricing/
- type: x-website
  url: https://aws.amazon.com/server-migration-service/
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---