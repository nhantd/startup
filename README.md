# Cosmos

## Company purpose
* Create a Software-Defined Data Center on the LXC environment.
* Selling data centers defined by software, not just a infrastructure.
* Software-Defined Data Center
  - http://en.wikipedia.org/wiki/Software-defined_data_center
* Linux Container (LXC)
  - The LXC is an alternative of the Virtual Machine.
  - In case of the VM, its performance is 70~80% of its host. (20~30% loss)
  - In case of the LXC, its performance is 99% of its host. (0~1% loss)
  - http://en.wikipedia.org/wiki/LXC

## Problem
* Storing LXCs as files.
* Moving LXCs to servers.
* Running LXCs on servers.
* Killing LXCs on servers.
* Checking LXCs on servers.
* Automation of running, killing and checking LXCs.
* There are lots of distributed servers on several infrastructures in large-scale production. (Hard to manage these)

## Solution
* Create a cloud storage for storing LXCs.
* Create a cluster management for moving, running, killing and checking LXCs.
* Create a single dashboard for lots of distributed servers.

## Why now
* The stable version of LXC was released in 14 July 2014.
* Now there is a stable version of LXC.
* Need to develop technologies as soon as possible.

## Market size
* expected to be valued at about USD $5.41 billion by 2018.
* compared to USD $396.1 million in 2013.
* estimated Compound Annual Growth Rate (CAGR) of 68.7% from 2013 to 2018.
* http://www.researchandmarkets.com/research/4rrtp6/software_defined

## Competition

### Competitors
* Red Hat Atomic Host (http://www.projectatomic.io)
  - Only for a certain operating system.
* CoreOS (https://coreos.com)
  - Only for a certain operating system.
* Docker Hub (https://hub.docker.com)
  - Only for a cloud storage.
* Quay.io (https://quay.io)
  - Only for a private cloud storage.
  - Acquired by CoreOS.
  - It is not developing anymore.
* Google Container Engine (https://cloud.google.com/container-engine/)
  - Alpha
  - Only for a Google Cloud.
  - Not support for distributed infrastructures.
* Amazon Web Services EC2 Container Service (http://aws.amazon.com/ecs/)
  - Alpha
  - Only for a Amazon Web Services.
  - Not support for distributed infrastructures.
* Flynn (https://flynn.io)
  - Not public.
* NewRelic (http://newrelic.com)
  - Not support for LXCs.

### Competitive advantages
* We write code in Go language for efficiency.
* No dependency for a certain infrastructure
* No dependency for a certain operating system
* A cluster management service integrated with a cloud storage service
* A single dashboard for distributed servers
* An automation service for a certain pattern
* Using the BitTorrent protocol for rapid deployment in a large-scale production.

## Product

### Product line-up
* LXC Cloud Storage
  - Every user owns their repositories for storing their LXC images.
  - Every user also can have private repositories.
  - No limitation of the number of repositories.
* LXC Cloud Storage for Enterprise
  - for Enterprise
  - Using the BitTorrent protocol for rapid deployment in a large-scale production.
* Cosmos
  - A cluster management
  - No dependency for a certain infrastructure
  - No dependency for a certain operating system
* Cosmos Telescope
  - Every user owns a single dashboard for their infrastructures and servers.

### Development roadmap
* 2014.12  start to develop the LXC Cloud Storage.
* 2014.12  start to research a distributed file upload & download protocol such as BitTorrent
* 2015.02  The LXC Cloud storage is open to the Cosmos.
* 2015.03  start to develop the LXC Cloud Stoage for Enterprise.
* 2015.04  The LXC Cloud storage is alpha to the public.
* 2015.05  The LXC Cloud storage for Enterprise is open to the Cosmos.
* 2015.06  The LXC Cloud storage is beta to the public.
* 2015.07  The LXC Cloud storage for Enterprise is alpha to the public.

## Business model
* Pricing plan for private repositories
  - USD $1 per a private repository per a month
  - If 10,000 private repositories, USD $10,000
* Selling a LXC Cloud Storage for Enterprise
  - At least USD $5,000 per a data center per a month
  - It depends on a scale.

# Team
* Founders
  - Hancheol Lee (Former Senior Software Engineer at Enswers, wemakeprice, Waplestore, BananaWiki)
* Board of advisors
  - Sherman Li (President at Enswers America)
* Members
  - David Lonjon (Former Senior Software Engineer at Enswers)
  - Nikolay Dubina (Former Senior Research Engineer at Enswers)
  - Jihoon Park (Former Senior Software Engineer at SKPlanet, wemakeprice, Waplestore, BananaWiki)
  - Hanjae Lee
  - Dongju Jang
  - Kyle Kim
  - Min Kim
  - Jooyeon Maeng (Former PR at Prain Global, Waplestore)

## Financials

### Expected cost
* Principal Software Engineers
  - USD $7,800 per a principal software engineer per a month
  - If 1, USD $93,600 per a year
* Senior Software Engineers
  - USD $4,000 per a senior software engineer per a month
  - If 4, USD $192,000 per a year
* Software Engineer
  - USD $2,000 per a software engineer per a month
  - If 1, USD $ 24,000 per a year
* Cloud Storage Servers
  - Will spend lots of cloud storages.
  - A LXC image is mostly 0.4 GB.
  - If 10,000 private repositories, expected 4,000 GB.
  - on Amazon Web Services S3, expected only USD $120 per a month.
* Cloud Computing Servers
  - USD $9.36 per a month per a EC2 t2.micro
  - USD $9.36 per a month * 10 = USD $93.60 per a month
* SSL certificate Wildcard
  - USD $94.00 per a year
* cosmos.io domain
  - USD $39.00 per a year
* Google Apps for Work Unlimited
  - USD $10 per a user per a month
* Slack Standard Plan
  - USD $8 per a user per a month

### Expected income
* LXC Cloud Storage
  - 10,000 private repositories
  - USD $10,000 per a month - USD $120 per a month = USD $9,880 per a month