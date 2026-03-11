Simple action that runs on workflow_dispatch and automatically approves alerts that are delegated for approval.

DISMISSAL_SECRET must be set as the Actions secret. For this to run successfully you'll need the scopes admin:org, admin:repo_hook, delete_repo (based on log outputs of failed runs), repo, and workflow
