

# Clone your Project

With things properly configured, you can now clone your project.

First confirm you are in the correct directory:

```bash
pwd
```

This should print `/home/nhcarrigan`, of course replacing `nhcarrigan` with your username. This should *not* be `/root` (if it is, make sure you are logged in as your user account).

Now clone the repository into the directory. Note that you need to use the HTTPS url, not the SSH url, as you haven't authenticated `git`. If you are deploying a private repository, you will need to authenticate `git` or use another method for pulling your files into the VM.

By default, `git` will clone the repository into a directory with the repository's name. If you want a different directory name, replace `(name)` with the name you want the directory to take.

```bash
git clone <https url, NOT ssh url> (name)
```

Switch to the repository directory.

```bash
cd <repo folder (same as repo name)>
```
