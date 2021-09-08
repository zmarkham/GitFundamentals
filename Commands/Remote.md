# git remote
When working with git, a **remote** is any git repository that is not on the machine you're working on, The conterpart to this is **local**, or the machine that is being developed on.
Take GitHub for example. While git is the technology that allows you to create local repositories, GitHub us the site that will host your remote repositories.  Once sotred remotely, you can bring the repository back down or share it with others.
**Note**: While the repositiies (local and remote) are related and trach the same project, they can have different states if changes are not shared between the two.
### Adding a remote
A remote can be added with the `git remote add` command, followed by the name and location of the remote.
The name is a local name, meaning it's your label and does not impact the actual remote whatsoever.
```
git remote add orgin https://github.com/ElevenfiftyAcademy/GitFundaments.git
```
### Removing a Remote
A remote can be removed witht he `git remote remove` command, followed by the name of the remote. 
```
git remote remove origin
```
### Resources
- [Git Remote Documentation](https://git-scm.com/docs/git-remote)
---
[Back to home](../README.md)
