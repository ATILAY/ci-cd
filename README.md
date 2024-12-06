# ci-cd
ci/cd  details
---------------------------------------------------------------------------------------------------------------------------------------------------------------
**What is CI/CD ?
it is  used in modern software development to streamline and automate the process of delivering code changes.

1. Continuous Integration (CI) : the practice of automatically integrating code changes from multiple developers into a shared repository multiple times a day.
1.A. Key Features:
-Code is tested automatically using tools whenever changes are pushed to the repository.
-Helps catch bugs early by running automated unit tests, integration tests, and code quality checks.
-Reduces integration issues, as changes are merged and tested incrementally.
1.B. Tools: Jenkins, GitHub Actions, GitLab CI/CD, CircleCI, Travis CI.

2. Continuous Delivery (CD) : ensures that the codebase is always in a deployable state and automates the process of delivering new features or fixes to production-like environments.
2.A.Key Features:
-Manual approval is required before deploying to production.
-Ensures smooth and reliable releases with minimal manual effort.
-Includes stages like staging and pre-production environments for testing.
2.B.Tools: Azure DevOps, AWS CodePipeline, Bamboo, Spinnaker.

3. Continuous Deployment (CD) :  is the next step after Continuous Delivery, where every change that passes automated tests is deployed directly to production.
3.A.Key Features:
-Fully automated deployment process with no manual intervention.
-Faster delivery of features and fixes to end users.
-Requires robust testing and monitoring to ensure reliability.
-Tools: Kubernetes, Docker Swarm, Harness.**
---------------------------------------------------------------------------------------------------------------------------------------------------------------
---------------------------------------------------------------------------------------------------------------------------------------------------------------
Benefits of CI/CD ?
-Faster Releases: Automates repetitive tasks, enabling rapid feature delivery.
-Improved Quality: Automated testing ensures consistent quality checks.
-Reduced Risks: Frequent and small changes are easier to manage and troubleshoot.
-Collaboration: Encourages teamwork and communication among developers.
---------------------------------------------------------------------------------------------------------------------------------------------------------------
---------------------------------------------------------------------------------------------------------------------------------------------------------------
CI/CD steps ?
1
version control ->
2
build ->
3
unit testing ->
4
deploy ->
5
auto test ->
6
deploy to production ->
7
measure + validate ->
---------------------------------------------------------------------------------------------------------------------------------------------------------------
---------------------------------------------------------------------------------------------------------------------------------------------------------------
What challenges can arise while implementing CI/CD pipelines?

Common challenges:
1.Configuring pipelines for complex applications.
2.Handling long build times.
3.Debugging failed tests.
4.Securing the pipeline against unauthorized changes.
---------------------------------------------------------------------------------------------------------------------------------------------------------------
---------------------------------------------------------------------------------------------------------------------------------------------------------------
How do you manage secrets (e.g., API keys) in a CI/CD pipeline?

-Use secure secret management tools such as HashiCorp Vault, AWS Secrets Manager, or CI/CD tool integrations like GitHub Secrets or GitLab CI/CD variables.
---------------------------------------------------------------------------------------------------------------------------------------------------------------
---------------------------------------------------------------------------------------------------------------------------------------------------------------
How can you ensure rollback capability in CI/CD?

-Use versioned releases, maintain a rollback plan with stable artifacts, and use infrastructure as code to restore environments quickly.
---------------------------------------------------------------------------------------------------------------------------------------------------------------
---------------------------------------------------------------------------------------------------------------------------------------------------------------
What is the role of containerization (e.g., Docker) in CI/CD?

-Containers provide consistency across environments by packaging applications and dependencies together, enabling reliable builds, testing, and deployments.
---------------------------------------------------------------------------------------------------------------------------------------------------------------
---------------------------------------------------------------------------------------------------------------------------------------------------------------
popular CI/CD tools?

- Jenkins, GitLab CI/CD, GitHub Actions, CircleCI, Bamboo.
---------------------------------------------------------------------------------------------------------------------------------------------------------------
---------------------------------------------------------------------------------------------------------------------------------------------------------------
How does Jenkins support CI/CD?

-Jenkins automates the pipeline by executing jobs such as code builds, running tests, and deploying applications through plugins and declarative pipelines.
---------------------------------------------------------------------------------------------------------------------------------------------------------------
---------------------------------------------------------------------------------------------------------------------------------------------------------------
What is a build agent in CI/CD?

-A build agent is a machine or container that runs jobs in a CI/CD pipeline, such as compiling code or running tests.
---------------------------------------------------------------------------------------------------------------------------------------------------------------
---------------------------------------------------------------------------------------------------------------------------------------------------------------
How do Kubernetes and CI/CD work together?

-Kubernetes orchestrates deployment and scaling of applications, while CI/CD pipelines automate the process of building and delivering the containers that Kubernetes runs.
---------------------------------------------------------------------------------------------------------------------------------------------------------------
---------------------------------------------------------------------------------------------------------------------------------------------------------------
What types of tests should be part of a CI/CD pipeline?

