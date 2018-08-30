# bisect-demo
Repository to demonstrate the tool `git bisect`


This is for demonstrating the tool [git bisect](https://git-scm.com/docs/git-bisect)

Usage:

- `git bisect start` to start bisect session
- `git bisect bad` to indicate, that the bug is still present
- `git bisect good daf804357` to indicate, that the bug is not present on inital commit
- Proceed to use `bad` and `good` until bug is found
- `git bisect reset` to exit the current bisect session.
