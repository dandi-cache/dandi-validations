# DANDI Cache: DANDI Validations

Derivative dataset of validation outputs for all published Dandiset versions.

Updated frequently.

Used as evidence in the design document proposing enhancements to validation of assets on the DANDI Archive.



# Note: Self-hosted runner

The original design of this repository was to use a self-hosted runner to run the update scripts.

This is because the runner in question has direct access to a copy of all of the blobs on the archive, which reduces the need to transfer any data to the runner environment.

Because of this, pull requests are not allowed on this repository to prevent accidental approval of random workflow executions from forked PRs.
