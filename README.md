# Git Semver

Git command for semantically versioning tags (a wrapper around the tag command)

## How to use

To increase the version by a major:
```
git semver --break -m "message"
```

To increase the version by a minor:
```
git semver --feature -m "message"
```

To increase the version by a patche:
```
git semver --fix -m "message"
```
