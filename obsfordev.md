# Observability for Developers

* Biggest improvement came from talk about the application in the context of resources
    * First Wave: gettign ops folks to code
    * Second Wwave: Devs owning their code in prod
* Observability is about improving good processes to build good environments
* Obs is also good for developers getting better in prod
* Developers observing code in production is important
* What code to write
    * Determine what based on user experience
        * What good is
        * What bad is
    * Understanding whats happening in the real world
* Whether the code works
    * Many failures are unpredictable or not common enough for testing
    * Evaluate whether small change improves the environment
* Make prod feel more like dev
    * One step at a time
        * Start from the edge (breadth) - ex. ELB logs, HTTP handler
        * Cocus on the pain (depth) - ex. Instrument one endpoint and only do what is useful for the team
        * Instrument from where you control
        * Capture what matters to you (context)

