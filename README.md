# apply-autopep8-action

A git action that applies autopep8 to formatting every file upon every pull request/push.

# Before enabling this workflow, configure the following settings:
# 1. On GitHub.com, navigate to the main page of the repository.
# 2. Under your repository name, click "Settings"
# 3. In the left sidebar, click "Actions", and select "General" upon the slide-down menu
# 4. Scroll down to "Workflow Permissions", and select "Read and Write Permissions".
# 5. Tick the "Allow GitHub Actions to create and approve pull requests" box and press "Save".

# To grant additional permissions/accesses, a customized Token can be generated and added to the repo secret.
# For more info, visit https://docs.github.com/en/actions/security-guides/automatic-token-authentication

# IMPORTANT: Pulls that are requested by forked repos would trigger a FAILED Action,
# for PRs coming from other repos cannot access local repo secrets.
