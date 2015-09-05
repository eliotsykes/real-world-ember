# Real World Ember

> Real World Ember apps and their open source codebases for developers to learn from

Learn from Ember apps written by experienced developers.

You&rsquo;ll find the source code for the Real World Ember apps in the [`apps/`](apps/) subdirectory.

Thank you to every developer who has worked on a project this repo links to, your work is helping developers learn Ember.

## How to install on your computer

```bash
# Clone this git repo:
git clone git@github.com:eliotsykes/real-world-ember.git

cd real-world-ember/

# The apps are linked to as git submodules.
# This will take some time...
git submodule update --init  
```

## Information for Contributors

#### How to add a Real World App

Given a GitHub repo for an app `githubuser/foo`:

```bash
# Inside the project root:
git submodule add -b master git@github.com:githubuser/foo.git apps/foo
```

#### Updating the apps submodules to latest

The apps in `apps/` are git submodules. Git submodules are locked to a revision and don't stay in sync with the latest revision.

To update the revisions, run:

```bash
#git pull --recurse-submodules # Probably not needed, try without.
# This will take some time:
git submodule foreach git pull origin master
```

---

# Contributors

- Eliot Sykes https://eliotsykes.com/
- Contributions are welcome, fork the GitHub repo, make your changes, then submit your pull request! Reach out if you'd like some help.
