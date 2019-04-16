## MS Build 2019, Seattle

A talk by @nerdneha and @zeke.

## Overview

- Intros
- Prompt: What project would you like to open source? Find a partner and share.
- Desktop Project (Neha)
- Electron Project (Zeke)
- GitHub Flow
- Open Source Basics (Neha)
- Workflow / Etiquette (Zeke)
- Prompt: What do you want your project to look like in three years?
- Shared Ownership (Neha)
- Prompt: what does shared ownership look like for you? 
- GitHub Apps / Marketplace (Zeke)
- Prompt: Write down two tools you wanna check out
- Probot
- Actions

## Topics

### Desktop

- Transitioning from a private repo to an open source community

### Electron

- @zeke wanted to be able to disappear

### GitHub Flow

- Happens entirely on GitHub
- Create a branch
- Add commits
- Open a Pull Request
- Discuss and review your code
- Deploy
- Merge

### Open Source Basics / Community Checklist

- README
- CoC
- CONTRIBUTING.md
- License
- Issue and PR templates
- `good-first-issue` labels: https://www.firsttimersonly.com/

### Workflow / Etiquette

- Open issues before PRs (conversation before implementation)
- Draft PRs (new feature)
- semantic release?
- Review apps
  - Heroku
  - Zeit Now
  - Azure
  - Netlify

### Shared Ownership / Giving Credit

- Write permissions for members
- Avoid fork-based workflow
- Branch protection for safety
- CODEOWNERS
- Roles: Different ways to contribute
- Desktop release notes summarize contributors
- VSCode changelog is a good example
- all-contributors

## Semantic Release

- SemVer
- https://www.conventionalcommits.org - A specification for adding human and machine-readable meaning to commit messages
- https://github.com/semantic-release - Fully automated version management and package publishing
- https://github.com/conventional-changelog/standard-version - Automate versioning and CHANGELOG generation, with semver.org and conventionalcommits.org

### GitHub Apps / Marketplace

marketplace focus is on teams and businessea, be they open source or private.

write less code, click fewer buttons.

- accesslint
- [twitter-together](https://github.com/marketplace/actions/twitter-together)
- welcome (3 things)
- octobox
- LGTM
- Codacy
- Dependabot
- BackHub
- Semantic Pull Requests

## Probot

- Webhooks - https://github.com/octokit/webhooks.js/blob/master/lib/webhook-names.json

### Actions

- arbitrary code execution
- respond to any webhook event
- run on a schedule
- Secrets API
- Docker

## Audience participation ideas

- close your eyes
- write something down
- tweet something with a hashtag
- talk to your neighbor - exchange contact information
- collective selfie
- extra credit activity
- What are the biggest challenges you might have open-sourcing a project?

## Other topics and concepts

- geodistribution
- diversity
- BUS factor
- Onion skin. The more layers you peel off, the more you cry.
- If I do my job right, you never see it
- Jake replaced herself with a machine
- Cumulative list of tools and practices (see youtube video: https://youtu.be/WzghfjjjKvA?t=3064)
- https://github.com/desktop/desktop/blob/development/docs/process/what-is-desktop.md
- progress bar across the bottom

Questions:

- Will this be live-streamed?
- Will the video be edited?
- If you're at home, send a DM to someone
- Brand me!

Resources:

https://github.com/desktop/desktop/blob/development/docs/process/roadmap.md
https://github.com/customer-stories/jessfraz
https://www.firsttimersonly.com/
http://hood.ie/blog/welcoming-communities.html

> Use simple language (Hemingway can help). List all professions like “Design”, “Editorial”, “Documentation” instead of saying “Non-Coding”. Use gender-neutral language, prefer “them” and “they” over “him” and “she”. Avoid phrases like “Hey guys”. If you use Slack, you can configure slackbot to suggest alternatives, as we do in our Hoodie Chat. This is your chance to “set a tone” in your community. It helps to limit unfriendly, over-demanding and self-entitled requests from strangers.