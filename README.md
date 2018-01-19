# GitCheatSheet

Git snippets

## Unstage all files you might have staged with git add:

```
git reset
```

## Revert all local uncommitted changes (should be executed in repo root):

```
git checkout .
```

### Revert uncommitted changes only to particular file or directory:

```
git checkout [some_dir|file.txt]
```

## Yet another way to revert all uncommitted changes 

(longer to type, but works from any subdirectory):

```
git reset --hard HEAD
```

## Remove all local untracked files, so only git tracked files remain:

```
git clean -fdx
```
