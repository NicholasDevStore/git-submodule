# git-submodule

### Add submodule

```bash
git submodule add https://github.com/NicholasDevStore/git-submodule-schema.git
```

### Once schema is added to your repo, you have to init and update it.

```bash
git submodule init
git submodule update
```

### Fetch latest change from upstream in submodule

```bash
git submodule update --remote --merge
```
