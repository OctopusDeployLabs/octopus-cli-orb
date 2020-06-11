# Octopus CLI Orb [![CircleCI Build Status](https://circleci.com/gh/OctopusDeployLabs/octopus-cli-orb.svg?style=shield "CircleCI Build Status")](https://circleci.com/gh/OctopusDeployLabs/octopus-cli-orb) [![CircleCI Orb Version](https://img.shields.io/badge/endpoint.svg?url=https://badges.circleci.io/orb/octopusdeploylabs/octopus-cli)](https://circleci.com/orbs/registry/orb/octopusdeploylabs/octopus-cli) [![GitHub License](https://img.shields.io/badge/license-MIT-lightgrey.svg)](https://raw.githubusercontent.com/OctopusDeployLabs/octopus-cli-org/master/LICENSE) [![CircleCI Community](https://img.shields.io/badge/community-CircleCI%20Discuss-343434.svg)](https://discuss.circleci.com/c/ecosystem/orbs)

Experimental orb for working with the Octopus CLI. This orb is provided as-is, with no support available.

Email circleci@octopus.com if you have questions about the orb.

This is a proof of concept orb for integrating CircleCI and Octopus Deploy.

The orb exposes the following functions from the Octo CLI: build-information, create-release, deploy-release, pack, promote-release, and push.

## Usage

Example use-cases are provided on the orb [registry page](https://circleci.com/orbs/registry/orb/octopusdeploylabs/octopus-cli#usage-examples). Source for these examples can be found within the `src/examples` directory.

## Limitations

`build-information` does not include commits or work-items.

Providing parameters multiple times to a command (--package on `create-release` for example) is not supported.

The commands have to be run on the Bash shell.

## Resources

[CircleCI Orb Registry Page](https://circleci.com/orbs/registry/orb/octopusdeploylabs/octopus-cli) - The official registry page of this orb for all versions, executors, commands, and jobs described.
[CircleCI Orb Docs](https://circleci.com/docs/2.0/orb-intro/#section=configuration) - Docs for using and creating CircleCI Orbs.

## License

[MIT](http://www.opensource.org/licenses/mit-license.html)

## Disclaimer

No warranty expressed or implied. Software is as is.
