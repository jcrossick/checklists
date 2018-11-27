How many of these does your team follow?

Not that your team _should_ follow them all. Pick and choose the ones that work for you

### Code static analysis
- [ ] Linting runs as part of pipeline
- [ ] Code quality analysis in place (e.g. CodeClimate)
- [ ] Code quality scores in pipeline/run regularly and used for incremental improvements

### Unit testing
- [ ] Unit testing framework in place
- [ ] Unit testing run in pipeline
- [ ] 80%+ coverage
- [ ] 100% coverage
- [ ] 100% coverage + negative scenarios
- [ ] Snapshot testing if applicable

### Integration testing
- [ ] Integration testing framework in place
- [ ] Integration testing run in pipeline
- [ ] Tests have well-defined and complete stubs or mocks for external systems
- [ ] Tests run in <10 mins
- [ ] High coverage
- [ ] High coverage + negative scenarios

### Journey testing
- [ ] Journey testing framework in place
- [ ] Journey tests run in pipeline
- [ ] Tests run in <20 mins
- [ ] High coverage
- [ ] Automated visual regression testing (e.g. using BackstopJS)
- [ ] Well-structured and maintained manual regression testing

### Nonfunctional testing
- [ ] Security static analysis in place
- [ ] Security static analysis run in pipeline
- [ ] Performance, load, stress and soak testing framework in place
- [ ] Performance, load, stress and soak testing run frequently against defined metrics/expectations
- [ ] Agreed approach to full security & pen testing/review, using 3rd parties where appropriate
- [ ] Accessibility analysis in place and runs as part of pipeline. (e.g. pa11ly / a11ly )

### Code repository
- [ ] SCM in place with well-understood branching/collaboration rules (I advocate for trunk-based development over branching)
- [ ] Code versioning/tagging strategy in place
- [ ] Automated tagging and version management

### Configuration management
- [ ] A structured approach to configuration management, including environment variables and IAM.
- [ ] Configuration fully scripted and automated
- [ ] Configuration stored securely as required (e.g. KMS, Vault)

### Pipeline
- [ ] Basic build and test pipeline in place (e.g. Jenkins, CircleCI)
- [ ] Deploy automation/basic CD pipeline in place
- [ ] Sophisticated multi-stage build, test and deploy pipeline in place
- [ ] Pipeline runs quickly and is fit for purpose
- [ ] Visible and reliable notification of failures
- [ ] Roll-back capabilities in place

### Deployment
- [ ] Deployments are semi-automated
- [ ] Deployments are fully automated in all environments
- [ ] Zero downtime deployments
- [ ] Canary or A/B deploys

### Infrastructure
- [ ] Simple environment structures with basic scripting in place
- [ ] 100% scripted environments (IaC) with pipeline in place
- [ ] Sophisticated infrastructure architecture with relevant security measures and full implementation of least privilege.
- [ ] Static analysis and testing of IaC
- [ ] Infrastructure auto-scales according to demand
- [ ] DDoS protection and CDN in place
- [ ] Zero downtime infrastructure deployments

### Monitoring
- [ ] Basic automated status monitoring on key resources/endpoints
- [ ] Application logs captured and centralised
- [ ] Application logs searchable and monitorable (basic dashboards)
- [ ] Infrastructure logs captured and centralised
- [ ] Infrastructure resource usage monitored 
- [ ] Sophisticated dashboards and alerting
- [ ] Basic self-heal in place
- [ ] Intelligent threat/suspicious behaviour monitoring

### Architecture and code
- [ ] Basic target application & solution architecture in place and communicated
- [ ] Sophisticated target application & solution architecture in place and communicated
- [ ] Coding standards and design in place and adhered to
- [ ] Feature flags in place and managed well
- [ ] Performance tuning carried out regularly

### Data storage
- [ ] Data server/technology choice has been considered and is fit for purpose
- [ ] Database server is scripted
- [ ] Database structure/schema is scripted
- [ ] Database DDL migration is scripted
- [ ] Database test and reference data is scripted
- [ ] Database is performance tuned and scalable
- [ ] Database has backup, failover and replication processing in place
- [ ] Database access is securely controlled - IAM, password management, etc.

_Please feel free to contribute. If you use it, please reference this copy_
