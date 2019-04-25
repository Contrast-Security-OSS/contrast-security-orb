# contrast-security-orb

Contrast Ecurity Orb for CircleCI

## Begin

Download the CircleCI command line tool: https://circleci.com/docs/2.0/local-cli/

## Building

`circleci config pack src/ > orb.yml`

## Releasing

`circleci orb publish orb.yml contrastsecurity/verify@0.0.5`