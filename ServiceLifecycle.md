# The Lifecycle of A Service

* Service ownership means people take responsibility for what they deliver at every stage of the lifecycle
* What is a service?
    * Microservice
    * Slice of a monolith
    * Internal tool
    * Piece of functionality
    * Shared infra
* Define what a "service" means to you?
* Shared understanding
    * Who is responsible?
    * "Service mitosis" - If multiple teams share responsibility, split the code
    * Service defintitions help with problem resolution
    * Your service should make sense to other people who will interact with it
    * Naming
        * Be specific
            * Ex of specifics: user auth
            * Ex of less specifics: Pcman,bergunDB
* API
    * Versioning
    * Clear documentation/examples
* Sustainability team
    * Runbooks
        * Make sure they are updated regularly
    * Alerting
        * Alert only on things that are actionable
    * Resiliency (but really Robustness and Reliability)
    * Program Mgmt
        * Proactive maintainence based on postmortem
        * Define what done is
    * Product owner
        * Customers are always asking for uptime, performance, and security - they just don't usually use those words
    * Senior Leadership
        * Set goals, draw roadmap
* A brief overview of SLA/SLI/SLO
    * SLI
        * Latency
        * Throughput
        * Availability
    * SLO
        * Made up of SLIs
    * SLA
        * Agreed with users
* The "hadness" point
* Alert on SLO
* Investigate patterns, build from post mortems
* What alerts do you actually need? , again build from post mortems and PRRs
* Supression of non-actionable alerts
* Understand business impact - How does the service impact the business
* Lifecycle steps
    * Design a new service
    * Maintaing and Iterating
    * Retiring a service
        * Deprecate then turning off a service 