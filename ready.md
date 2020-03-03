# Are you ready for production?

* Production can be intimidating, especially for new comers
* Are we ready to push to production?
* Whats good or bad when operating services?
* How do we transfer knowledge?
* How do we learn from failure?
* Production Readiness
* When to evaluate production readiness?
    * Various times in lifetime of a service
        * Launching a new service, introducting prod readiness to an existing service
* Checklist
    * Design
    * Development
    * Config mgmt
    * Release mgmt
    * Observability
    * Security
    * Cap planning
* Why review?
    * Engineers dont feel confident as the cycle grows organically
    * Trial and Error culture makes finger pointing common
* PRR (Reviews)
    * Checklist or Questionaire
    * Manually, Automatically, or both
    * Templates created as needed
* Example Checklist
    * Design and dev
        * Have reproducible builds
        * Define and set SLO for service at design time
        * Document availability
    * Configuration
        * Static, small, and non-secret configuration can be flags
        * Use a configuration devlivery service for everything else
    * Release Mgmt
        * Doc release process, metrics, canary release process, revert canaries, 
    * Observability
    * Security
        * Ensure proper IAM, Encryption, etc
        * Sanitize user input, payload restrictions, etc
    * Capacity planning
        * Document scaling, requirements, etc
* Where to start?
    * Teamwork!
    * Research practices that apply, consult domain experts
    * Start discussions early
    * Learn from failure, Share knowledge!
    * Enforce prod readiness practices
* Continue Evaluating and Remove/Add items as relevent
* Reviews can increase velocity
    * Faster design decisions
    * Faster troubleshooting
    * Faster onboarding
* Make sure it's more than checking boxes!
* Avoid making it boring and repeditive
* Help teams be confident, reduce mistakes, and help onboarding