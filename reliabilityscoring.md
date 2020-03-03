# Reliability Scoring: A 3-Part Formula for Promoting Reliable Code

* Evaluating release stability and quality
* Preventing SEV1s
* Using quality gates in CI/CD pipeline
* Speed and stability are at odds in the SDLC
* Cost of poor quality software is growing - $2.8T in 2018
* SEV1 impacts customer loyalty and the bottom line
* How are orgs addressing this today?
    * "You build it, you run it" - Verner Voegls - Increases Accountability
    * Shift Left approach to software quality
    * Shift Right approach to test in production
* Measuring software quality is all about good data
* Types of Data
    * Conventional
        * Static analysis
        * Code coverage
        * Log files
    * New Approach
        * New errors
        * Increasing errors
        * Slowdowns
* The reliability score
    * A release is scored for stability and saftey based on if it:
        * Intorduces new errors
        * Increased error
        * Added slowdowns
* The scoring process
    * Detect all errors and slowdowns
    * Classify each event
    * Prioritize by severity
    * Score the build
    * Block builds
    * Visualize the data
* Detection
    * Youre only as good as the data you collect
        * Manual
            * Metric libraries
            * Log files
        * Automatic
            * APM
            * Log aggregators
            * Error tracking
