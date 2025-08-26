1. What triggers this workflow to run is the on: section of the deploy.yml file specifies the triggers. The workflow is triggered by the push event to the main branch.
2. 1. Checkout code copies repository code 2. Validate HTML checks for valid HTML syntax 3. Check for Broken links scans website for broken links 4. Deploy to Github Pages deploys the website if previous steps pass.
3. Copies repository code into GitHub Actions. Necessary to validate html and other steps.
4. Configures deployment enviroment for Github Pages and gives permissions.
5. It runs tests and deployment every time which reduces chance of human messing things up.
6. Nothing because pushes to any other branch beside main would be ignored. 
