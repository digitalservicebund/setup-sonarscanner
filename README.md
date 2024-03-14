# Setup SonarScanner

Install [SonarScanner](https://github.com/SonarSource/sonar-scanning-examples) in your pipeline.

## How to use

```yaml
- name: Install SonarScanner
  uses: digitalservicebund/setup-sonarscanner@LATEST_HASH
```

## Updating this action

After merging a dependabot PR or pushing changes, you need to [cut a new release](https://docs.github.com/en/repositories/releasing-projects-on-github/managing-releases-in-a-repository).
