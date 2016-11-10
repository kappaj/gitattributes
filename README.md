# A Collection of Useful .gitattributes Templates

Similarly to the [`.gitignore` Templates][gt], we're trying to build 
templates for `.gitattributes`. 

`Common.gitattributes` contains general exclusions that may apply to any project.
Consider including them if they are applicable to your project.

Please contribute by [forking][fk] and sending a [pull request][pr].

Also **please** only modify **one file** per commit. This'll
make merging easier for everyone.

For more information on gitattributes: [gitattributes(5)][g5]

[gt]: https://github.com/github/gitignore
[fk]: http://help.github.com/forking/
[pr]: http://help.github.com/pull-requests/
[g5]: http://schacon.github.com/git/gitattributes.html


From https://stackoverflow.com/questions/19411981/images-corrupt-after-git-push

running git check-attr --all -- path/to/png before and after adding the new gitattributes showed that the image file was originally treated as a text file, and now it's binary (note I had to commit/push the .gitattributes file for it to take effect on remote)
