# Setup Git Hooks
This script is intended to allow all team members to quickly
configure cloned projects so that they can follow project
quality requirements with minimal effort.

## Configured Hooks
These are the configured hooks

### Pre-commit
* Run clang-format against project using .clang-format file in project root

## Setup process
These are the step run by the setup script

### clang-format
* Download / Install required version of clang-format
* Add pre-commit hook to the .git/hooks directory
