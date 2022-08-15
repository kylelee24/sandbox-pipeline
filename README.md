# GitHub Actions Starter Pipeline Template

## Description

This pipeline is intended to be the golden baseline template for GitHub Actions workflows (pipelines). This uses [reusable workflows](https://docs.github.com/en/actions/using-workflows/reusing-workflows).

The pipeline template supports:

* Triggers:
  * Manual
  * On push (with ignored paths)
* Reusable workflows
* Environments
* Inputs (parameters)
* Runs-on (pipeline agent)

## Backlog

- Global environment variables. This doesn't seem to be possible with reusable workflows. Several possible workarounds have been tested which do not seem to work. Needs more investigation. 
