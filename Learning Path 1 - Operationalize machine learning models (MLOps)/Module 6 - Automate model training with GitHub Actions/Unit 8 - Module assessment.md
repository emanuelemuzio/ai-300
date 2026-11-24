# Assessment

*1.* A team stores its training scripts, pipeline component YAML files, and a trained model binary in the same GitHub repository. Which item is misplaced?

> The trained model binary.

*2.* A data scientist directly pushes a change to the `main` branch that breaks the training script. Which practice would have prevented this?

> A branch protection rule blocking direct pushes to `main`, combined with a pull request process.

*3.* A team wants linting to run automatically whenever someone opens a pull request, and the merge must be blocked if linting fails. Which two GitHub features work together to enforce this?

> A workflow with a `pull_request` trigger, and a branch protection rule that requires that workflow's status check.

*4.* A team uses a service principal with client secrets stored in GitHub secrets to authenticate their training workflow to Azure. A security review recommends switching to workload identity federation with OIDC. What is the primary security benefit?

> Workload identity federation issues short-lived tokens at runtime instead of storing long-lived credentials, so a compromised token has a limited window of validity.

*5.* Azure Event Grid reports that new training data arrived in storage. The team wants this event to start a GitHub Actions retraining workflow. Why does the design use an intermediary?

> GitHub Actions doesn't natively subscribe to Event Grid events, so an intermediary can receive the event, authenticate to GitHub, and send a `repository_dispatch` call.

## [[Unit 9 - Summary| Next Unit > Summary]]
