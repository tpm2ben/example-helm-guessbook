# example-helm-guessbook

https://github.com/harness-community/harnesscd-example-apps/tree/master/helm-guestbook

https://developer.harness.io/docs/continuous-delivery/get-started/cd-tutorials/helm-chart/?deploymentui=canaryui#how-to-deploy-your-own-app-by-using-harness

Helm is primarily focused on managing the release and versioning of application packages. Helm supports rollback through its release management features. 
When you deploy an application using Helm, it creates a release that represents a specific version of the application with a unique release name.

In Harness, You can specify the percentage of traffic to route to the new version in a canary deployment or define the conditions to switch traffic between 
the blue and green environments in a blue-green deployment.

Harness orchestrates the deployment workflow, including the deployment of Helm charts, by interacting with the Helm API. It manages the release lifecycle, 
tracks revisions, and controls the rollout process based on the defined canary or blue-green strategy.

Harness adds an additional layer of functionality on top of Helm, providing a streamlined and automated approach to canary and blue-green deployments. 
By leveraging Helm's package management capabilities and integrating with its release management features, Harness extends Helm's capabilities to 
support canary and blue-green deployment strategies.