-Unit tests, integration tests, performance tests, security scans, and acceptance tests.
---------------------------------------------------------------------------------------------------------------------------------------------------------------
---------------------------------------------------------------------------------------------------------------------------------------------------------------
How can you speed up slow CI/CD pipelines?

-Use parallel builds and test execution.
-Cache dependencies and artifacts.
-Optimize tests to run only on changed code.
-Use powerful build agents.
---------------------------------------------------------------------------------------------------------------------------------------------------------------
---------------------------------------------------------------------------------------------------------------------------------------------------------------
What is the purpose of a smoke test in a CI/CD pipeline?

-A smoke test quickly verifies that the core functionalities of an application work after deployment, ensuring it’s ready for further testing.
---------------------------------------------------------------------------------------------------------------------------------------------------------------
---------------------------------------------------------------------------------------------------------------------------------------------------------------
How do you handle flaky tests in CI/CD?

-Investigate and fix underlying issues, isolate flaky tests, retry failed tests, or quarantine them temporarily.
---------------------------------------------------------------------------------------------------------------------------------------------------------------
---------------------------------------------------------------------------------------------------------------------------------------------------------------
How do you monitor the health of a CI/CD pipeline?

-Use monitoring tools (e.g., Prometheus, Grafana, New Relic), log aggregation tools (e.g., ELK stack), and built-in CI/CD tool dashboards to track build status, success rates, and failures.
---------------------------------------------------------------------------------------------------------------------------------------------------------------
---------------------------------------------------------------------------------------------------------------------------------------------------------------
What steps do you take to debug a failed build in CI/CD?

1-Check logs to identify errors.
2-Verify configurations and environment variables.
3-Run tests locally to replicate the issue.
-Rollback recent changes to isolate the problem.
---------------------------------------------------------------------------------------------------------------------------------------------------------------
---------------------------------------------------------------------------------------------------------------------------------------------------------------
What is blue-green deployment in CI/CD?

-Blue-green deployment involves having two environments (blue and green). One runs the current version, and the other deploys the new version. After verification, traffic is switched to the new environment.
---------------------------------------------------------------------------------------------------------------------------------------------------------------
---------------------------------------------------------------------------------------------------------------------------------------------------------------
What is the role of Infrastructure as Code (IaC) in CI/CD?

-IaC tools like Terraform or Ansible automate provisioning and managing infrastructure, ensuring consistent environments across CI/CD stages.
---------------------------------------------------------------------------------------------------------------------------------------------------------------
---------------------------------------------------------------------------------------------------------------------------------------------------------------
---------------------------------------------------------------------------------------------------------------------------------------------------------------
---------------------------------------------------------------------------------------------------------------------------------------------------------------
---------------------------------------------------------------------------------------------------------------------------------------------------------------
---------------------------------------------------------------------------------------------------------------------------------------------------------------
---------------------------------------------------------------------------------------------------------------------------------------------------------------
---------------------------------------------------------------------------------------------------------------------------------------------------------------
---------------------------------------------------------------------------------------------------------------------------------------------------------------
---------------------------------------------------------------------------------------------------------------------------------------------------------------
---------------------------------------------------------------------------------------------------------------------------------------------------------------
---------------------------------------------------------------------------------------------------------------------------------------------------------------
---------------------------------------------------------------------------------------------------------------------------------------------------------------
---------------------------------------------------------------------------------------------------------------------------------------------------------------
---------------------------------------------------------------------------------------------------------------------------------------------------------------
---------------------------------------------------------------------------------------------------------------------------------------------------------------
---------------------------------------------------------------------------------------------------------------------------------------------------------------
---------------------------------------------------------------------------------------------------------------------------------------------------------------
---------------------------------------------------------------------------------------------------------------------------------------------------------------
---------------------------------------------------------------------------------------------------------------------------------------------------------------
---------------------------------------------------------------------------------------------------------------------------------------------------------------
---------------------------------------------------------------------------------------------------------------------------------------------------------------
---------------------------------------------------------------------------------------------------------------------------------------------------------------
---------------------------------------------------------------------------------------------------------------------------------------------------------------
---------------------------------------------------------------------------------------------------------------------------------------------------------------
---------------------------------------------------------------------------------------------------------------------------------------------------------------
---------------------------------------------------------------------------------------------------------------------------------------------------------------
---------------------------------------------------------------------------------------------------------------------------------------------------------------
---------------------------------------------------------------------------------------------------------------------------------------------------------------
---------------------------------------------------------------------------------------------------------------------------------------------------------------
---------------------------------------------------------------------------------------------------------------------------------------------------------------
---------------------------------------------------------------------------------------------------------------------------------------------------------------
---------------------------------------------------------------------------------------------------------------------------------------------------------------
---------------------------------------------------------------------------------------------------------------------------------------------------------------
---------------------------------------------------------------------------------------------------------------------------------------------------------------

