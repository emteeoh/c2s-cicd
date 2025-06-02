
# cheatsheet:

## to modify a tag:
`<edit code>`  
git commit  
git tag -f v1    # -f forces tag to be moved  
git push  
git push origin --force v1  #move the tag upstream to this commit


## plan:
I think I'll tag using something that matches the feature branch. eg ito73.
Once the feature is merged into c2s@develop, I can also tag it as main and then
later c2s@develop can be migrated off ito73 to main, but I'm not certain this step is necessary.
