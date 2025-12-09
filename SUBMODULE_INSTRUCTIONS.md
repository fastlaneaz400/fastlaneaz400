# Instructions for Using Git Submodules

This repository uses a Git submodule to include the lab exercises from the [mslearn-devops](https://github.com/schuerstedt/mslearn-devops) repository in the `Instructions` folder.

## Cloning the Repository with Submodules

When you clone this repository, use the `--recurse-submodules` flag to automatically initialize and update the submodule:

```
git clone --recurse-submodules https://github.com/fastlaneaz400/fastlaneaz400.git
```

If you have already cloned the repository without this flag, you can initialize and fetch the submodule with:

```
git submodule update --init --recursive
```

## Pulling Updates for Submodules

To update the submodule to the latest commit from the remote repository, run:

```
git submodule update --remote --merge
```

## Additional Resources
- [Git Tools - Submodules (Pro Git Book)](https://git-scm.com/book/en/v2/Git-Tools-Submodules)
- [Git Submodules Documentation](https://git-scm.com/docs/git-submodule)

---

If you have any issues with submodules, please refer to the documentation above or contact the repository maintainer.
