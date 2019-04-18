# contrast-security-orb
boilerplate for possible CircleCI Technology Partner orb with Contrast Security

## questions
1. there's a reference to a `teamcity.agent.hostname` value in the `check-vulnerabilities.yml` job, & i'm not sure what that's doing—maybe the circleci instructions have some boilerplate left-over from an instructions guide for use with teamcity? for now, i left that code as-is, because i wasn't sure what else to do with it
2. i suspect you may want to parameterize the `env.$CIRCLE_BUILD_NUMBER` code in the `check-vulnerabilities.yml` job, just in case folks organize their contrast data in a slightly different way than you recommend in your guide

## next steps
- https://circleci.com/docs/2.0/creating-orbs/#orbs-quickstart
- https://circleci.com/blog/creating-automated-build-test-and-deploy-workflows-for-orbs
