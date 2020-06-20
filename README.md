# Learning about CODEOWNERS files

Just one of the things I'm learning. <https://github.com/hchiam/learning>

Use CODEOWNERS files to auto-assign code reviewers based on which files/folders were changed.

This repo has [an example PR](https://github.com/hchiam/learning-codeowners/pull/2) where [@hchiam](https://github.com/hchiam) was automatically assigned to review, because the [CODEOWNERS](https://github.com/hchiam/learning-codeowners/blob/master/CODEOWNERS) file had `* @hchiam`.

Note: [apparently](https://help.github.com/en/github/creating-cloning-and-archiving-repositories/about-code-owners) you have to set sub-folder-specific owners at the top level, not with separate CODEOWNERS files in respective sub-folders.

More info (short read): <https://tech.people-doc.com/using-github-codeowners-file.html>

More info (longer read): <https://help.github.com/en/github/creating-cloning-and-archiving-repositories/about-code-owners>
