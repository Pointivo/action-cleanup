## Pointivo Action: Cleanup

Cleans up any leftovers from the build process.


### Upload

```bash

git add .
git commit -m "Update Action"
git push

git tag -fa -m "Updates to the Action" v1
git push origin master -f --tags
```