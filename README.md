# manas-kubectl-ssh

Simple Kubectl plugin to establish SSH connection with the specific labeled nodegroups.If you want to use this SSH plugin you should have jq command.
# ENABLE Plugin
After you fetch this repo, you should move `kubectl-ssh` file somewhere into $PATH after you can use it like this:

`kubectl ssh <LABEL_OF_YOUR>`

If you want to specify ssh private key path you should do it like this by the way you can use this script without specify ssh-keypair

```
kubectl ssh master USER_NAME KEY_PATH
```

If you do not specify SSH user the default value is `ubuntu`.
## Installation of JQ
From the source binary of jq 

You can download from this link:
`https://stedolan.github.io/jq/download/`

Installation via package manager
```
mac OSX:
brew install jq

Ubuntu:
apt-get install -y jq
```
