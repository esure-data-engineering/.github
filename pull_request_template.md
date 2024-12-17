This is a global template for all GitHub repository under the Esure Data Engineering organisation

Please make sure the following checks are performed before merging this PR

- Branch name:
    - [ ] Feature and sandbox branches name convention: feature or sandbox + '/' + the Jira ticket number in lowercase
    - [ ] Only valid branch names are main, develop, release/*, sandbox/*, feature/*
- Title:
    - [ ] Use semantic PR approach (https://pulsar.apache.org/contribute/develop-semantic-title/)
    - [ ] Short informative summary of the pull request
    - [ ] Include the corresponding ticket/story ID in square brackets
    - [ ] It should be capitalised and written in the imperative present tense and not end in a period
- Description:
    - [ ] Explain what, why and deployment steps
    - [ ] Include related tasks/stories
    - [ ] Max 72 chars per line
    - [ ] Each paragraph capitalised
    - [ ] Include diagrams or pictures if they help the explanation
    - [ ] Detail how reviewers can test the changes
- Commit message (https://myesure.atlassian.net/wiki/spaces/DE/pages/625247173/Branching+Strategy+and+git+standards):
    - [ ] Only one commit message per PR. Squash commits as per the documentation above
    - [ ] Separate the subject from the body with a blank line
    - [ ] Limit the subject line to 50 characters
    - [ ] Capitalize the subject line
    - [ ] Do not end the subject line with a period
    - [ ] Use the imperative mood in the subject line
    - [ ] Wrap the body at 72 characters
    - [ ] Use the body to explain what and why vs. how
- Testing:
    - [ ] In a Python repo include a test folder with all unit tests to be run via Jenkins
    - [ ] In SQL repo, include evidence of the reconciliation in the sql_test folder
    - [ ] Include any evidence of any integration or regression test in the sql_test folder
    - [ ] Include .pre-commit-config.yaml to check formatting define in our standards
   

