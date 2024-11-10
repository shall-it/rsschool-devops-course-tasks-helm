# rsschool-devops-course-tasks-helm

## Task 5
https://github.com/rolling-scopes-school/tasks/blob/master/devops/modules/3_ci-configuration/task_5.md


To deploy WordPress helm chart:
1. Use https://github.com/shall-it/rsschool-devops-course-tasks/pull/4 PR to deploy kOps cluster into AWS
2. Setup KUBECONFIG secret variable in https://github.com/shall-it/rsschool-devops-course-tasks-helm/settings/secrets/actions to use it within GHA to access cluster
3. Re-run the latest job or push your changes into `task_5` branch or create PR to `master` to deploy web-application into kOps cluster. Or just use `helm upgrade --install app-chart ./Chart` command from root of repository to deploy the same one.