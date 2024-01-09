#  violet-git
>  It builds from repository and build

# You can use with 
[violet-manager](https://github.com/TaYaKi71751/violet-manager)

#  Build.yml
```
env:
  target_owner:      '<TARGET_USER_NAME_HERE>'      # default: 'project-violet'
  target_repository: '<TARGET_REPOSITORY_HERE>'     # default: 'violet'
  target_ref:        '<TARGET_BRANCH_HERE>'         # default: 'dev'
```

#  Files
## dev_hash
>  hash of '<TARGET_OWNER>/<TARGET_REPOSITORY>#<TARGET_BRANCH>'

## appversion
>  '<APP_VERSION_NAME>+<BUILD_HASH>'

# How to get <BUILD_HASH> from app-release.apk
> It's in assets/HEAD
```
unzip app-release.apk -d apk-extract                # extract apk file
cat   apk-extract/assets/flutter_assets/assets/HEAD # hash here
```
