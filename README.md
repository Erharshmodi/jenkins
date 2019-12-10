# jenkins
Generic implementation of jenkins pipeline for continuous delivery.

# Problem Statement:

  1. Need for a generic impelementation of a jenkins pipeline to ensure that the code is:
      i. Continuously Integrated
      ii. Continuously Deployed
      iii. Continously Delivered
  2. Integrety of the code should be maintained, i.e. the code that is on Dev should be pushed subsequently to further enviornments.
  
# Solution:
  1. Dev environment is built by the user after choosing a git branch and is deployed in the Dev enviornment.
  2. For every other enviornment, the code from the previous environment is pushed forward, i.e., from Dev to SIT, from SIT to QA and so on.
