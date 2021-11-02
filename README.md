# Links_on_Distributed_Systems_and_Design

Distributed consensus made simple (for real this time!)
https://decentralizedthoughts.github.io/2021-09-30-distributed-consensus-made-simple-for-real-this-time/

List of must reads on Distributed Systems and Design
How Web Browsers work -- https://github.com/vasanthk/how-web-works

Thundering Herd Problem --
https://en.wikipedia.org/wiki/Thundering_herd_problem
https://www.nginx.com/blog/mitigating-thundering-herd-problem-pbs-nginx/#thunderingherd  --> Go through the youtube presentation

Rate Limiting --
https://stripe.com/blog/rate-limiters
https://nordicapis.com/everything-you-need-to-know-about-api-rate-limiting/
https://www.ably.io/blog/distributed-rate-limiting-scale-your-platform/
https://cloud.google.com/solutions/rate-limiting-strategies-techniques
https://konghq.com/blog/how-to-design-a-scalable-rate-limiting-algorithm/
https://blog.getambassador.io/rate-limiting-a-useful-tool-with-distributed-systems-6be2b1a4f5f4
educative.io's "Grokking the System Design Interview" has a chapter dedicated to designing rate-limiters

Articles from Rubrik's Blog --
https://www.rubrik.com/blog/introducing-atlas-rubriks-cloud-scale-file-system/

CQRS pattern --
Very good link on CQRS pattern(separate read and write data models and keep them in sync using Event Sourcing pattern)
https://docs.microsoft.com/en-us/azure/architecture/patterns/cqrs
Read all the other patterns, very important
https://martinfowler.com/bliki/CQRS.html --> references a lot of other patterns at the end
http://codebetter.com/gregyoung/2010/02/16/cqrs-task-based-uis-event-sourcing-agh/ -- perhaps the best of all
http://udidahan.com/2009/12/09/clarified-cqrs/

2020-07-31 --
[RR] https://kislayverma.com/programming/design-review-checklist-for-distributed-systems/
Very good description of basic design guidelines that should be followed when designing a large distributed system. 

2020-08-01
Very short and simple introduction to API Gateways (just a description and their multiple purposes) -- 
https://www.redhat.com/en/topics/api/what-does-an-api-gateway-do

2020-08-12
[MUST_READ]
This is the best short introduction to the problem of database replication (author chose to call synchronization) and the solutions (including use of consensus protocols)
https://www.alibabacloud.com/blog/strategies-for-effective-database-synchronization_152131?spm=a2c65.11461447.0.0.42576a34ztIwC6

2021-03-04
Design of P2P File Transfer Networks --

Peer-to-Peer Networks for Content Sharing
http://cloudbus.org/papers/P2PbasedContentSharing.pdf

Design and Implementation of a Peer-to-Peer based System to enable the Share Functionality in a Platform-independent Cloud Storage Overlay
https://www.merlin.uzh.ch/contributionDocument/download/4930

Very Good Introduction to API Gateway --
https://nordicapis.com/what-is-an-api-gateway/
