# contrast-security-orb
boilerplate for possible CircleCI Technology Partner orb with Contrast Security

## questions
1. [there's a reference](https://github.com/iynere/contrast-security-orb/blob/a6e78db8013015277f5d37804581aeaf0f7abc12/commands/check-vulnerabilities.yml#L85) to a `teamcity.agent.hostname` value in the `check-vulnerabilities.yml` command, & i'm not sure what that's doing—maybe the circleci instructions have some boilerplate leftover from an instructions guide for use with teamcity? for now, i left that code as-is, because i wasn't sure what else to do with it
2. i suspect [you may want to parameterize](https://github.com/iynere/contrast-security-orb/blob/a6e78db8013015277f5d37804581aeaf0f7abc12/commands/check-vulnerabilities.yml#L109) the `env.$CIRCLE_BUILD_NUMBER` code in the `check-vulnerabilities.yml` command, just in case folks organize their circleci data in contrast in a slightly different manner than what you recommend in your guide

## next steps
- https://circleci.com/docs/2.0/creating-orbs/#orbs-quickstart
- https://circleci.com/blog/creating-automated-build-test-and-deploy-workflows-for-orbs
