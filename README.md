# lrc-selfhosted-runner

This demonstrates using a self-hosted runner to launch a slurm job submission automatically on Lawrencium.

Usage:

1. Install GitHub actions-runner: [https://github.com/actions/runner]
2. Start the runner script from terminal: `actions-runner/run.sh`
3. Push code to target repo, the runner script should detect the push and trigger the action

For details on the runner configuration, see `.workflows`.

Need help? Email scienceit@lbl.gov
