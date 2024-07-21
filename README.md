# sample_test-prod-auto-deploy
Testing out my Github Actions to auto deploy from TEST to PROD by auto merging branches, if the commit is considered safe to be deploy automatically. This is a simple github repo just to see how quickly I can have this feature if I start from scratch

- `MAIN` is always ahead or on-par with `PROD`

## Working
### Auto merge to `prod` if PR to `main` contains "SAFE" changes
- https://github.com/nvatuan/sample_test-prod-auto-deploy/pull/50
- https://github.com/nvatuan/sample_test-prod-auto-deploy/pull/51

### Not automerge when changes are not in `.github/workflows/misc/auto-deploy-prefix.txt`
- https://github.com/nvatuan/sample_test-prod-auto-deploy/pull/63
- https://github.com/nvatuan/sample_test-prod-auto-deploy/pull/62
