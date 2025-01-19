# Diff sample

This repository contains some sample files in folder [zoo](zoo). The changes
were crafted in a way to represent basic scenarios for diff file generated from
this e.g.:

```bash
FIST_COMMIT=$(git rev-list --max-parents=0 HEAD)

# print diff between the first commit and the latest
git diff --unified=0 $FIST_COMMIT HEAD -- zoo
```
