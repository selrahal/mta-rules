# mta-rules

## Apps

The `apps/` folder contains mapping files that are used to locate binary artifacts.
These urls can be in an internally hosted artifact repository (such as Artifactory or Nexus) or a public one like Maven Central.
Different files should be used to represent different application owners and their estate of applications.


## Rules

The `rules/` folder contains custom cloud-maturity rules as well as automatic remediations in the form of OpenRewrite specs.
Any MTA rules placed underneath the `rules/` folder will automatically get included and used in assessments.
Likewise, any OpenRewrite recipes in the folder will be available for remediation.
