# Custom Git commands

## Requirements
* Install `github cli`: https://cli.github.com
* Install [Github Pull Requests and Issues](https://marketplace.visualstudio.com/items?itemName=GitHub.vscode-pull-request-github) extension
* Add `bin` to `PATH`

## Usage
```bash
# Checkout PR using github cli
gh pr checkout 1234

# Add config value for 'github.vscode-pull-request-github' extension
# Rename branch to 'pr/<author>/<pr_number>
git vsc

# Remove branch and remote
git vsc-delete
```

## How to
- Create new file in `bin`
- `chmod +x <file>`

## Helpful Links
- http://thediscoblog.com/blog/2014/03/29/custom-git-commands-in-3-steps/
- https://gitbetter.substack.com/p/automate-repetitive-tasks-with-custom
- https://devhints.io/bash
