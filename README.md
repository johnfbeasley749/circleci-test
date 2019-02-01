# CICDtestapp: build, test, deploy, mesure 
this is a test application to verify automated steps for: commit, build, test and deploy process

Application is a simple "hello world" app for testing CI/CD pipeline implementation.
1. developer commits to a shared mainline
2. commit triggers automated build and test
If build and test:
- fails, it’s repaired imediately (back to step 1)
- pass, it's deployed to staging env for testing, following production env push and verification

circleci pipline examples https://circleci.com/docs/2.0/sample-config/
