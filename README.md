# Environment Manifest file for C-19 Benefit Finder

This repository is used to deploy to our staging environment and acts as a way to see what version is currently running in production. It is also used as an audit log to track releases of the application.

## How to deploy to staging.

1. Create a new branch
1. Update the manifest.json with the version you wish to deploy
1. Create a Pull Request, the description should outline the new features you wish to release
1. Get approval from the individual with the delegated authority to release to production.

Upon Merging to the mainline code branch the version of the application will be deployed to the staging environment where you can perform a final smoke test before releasing to production.

