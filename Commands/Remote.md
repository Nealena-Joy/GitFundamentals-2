# git remote
When working with git, a **remote** is any gi trepository that is not on the machine you're working on. The counter part to this is **local**, or the machine that is being developed on.

Take GitHub for example. While git is the technology that allows yu to create local repositories, GitHub is the site that will host your remote repositories. Once stored remotely, you can bring that repository back down or share it with others.

**Note**: While the repositories (local and remote) are related and track the same project, they can have different states if changes are not shared between the too.

---

### Adding a remote
A remote can be added witht eh ~git remote add` command, followed by the name adn location of the remote.

The name is a local name, meaning it's your label and does not impact the actual remote whatsoever.

```
git remote addd origin https://github.com/Nealena-Joy/GitFundamentals.git
```

---

### Removing a remote
A remote can be removed witht e`git remote remove` command, followed by the name of the remote.
```
git remote remove origin
```
---

## Resources
- [Git Remote Documation](https://git-scm.com/docs/git-remote)
---


[Back to home](../README.md)
