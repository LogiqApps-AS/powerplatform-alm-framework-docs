# ALM Self-Assessment Checklist

## Solution Management

* Solution boundaries are defined and related to the business domain
* Solution.zip files and their contents are never manually edited

## Version Control

* Solutions are unpacked using the Solution Packager and version controlled in a\
  repository such as Azure DevOps, GitHub, etc.

## Build Management

* Solutions are built through an automated process that invokes the Solution Packager\
  to repack the solution into a Solution.zip file

## Test Management

TBD

## Deployment Management

* Only managed solutions are deployed to QA/Staging/Production environments
* All solutions are deployed via the Package Deployer
* No unmanaged changes are made directly to environments downstream of\
  development
