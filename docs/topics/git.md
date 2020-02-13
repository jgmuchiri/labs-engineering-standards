# Git

## (GIT-100) Git Basics

Basic git commands (as outlined in the [Web Training Kit](https://learn.lambdaschool.com/web1/module/rect59e95N6OSvoCd))
should be understood.

Rationale:

- Basic git branching is required for teams to work effectively; avoiding
  complications and delays.

Exceptions:

- None

---

## (GT-110) Only Branch from Master

All branches must be created from the Master branch

Rationale:

- Multiple levels of branching from master creates opportunities for conflicts

Exceptions:

- None

---

## (CQ-120) Cleanup merged branches

After a branch has been merged to master, it must be immediately delete.

Rationale:

- Short-lived branches are a best-practice for minimizing merge conflicts.
  Leaving many branches active in a repository makes it difficult for team members
  to navigate the ongoing work. Once a branch has been reviewed, approved and merged
  into the master branch, it should be immediately deleted.
- A healthy Git repository has a minimum of active branches.
- This is [easy to comply with using GitHub](https://help.github.com/en/github/administering-a-repository/managing-the-automatic-deletion-of-branches).

Exceptions:

- None
