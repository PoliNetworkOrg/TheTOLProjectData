# TheTOLProject

This repo hosts the compiled JSON database of the web app developed [here](https://github.com/PoliNetworkOrg/TheTOLProject).  
The repo is automatically updated by the [`update`](https://github.com/PoliNetworkOrg/TheTOLProjectData/blob/main/.github/workflows/update.yml) workflow, any manual change will be overwritten.  
For any issue and/or proposal, please refer to the info provided in the main repo.

This repo has two branches:

- `main`: this is the branch where every new change will be reflected, it's intented to be used in development
- `stable`: this is the branch that holds the production database, will not reflect changes until manually updated

To deploy the development database (in the `main` branch) to production (`stable`), dispatch the [`deploy`](https://github.com/PoliNetworkOrg/TheTOLProjectData/actions/workflows/deploy.yml) workflow.
