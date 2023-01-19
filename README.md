# Spectacles Style Rules

This repository contains the YAML rule definitions for the [Spectacles](https://spectacles.dev) Style Validator. The Style Validator is a style checker/linter for Looker and LookML.

These rules define stylistic preferences for [LookML](https://looker.com) that the Spectacles Style Validator uses to check LookML for violations.

To override a rule for your Looker project, copy the YAML for a rule into the `custom_rules` section of your `lkmlstyle.yaml` configuration file, then make the desired modifications.

For example, you could modify a rule that checks that `count`-type measures have names starting with `count_` to check for names starting with `c_`.

## Contributing

Please feel free to open Pull Requests if you've created or modified a rule in an interesting way that you think the Looker Community could benefit from.
