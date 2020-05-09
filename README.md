REPO PAGE
=========

Repo `gh-page`: [https://simosca.github.io/own-notes/](https://simosca.github.io/own-notes/).


COMMANDS
========


STARTUP
-------

First of all to automatically trigger the publishing while committing, without manually builds, 
I've add some `git hooks` that you can use by setting the local project git hook folder `.githooks`:

````
git config --local core.hooksPath .githooks/
````
See [here](https://www.viget.com/articles/two-ways-to-share-git-hooks-with-your-team/).



RUN
---

- `predeploy`, creates only the assets without publishing

- `deploy`, publish ghe pages (no commits on master appears)





NOTES
=====

Test of single page published on `gh-pages` improved via `create-react-app` and `gh-pages` package.




REFS
=====

- [kickoff page](https://dev.to/yuribenjamin/how-to-deploy-react-app-in-github-pages-2a1f).

