# sample-node-sonar

Minimal Node/TS project used to validate the SonarCloud GitHub Actions template.

## Setup
1. Create a SonarCloud project and note your organization key and project key.
2. Update `.github/workflows/sonar.yml` with your `sonar.organization` and `sonar.projectKey`.
3. Add `SONAR_TOKEN` as a GitHub repository secret.
4. Push to `main` and confirm the analysis appears in SonarCloud.
