---
title: Home
#weight: 5
#menuTitle: Linux
---

# Home

여기는 홈화면입니다.

## 🍳**Remove a git submodule**

From:

[Remove a git submodule (Example)](https://coderwall.com/p/csriig/remove-a-git-submodule)

### T**o remove a submodule you need to: 🐌**

1. Delete the relevant line from the .gitmodules file.
2. Delete the relevant section from .git/config.
3. Run git rm --cached path*to*submodule (no trailing slash).
4. Commit the superproject.
5. Delete the now untracked submodule files.

Source(s): [https://git.wiki.kernel.org/index.php/GitSubmoduleTutorial](https://git.wiki.kernel.org/index.php/GitSubmoduleTutorial)
