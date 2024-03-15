# Test for submodule coworking and docker compose

## Git Submodule

### Process

#### link new submodule, and better to use ssh url.

```bash
git submodule add <url> <path>
```

#### grabbing updates inside a submodule

1. `cd` to the submodule
2. `git pull` to update update the project
3. back to the main project and `git add`, `git commit` and push.

#### removing submodules

1. `git submodule deinit path/to/module`
2. `git rm path/to/module`
3. `git commit`

## Docker

### Compose process
