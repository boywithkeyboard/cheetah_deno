## cheetah for deno

### File Structure

- `.github`
  - `workflows`
    - `bump.yml` *- updates your dependencies daily at 2pm* **(make sure to update the `reviewers` property!)**
- `.vscode`
  - `settings.json` *- enables deno for this workspace*
- `deno.json` *- for managing tasks and dependencies*
- `mod.ts` *- the entry file for your app*

### Get Started

1. Don't forget to replace `YOUR_GITHUB_USERNAME` with your username in the `.github/workflows/bump.yml` file. You can learn more [here](https://github.com/azurystudio/bump#readme).
