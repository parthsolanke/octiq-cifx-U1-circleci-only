# CI detection fixture

The OSW-1178 message. An unsupported provider must be NAMED, and must never be mistaken for 'no CI'.

Expected verdict line in the Octiq chat:

    Tests not run - Currently, we support GitHub Actions, GitLab CI, Jenkins and Azure Pipelines. Found .circleci/config.yml, so tests were not checked.
