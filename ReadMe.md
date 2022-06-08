# Read Me

This is a thrown together note taking system made by Troy Fournier. It currently has next to no features. Its purpose is to leverage VS Code & git capabilities to 
efficiently take notes accross multiple repos at work or for personal projects. 

By having this notes repo relative to your other project repos and using the meta files properly git will automatically create task files for sane note keeping
these task files can also be used as informative summaries on git PRs

Everyone is free to copy and build on this. PRs are welcome. 

## Current Features
Required relative directory structure
repos
    <your_project_name_here>
    notes

- automatic note file on branch checkout
    - [post-checkout](./Meta/post-checkout-task-file)
    - to use this copy the bin file with the name `post-checkout` to a relative repo and place in the .git > hooks directory

## Future Improvements
- automatic notes files created in project named dirs
- dev not saying notes file already created


