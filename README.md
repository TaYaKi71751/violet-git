# violet-git
> It builds from repository and build

# Build.yml
```
env:
  target_owner:      '<TARGET_USER_NAME_HERE>'    # default: 'project-violet'
  target_repository: '<TARGET_REPOSITORY_HERE>'   # default: 'violet'
  target_ref:        '<TARGET_BRANCH_HERE>'       # default: 'dev'
```

# How to get hash from built apk
> It's in assets/HEAD
```
unzip app-release.apk -d apk-extract              # extract apk file
cat apk-extract/assets/flutter_assets/assets/HEAD # hash here
```
