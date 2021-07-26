The following is a checklist of different good practices that i have learnt from my different work stunts and online readings. 

this checklist covers the code development aspect of software development. i.e HOW software or infrastructure works eg monitoring, logging are out of scope. the purpose is to cover how to ensure a team of engineers contribute to a code base and deploy it the correct environments in a sensible and meaningful process. 

this is not meant to be a definitive exhaustive guide. but in general, fulfilling these checks should ideally be considered a baseline of software development practices. for larger teams with multiple subteams or feature teams, the checklist should be used to assess each team atomically. 

# Tests

- [ ]  do you have unit tests?
- [ ]  do you have integration tests
- [ ]  do you have end-to-end tests?
- [ ]  are you automating testing
- [ ]  do you track test coverage?

# Quality

- [ ]  do you have code styles established
- [ ]  do you have linting in place
- [ ]  are you automating linting
- [ ]  do you track code quality
- [ ]  do you automate code quality checks eg sonarqube

# Security

- [ ]  do you implement secret detection? (detect-secrets by yelp)
- [ ]  do you sign your commits
- [ ]  do you prevent force pushes to critical branches
- [ ]  do you run SAST on your code base regularly

# Planning

- [ ]  do you have an engineering roadmap
- [ ]  do you use an appropriate tool to manage the roadmap?
- [ ]  can you use the tool to hold people accountable to the roadmap?
- [ ]  do you use the tool to estimate engineering load and velocity?

# Source Code Management

- [ ]  do you use a source code management tool eg. github
- [ ]  do you have a formalised structure for PR issues
- [ ]  do you use a PR template
- [ ]  do you do peer review before merging
- [ ]  are your PR sizes manageable ie <300 lines of change
- [ ]  do you follow conventional commits for your commit structures
- [ ]  do you enforce commit linting
- [ ]  do you have a formal branching strategy
- [ ]  are you using releases
- [ ]  do you use semantic versioning

# Deployment

- [ ]  do you build regularly eg weekly, daily
- [ ]  do you use a CI/CD tool to deploy automatically
- [ ]  are your branches tied to specific environments
- [ ]  can you rollback in a single step

# Documentation

- [ ]  do you have api documentation eg swagger
- [ ]  do you have a architecture diagram
- [ ]  do you document the lifecycle of your different processes
- [ ]  do you document coding styles and guidelines
- [ ]  must documentation be done before it can be merged
