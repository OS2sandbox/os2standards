
# Contribution guidelines for *OS2produkt*

If you want to contribute to *OS2produkt*, we ask you to follow these guidelines.

## Reporting bugs
If you have encountered a bug in *OS2produkt*, please check if an issue already exists in the list of existing [issues](https://os2web.atlassian.net/), if such an issue does not exist, you can create one [here](https://os2web.atlassian.net/). When writing the bug report, try to add a clear example that shows how to reproduce said bug.

## Adding new features
Before making making changes to the code, we advise you to first check the list of existing [issues](https://os2web.atlassian.net/) for OS2produkt to see if an issue for the suggested changes already exists. If such an issue does not exist, you can create one [here](https://os2web.atlassian.net/). Creating an issue gives an opportunity for other developers to give tips even before you start coding. If you are in the early idea phase, or if your feature requires larger changes, you can discuss it with the [projects coordination group](https://os2.eu) or by [contacting OS2 directly](https://os2.eu/kontakt) to make sure you are heading in the right direction.

### Code style
To keep the code clean and readable, *Please include links to coding standards and tools used:*

Whenever a branch is pushed or a pull request is made, the code will be checked in CI by the tools mentioned above, so make sure to install these tools and run them locally before pushing branches/making PRs.

### Forking the repository
In order to implement changes to *OS2produkt* when you do not have rights for the required repository, you must first fork the repository. Once the repository is forked, you can clone it to your local machine.

### Making the changes
On your local machine, create a new branch, and name it like:
- `feature/some-new-feature`, if the changes implement a new feature
- `issue/some-issue`, if the changes fix an issue

Once you have made changes or additions to the code, you can commit them (try to keep the commit message descriptive but short). If an issue exists in the issue list for the changes you made, be sure to format your commit message like `"Fixes #<issue_id> -- description of changes made`, where `<issue_id>"` corresponds to the number of the issue on Jira or GitHub. To demonstrate that the changes implement the new feature/fix the issue, make sure to also add tests.

### Making a pull request
If all changes have been committed, you can push the branch to your fork of the repository and create a pull request to the `master` branch of the *OS2produkt* repository. Your pull request will be reviewed, if applicable feedback will be given and if everything is approved, it will be merged.

### Reviews on releases

All pull requests will be reviewed before they are merged to a release branch. As well as being reviewed for functionality and following the code style they will be checked with the steering committee and/or the coordination group for the project.
## Setting Up the Development Environment

1. **Clone the repository**: Use the command `git clone <repository-url>` to clone the repository to your local machine.

## Contributing using GitHub and the git command line client.

### Guides on how to follow our Contribution guidelines using GitHub. 

## Creating an Issue

1. **Navigate to the issues tab**: In the GitHub repository, navigate to the 'Issues' tab.
2. **Create a new issue**: Click on 'New issue' and fill out the title and description with the relevant details of the issue.

## Creating a Branch

1. **Create a new branch**: Use the command `git checkout -b <branch-name>` to create a new branch. The branch name should be descriptive of the issue you are working on.

## Making Changes

1. **Make your changes**: Make the necessary changes to the codebase.
2. **Stage your changes**: Use the command `git add .` to stage your changes.
3. **Commit your changes**: Use the command `git commit -m "<commit-message>"` to commit your changes. The commit message should be descriptive of the changes made.

## Creating a Pull Request (PR)

1. **Push your changes**: Use the command `git push origin <branch-name>` to push your changes to the remote repository.
2. **Create a PR**: Navigate to the 'Pull requests' tab in the GitHub repository and click on 'New pull request'. Select your branch from the dropdown and fill out the title and description with the relevant details of the changes made.
3. **Submit the PR**: Click on 'Create pull request' to submit the PR for review.

Remember to always pull the latest changes from the main branch before starting work on a new issue.
