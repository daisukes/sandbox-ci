- Started from github action tutorial
  - https://docs.github.com/en/actions/quickstart
- Github action takes a few minutes with minimum lint check
- Found act to run github action locally
  - https://github.com/nektos/act
  - It works on my Apple Silicon Mac Mini
  - exported GITHUB_TOKEN to get rid of the runtime error, but I'm not sure what's different
  - got ERROR in INFO message, but maybe for updating github.com actions page
  ```
ERROR! Failed to call GitHub Status API!
  ```



### general tips

- To keep your workflow stable even when updates are made to an action, you can reference the version of the action to use by specifying the Git or Docker tag number in your workflow file. [ref](https://docs.github.com/en/actions/learn-github-actions/finding-and-customizing-actions#adding-an-action-to-your-workflow)
