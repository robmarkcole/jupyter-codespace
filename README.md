# jupyter-codespace
Tryout running jupyter notebooks in a Github Codespace - basically vscode in the browser.
Summary: unreliable owing to issue below, wait until this is out of beta

* To create this repo followed https://dlite.cc/2020/05/26/github-codespaces-machine-learning.html, repo [here](https://github.com/whisk-ml/disaster_tweets)
* uses https://github.com/Microsoft/vscode-python
* https://docs.github.com/en/free-pro-team@latest/github/developing-online-with-codespaces
* Also a must read https://fastpages.fast.ai/codespaces

## Issues
* Worked first time, now getting timeout errors: `Timed out waiting to get a heartbeat from kernel process.` Possibly [this issue](https://github.com/microsoft/vscode-python/issues/13365). Solution appears to be up/downgraring the vscode-python extension

### FAQ
* Each codespace is associated with a specific branch of a repository. You can create more than one codespace per repository or even per branch. However, each user account has a two-codespace limit during limited public beta. 
* You can create a default codespace configuration for your repository that determines the environment of every new codespace anyone creates for that repository. 
