# How to become a MergeFest Hacker - Shreyeahhh-03

## Basic git commands

Please visit: https://github.com/IMGIITRoorkee/open-source-arcade/

## Issue label

Please note:  If you wanted to work on an issue, let us know by leaving a comment on the issue. If someone is already assigned or working on the issue, do not try to start working without asking in a thread. Also let us know later if you are no longer working on it.

- `easy` issues are usually confined to isolated areas of existing code.
- `medium` issues sometimes entail new features and might affect a significant area of the codebase, but aren't overly complex.
- `hard` issues are typically far-reaching, and might need architecture decisions during implementation. 

## Creating an issue.

- Check if the issue you are going to propose is not duplicate of another issue.
- Give a precise and meaningful name of the issue.
- Describe your issue as good as possible that may ease the process of issue-reviewing by a maintainer and maintainers will add labels to the issue.

## How to contribute

1. Fork the project and clone it to your local machine. Follow the [setup] guidelines for respective projects.
2. Always take a pull from the remote repository to your master branch to keep it at par with the main project(updated repository).
        
        git pull upstream master
        
3. Create a branch. For example, if you are going to work on issue number #44 (which is, say, a new feature for ‘forgot password’ management):

        git checkout -b forgot-password#44

    This both creates and checks out that branch in one command.  
    The feature name should provide a (short) description of the issue.
   **Branch without issue number will not be accepted.**

5. Update the README.md with details of changes to the interface, this includes new environment variables, exposed ports, useful file locations and container parameters.
6. Commit your changes and push it to your fork of the repository.
7. Create Pull Request (PR). Make sure to comment the issue that your PR is supposed to solve.

## Create a pull request

- Try to keep the pull requests small. A pull request should try its very best to address only a single concern.
- For work in progress pull requests, please use the Draft PR feature.
- Make sure all tests pass and add additional tests for the code you submit.
- Document your reasoning behind the changes. Explain why you wrote the code in the way you did. The code should explain what it does.
- If there's an existing issue, reference to it by adding something like `References/Closes/Fixes/Resolves #123`, where 123 is the issue number. 
- Please fill out the PR Template when making a PR.

> Please note: maintainers may close your PR if it has gone stale or if we don't plan to merge the code.

## Pull Request Template

### Related Issue  
Closes #issue number  

### Type of Change
Put `x` inside the square bracket to specify what type of change your PR is:  
- [ ] New Feature  
- [ ] Bug Fix  
- [ ] Code Refactor  
- [ ] Documentation Update  
- [ ] Other (please specify): 

### Description of Change  
Give a description of the change your PR is bringing.

### Implementation Details  
Give details about how you are implementing the change.

### Demo  
Provide screenshots or a video demonstrating the feature in action.  
(Include attachments or links, if applicable.)

## Pull request reviews

- Requested changes must be resolved (with code or discussion) before merging.
- If you make changes to a PR, be sure to re-request a review.
- Don't repeadetely tag someone(may be it is not the right time to review your PR), be patient.
- Do not 'resolve conversation' unnecessary raised by a community member or any workflow tools(codeclimate or hound) as they may have some purpose, try to resolve the request changes and if any help wanted tag a community member to give views about that.

#### PR Labels

- `under-review` labeled PRs are under review by core team.
- `waiting for contributor` labeled PRs are meant to waiting for contributor to respond.
- `waiting for design` labeled PRs are meant to waiting for review from UI/UX core team.
- `no activity` labeled PRs are meant to have no activity in the PR from since a while.
- `blocked` labeled PRs are meant not to go ahead for review.
- `do not merge` labeled PRs are meant not to merge the PR right now(may be later).
- `awaiting-approval` labeled PRs are meant to be waiting for other community members.

## Community
Discussions about MergeFest issues and features take place on Discord. Anybody is welcome to join these conversations. See the [README](README.md) for more information on communication channels.
Join [Discord](https://discord.com/invite/aKaEbaVYKf)

## The bottom line

We are all humans trying to work together to improve the community. Always be kind and appreciate the need for tradeoffs. ❤️
