# Troubleshooting guide

## Updating your local clone

When you cloned this repository, you got a copy of the files at that moment. As the course goes on, new tutorial notebooks and fixes are added to the remote repository (on GitHub), but they don't appear on your computer automatically. You need to pull them in.

**1. Open a terminal in the repository folder**

- This can be using the terminal in your project folder in VSCode.

**2. Pull the latest changes**

```
git pull
```

This command is the same on Linux, macOS, and Windows. 

Git will download any new or updated files and merge them into your local copy. If you see `Already up to date.`, there is nothing new yet.

Run `git pull` always before starting a new tutorial, so you have the latest version.

## Where to make your edits

**Don't edit the notebooks in the `/tutorials` folder directly.**

Git tracks the files in `/tutorials`. If you change them and we later update the same notebook on the remote repo, `git pull` will fail.

**Instead, work on a copy in the `/local` folder.**

This folder is listed in `.gitignore`, which tells git to ignore it. Anything you put there stays on your machine and never interferes with updates.

1. Copy the notebook you want to work on from `/tutorials` into `/local`. You can do this in your file explorer, or from the terminal (run from the repo root):

   - macOS / Linux:
```
     mkdir -p local
     cp tutorials/tutorial_01.ipynb local/
```
   - Windows:
```
     mkdir local
     copy tutorials\tutorial_01.ipynb local\
```
3. Open and edit the copy in `/local`.

Note that your copy won't update when we update the original. If a notebook in `/tutorials` changes after you've copied it, copy the new version into `/local` under a different name (for example `tutorial_01_v2.ipynb`) so you don't overwrite your own work.

## Common problems

### `git pull` fails with "Your local changes would be overwritten by merge"

This usually means you edited a notebook in `/tutorials` directly. To fix it without losing your work:

1. **Save your edits:** copy the modified notebook from `/tutorials` into `/local`.
2. **Reset the original** to the official version (replace the path with your file):

```
   git restore tutorials/tutorial_01.ipynb
```

   If `git restore` isn't recognized, try with:

```
   git checkout -- tutorials/tutorial_01.ipynb
```
3. **Pull again:**

```
   git pull
```

Your work is now safe in `/local`, and `/tutorials` is up to date with the remote repo.