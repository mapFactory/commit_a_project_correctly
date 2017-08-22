I build projects that I use in other locations. But they are not binaries. 
<br>They are scaffolds... templates.
<br>Scaffolds are no fun.
<br>They do not perform commit history correctly.

# commit_a_project_correctly
commit a foreign project into your project:
 * Commit's are meant to be readable and never retyped.
 * Credit remains with the guy who made the project.

When I bring a github repository into a github project; 
<br>I want to move that sub github repo's git information into the main repo's git.


<pre>
-- main_project/.git
---- main_project/sub_project/.git
#move sub_project's git information onto the top of main_project's git information.

#now deinitialize sub_projects .git information.
-- main_project/.git --- with new info.
---- main_project/subproject/no_longer_any_gitfile.
</pre>

## Possible initial Implementation plans.
1. Move git information on top of .git file. <br> Benefit of this plan is it will be cool "git stuff".
2. GitHub hook, or git Hook that pushes hardcoded commit messages.
3. Same as git hook, but instead a script pushes hard coded commits.

Copyright: Michael Dimmitt
<br>core team members: * pending volunteers * 😛 
