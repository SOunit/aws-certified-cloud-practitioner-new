# operational excellence

- includes the ability to run and monitor systems to deliver business value and to continually improves supporting processes and procedures
- design principles
  - perform operations as code
    - infrastructure as code
      - AWS CloudFormation
  - Annotate documentation
    - automate the creation of annotated documentation after every build
  - make frequent, small, reversible changes
    - so that you can reverse it when fail
  - refine operations procedures frequently
    - ensure that team members are familiar with it
  - anticipate failure
    - learn from all operation failures

# Operational Excellence in AWS services

- Prepare
  - AWS CloudFormation
  - AWS config
    - evaluate AWS CloudFormation configuration
    - not covered in this course though
- Operate
  - AWS CloudFormation
  - AWS config
  - AWS CloudTail
    - track all API call?
    - make sure nothing is done manually?
  - Amazon CloudWatch
    - monitor performance to see what you should improve
  - AWS X-Ray
    - monitor http request
    - not covered in this course
- Evolve
  - AWS CloudFormation
  - CI/CD tools
    - build, commit, deploy, pipeline faster
      - AWS CoreBuild
      - AWS CodeCommit
      - AWS CodeDeploy
      - AWS CodePipeline
