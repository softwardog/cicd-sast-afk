## Release 1st


### Version numbers

For WebGoat we use milestone releases first before we release the official version, we use `v1.0.0.M3` while tagging
 and 1.0.0.M3 in the .global.CONF file

At the moment we use Gitflow, for a release you create a new release branch and take the following steps:

```
git checkout develop
git flow release start <version>
-- build_command versions:set <<version>>  
git commit -am "New release, updating file.xpto" 
git flow release publish
git push --tags
```
Thanks For Now !


