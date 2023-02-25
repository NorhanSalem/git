## Tell me how to remove them locally and remotely.
## How to Remove Branches locally
### if the branch is merged
 
git branch -d dev


 git branch -d test
  

### if the branch is not merged
 
git branch -D dev

 
git branch -D test

## How to Remove Branches Remotly
 
git push origin :dev


git push origin :test

## Tell me how to list tags

git tag


##Tell me how to delete tag locally and remotely.
## Delete Tag Locally

git tag -d v1.7

## Delete Tag Remotly

git push origin --delete v1.7

## Adding Image
![Image](1..jpg)

