# *Awesome* Data Contracts

Data contracts is an amazing initiative to bring data producers and data consumers together. This is a curated list of awesome articles, tools, resources that will help you understand concepts and start your data contracts journey.

- [*Awesome* Data Contracts](#awesome-data-contracts)
  - [Articles and Blogs](#articles-and-blogs)
  - [Videos](#videos)
  - [Podcasts](#podcasts)
  - [Tools](#tools)
  - [Related Blogs](#related)
- [Contributing](#contributing)

## Articles and Blogs

- [Improving data quality with data contracts (GoCardless)](https://medium.com/gocardless-tech/improving-data-quality-with-data-contracts-238041e35698) What are data contracts and GoCardless implementation of data contracts
- [Interfaces and Breaking Stuff by Tristan Handy (CEO, DBT)](https://roundup.getdbt.com/p/interfaces-and-breaking-stuff) Need of data contracts as data interfaces and analogy with software APIs
- [Implementing data contracts at GoCardless](https://medium.com/gocardless-tech/implementing-data-contracts-at-gocardless-3b5c49074d13) Data contract specification examples from GoCardless systems
- [7 key learnings from implementing data contracts (Bar Moses and Andrew Jones)](https://barrmoses.medium.com/implementing-data-contracts-7-key-learnings-d214a5947d5e) Sample data contract example and learnings from implementations
- [A PM's thoughts on data contracts](https://pmdata.substack.com/p/a-pms-thoughts-on-data-contracts) A product manager’s view on data contracts and challenges they can solve
- [Engineer’s guide to data contracts part I - entities](https://dataproducts.substack.com/p/an-engineers-guide-to-data-contracts?utm_source=substack&utm_campaign=post_embed&utm_medium=web) covers implementing data contracts for entities
- [Engineer’s guide to data contracts part II - application events](https://dataproducts.substack.com/p/an-engineers-guide-to-data-contracts-6df?utm_source=profile&utm_medium=reader2) cover enforcing and monitoring data contracts using transactional outbox pattern
- [Data Contracts: The Mesh Glue](https://towardsdatascience.com/data-contracts-the-mesh-glue-c1b533e2a664) Scope of data contract and how it can be a layer with data mesh architectures
- [Yet another post on data contracts - part I](https://davidsj.substack.com/p/yet-another-post-on-data-contracts) Thoughts from David J. on what is data contracts and what it should contain
- [Yet another post on data contracts - part II](https://davidsj.substack.com/p/yet-another-post-on-data-contracts-9f0) What kind of data should be covered by data contracts and some highlights of tooling that’s available
- [Yet another post on data contracts - part III](https://davidsj.substack.com/p/yet-another-post-on-data-contracts-dad) Deeper dive on current tooling that can be used for data contracts implementation
- [Are we setting data contracts in the right place?](https://petrjanda.substack.com/p/the-art-of-drawing-lines?ref=Data+News-newsletter)  Considerations and analogies from software architecture world while defining data contracts
- [Implementing data contracts](https://medium.com/@danthelion/implementing-data-contracts-82800b9186b) Specifications and real world architecture example of data contract implementation
- [The best data contract is the pull request](https://www.datafold.com/blog/the-best-data-contract-is-the-pull-request) Datafold’s view on how the best data contract is pull request
- [An open letter to data ninjas - yes, you need to implement data contracts](https://www.dataengineeringweekly.com/p/an-open-letter-to-data-ninjas-yes) View on implementations and specifications of data contracts
- [Data person: attorney at law](https://stkbailey.substack.com/p/data-person-attorney-at-law) Interesting view on data contracts which turn data engineers into data lawyers by Stephen Bailey
- [Demystifying event streams](https://docs.getdbt.com/blog/demystifying-event-streams) - New event streams model at Merit and event specifications being treated as data contracts - named OMG contract
- [Fine let’s talk about data contracts](https://benn.substack.com/p/data-contracts) - Different view on viability and usability of data contracts
- [Brain, kidney, cancer research and data contracts](https://www.dataengineeringweekly.com/p/brain-kidney-cancer-research-and) ([Schemata project](https://github.com/ananthdurai/schemata)) - Example of data contract explanation / discussion in simple terms for people outside of data space
- [The rise of data contracts](https://dataproducts.substack.com/p/the-rise-of-data-contracts) - (Q/A style article on what are data contracts and why we need them) 
- [Data contracts from zero to hero](https://link.medium.com/rC07GQaW2ub) - a pragmatic approach to data contracts
- [Data contracts: ensure robustness in your data mesh architecture](https://link.medium.com/Bo7JOVnW2ub) - Data contracts as part of metadata driven ingestion network
- [Implementing data contracts](https://medium.com/@danthelion/implementing-data-contracts-82800b9186b) - Implementing basic schema based data contract with Kafka schema registry
- [Data contracts wrapped 2022] - Data contracts creation, storage, enforcement and application
- [McDonald's event driven architecture and data journey] - Use of data contracts in McDonald's event driven architecture


## Videos

- [Inventing data contracts and building data for a FinTech unicorn with Andrew Jones of GoCardless](https://www.youtube.com/watch?v=xv0s_byNmzw)
- [Data contracts and domain ownership](https://www.youtube.com/watch?v=HsfvZ1D5mDU)
- [How data contracts can kill innovation](https://accelerationeconomy.com/data/data-revolution-minute/how-data-contracts-can-kill-innovation/)
- [Getting jiggy with jsonschema: The power of contracts for building data systems](https://www.youtube.com/watch?v=s6iy0hqjcLk)
- [Data Contracts: Accountable Data Quality w/ Chad Sanderson - UDEM October 2022](https://www.youtube.com/watch?v=2U4g4YaQDTc)
- [Data Contract Battle Royale w/ Chad Sanderson vs Ethan Aaron](https://www.youtube.com/watch?v=4BEpYAp3Qu4)
- [Driving ML data quality with data contracts](https://home.mlops.community/home/videos/driving-ml-data-quality-with-data-contracts)

## Podcasts

- [Why You'll Need Data Contracts (w/ Chad Sanderson + Prukalpa)](https://open.spotify.com/episode/65Hs5C3yAJI138ZAGPdHhd)
  - The Analytics Engineering Podcast (11/18/2022)
- [Data Contracts & Domain Ownership w/ Ananth Packkildurai](https://open.spotify.com/episode/3agnuRLuIDDsJCdvRmPzp4?si=wXaz3bf_Qqq34fe5prQORw)
  - Monday Morning Data Chat (5/24/2022)

## Tools

- [Avo.app](http://Avo.app) - Avo is a data governance platform that error-proofs your analytics events and speeds up implementation.
- [Reflekt](https://github.com/GClunies/Reflekt) - Define tracking plans as code for analytics
- [Iteratively](https://iterative.ly/) - Bring your data teams, product managers and engineers together to define, instrument, verify and collaborate on analytics tracking
- [Buz](https://buz.dev/) - Buz collects, validates, and delivers schematized data to where it needs to bee
- [Benthos](https://github.com/benthosdev/benthos) - Benthos is a high performance and resilient stream processor, able to connect various sources and sinks in a range of brokering patterns and perform hydration, enrichments, transformations and filters on payloads.
- [Schemata](https://github.com/ananthdurai/schemata) - Schemata is a schema modeling framework for decentralized domain-driven ownership of data. Schemata combines a set of standard metadata definitions for each schema & data field and a scoring algorithm to provide a feedback loop on how efficient the data modeling of your data warehouse is.

## Related

- [Establish formal data contracts between consumers and producers](https://blogs.perficient.com/2018/08/02/establishing-formal-data-contracts-between-data-owners-data-consumers/) Older article from 2018 that explored the concept of data contracts (Older generation article)
- [Data Mesh — A Data Movement and Processing Platform @ Netflix -](https://netflixtechblog.com/data-mesh-a-data-movement-and-processing-platform-netflix-1288bcab2873) Schema enforcement in Netflix’s data mesh platform

# Contributing

**Your contributions are most welcome!** Please go ahead and create a pull request. We'll review each and every one. We will keep some pull requests open if we not sure whether the PRs are awesome or relevant, you could vote for them by adding 👍 to them. Pull requests will be merged when their votes reach 5.
