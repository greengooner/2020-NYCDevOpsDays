# CI/CD Agility & Controlling Pipeline Sprawl

* Tooling Obsticles
    * Managing Pipelines at Scale
        * Security
            * Secrets - exposed in pipeline, weak, stale
            * How to protect Secrets?
                * Secrets Management tooling
                    * Utilized policy 
                    * Random Password Generation
                    * Auto Rotate Passwords
        * Pipeline Sprawl
            * Lives in configuration files
            * Use yaml for the configuration files
            * yaml is a data structure
            * Syntax can be redundant
            * yaml will grow and becomd complex
            * 1 config file per repo
            * Gitops?
            * Create abstratction Common pipeline patterns
            * 
            * parameterized
            * Don't hardcode yaml
            * Create pipeline libraries
            * Using scripts that can utilize envi vars
            * Centrally managed functionality
            * Creates portability and mnimize vendor lockin
            * CircleCI created orbs to do the abstraction for yaml
            