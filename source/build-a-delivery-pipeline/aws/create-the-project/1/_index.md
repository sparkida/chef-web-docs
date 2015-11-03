## 1. Clone the GitHub repo to your workstation

In this step, you'll clone the repository from GitHub and move to your local repository directory.

Move to your working directory, for example, <code class="file-path">~/Development</code>.

```bash
# ~/Development/delivery-cluster
$ cd ~/Development
```

Clone the `deliver-customers-rhel` repo from GitHub.

[WINDOWS] Many Git users use Git BASH, which is part of [Git for Windows](https://git-for-windows.github.io), to work with Git from Windows. [posh-git](https://github.com/dahlbyk/posh-git) is another popular option, which provides access to Git from Windows PowerShell.

```bash
# ~/Development
$ git clone https://github.com/learn-chef/deliver-customers-rhel.git
Cloning into 'deliver-customers-rhel'...
remote: Counting objects: 1698, done.
remote: Compressing objects: 100% (849/849), done.
remote: Total 1698 (delta 540), reused 0 (delta 0), pack-reused 827
Receiving objects: 100% (1698/1698), 202.95 KiB | 0 bytes/s, done.
Resolving deltas: 100% (989/989), done.
Checking connectivity... done.
```

Move to the <code class="file-path">deliver-customers-rhel</code> directory.

```bash
# ~/Development
$ cd deliver-customers-rhel
```

[COMMENT] You're cloning an existing Git project to obtain starter code. You can configure Chef Delivery to connect directly with your existing Git projects, import code from another source control system, or create a new repository from scratch.