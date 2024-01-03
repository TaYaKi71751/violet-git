# violet-git
> It builds from repository and build

# Build.yml
```
env:
  target_owner: '<TARGET_USER_NAME_HERE>'
  target_repository: '<TARGET_REPOSITORY_HERE>'
  target_ref: '<TARGET_BRANCH_HERE>'
```

# How to get hash from built apk
> It's in assets/HEAD
```
unzip app-release.apk -d apk-extract
cat apk-extract/assets/flutter_assets/assets/HEAD # hash here
```
