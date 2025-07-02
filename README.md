# What about a #BigTech style open-source development ecosystem for Go?

![](./images/welcome.webp)

I'm working on a #BigTech style open-source development ecosystem that will 
take care of every detail of the development cycle, you simply clone, add 
your API handlers code into the provided API template and everything around it, 
is handled for you automatically, 

[here is an article describing the entire ecosystem.](https://medium.com/@earcamone/what-about-an-open-source-bigtech-style-development-ecosystem-for-go-024263853a35)

Its composed of four self-contained modules you can use separately in your 
own project or clone the projects main module which leverages the four of 
them all together:

- [Full Featured CI/CD GitHub Actions Workflow](https://github.com/earcamone/gwy): "clone and forget" full-fledged 
and easy to configure GitHub Actions CI Pipeline for Go applications that 
guarantees the integrity of the development cycle: unit tests and coverage 
check, hardcoded secrets, vulnerabilities and outdated dependencies scan, 
automatic releases to AWS/ECR (among other features).

- Multi-Cloud Terraform Deployment Framework: cloud-agnostic deploy solution 
with blue/green strategies and rollback support. Enables zero-downtime deploys 
by simplifying application configuration, abstracting cloud-specific complexity
across multiple platforms.

- Reusable Go API: modular, clone-and-extend Go API template with centralized
error handling and flexible rate-limiting (per IP, endpoint, or combined), 
project leverages the previous described ones to build a reusable among teams 
“BigTech style” development ecosystem.

- Go Integrations API Framework: declarative, standardized Go framework for 
rapid development of integration APIs with minimal code.
