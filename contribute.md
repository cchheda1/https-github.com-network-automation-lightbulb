# Contribute
We take pull requests!  Please read the [PHILOSOPHY.md](PHILOSOPHY.md) and search the issues before submitting a PR.

## Create a fork!
Create a fork on your own Github project (or your personal space)

[Github Documentation on Forking a repo](https://help.github.com/articles/fork-a-repo/)

## Stay in Sync
It is important to know how to keep your fork in sync with the upstream Lightbulb project.

### Configuring Your Remotes
Configure Lightbulb as your upstream so you can stay in sync

```bash
git remote add upstream https://github.com/ansible/lightbulb.git
```

### Rebasing Your Branch
Three step process

```bash
git pull --rebase upstream master
```

```bash
git status
```

### Updating your Pull Request
```bash
git push --force
```

More info on docs.ansible.com: [Rebasing a Pull Request](http://docs.ansible.com/ansible/latest/dev_guide/developing_rebasing.html)

## Create a pull requests

Make sure you are not behind (in sync) and then submit a PR to Lightbulb.  
[Read the Pull Request Documentation on Github.com](https://help.github.com/articles/creating-a-pull-request/)

Just because you submit a PR, doesn't mean that it will get accepted.  Right now the QA process is manual for lightbulb, so provide detailed directions on

 - WHY? Why did you make the change?
 - WHO? Who is this for?  If this is something for a limited audience it might not make sense for all lightbulb users.  Refer to the [Lighbulb Philosophy](PHILOSOPHY.md)
 - BEST PRACTICE?  Is this the "best" way to do this?  Link to documentation or examples where the way you solved your issue or improved Lightbulb is the best practice for teaching or building workshops.

Being more descriptive is better, and has a higher change of getting merged upstream.  Communication is key!  Just b/c the PR doesn't get accepted right away doesn't mean it is not a good idea.  Lightbulb has to balance many different types of users.  Thank you for contributing!

# Going Further
The following links will be helpful if you want to contribute code to the Lightbulb project, or any Ansible project:
- [Ansible Committer Guidelines](http://docs.ansible.com/ansible/latest/committer_guidelines.html)
- [Learning Git](https://git-scm.com/book/en/v2)
