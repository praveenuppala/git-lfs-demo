# git-lfs-demo
This repository demonstrates git-lfs use with artifactory

Create a local repository in Artifactory of type Git LFS. For this example, we will be using a repository called gitlfs-local on https://104.197.232.86/artifactory. To log in, the username is gitlfs and password is demo.

Clone the repository using the command git clone https://github.com/jfrogtraining/git-lfs-demo.git.
Go into that repository using the command cd git-lfs-demo.

Use the command open . to see everything that is currently inside the Github repository.

Add files that you would like to push to the Github repository and any large files that you would like to push to the Git LFS local repository in Artifactory.

Now, type the command git lfs track “*.<file extension>”. The file extension should match the file extension of the files you would like to push to the Git LFS repository in Artifactory. For example, if we wanted to push all the zip files to the Git LFS repository, we would type in git lfs track “*.zip”. If we also wanted to push a war file, we would simply type git lfs track “*.war” on the next

Use the command git add . to add any new or modified files.

Then type git commit -m “<comments>” to record the changes to the repository. The comment can consist of a brief explanation of what you added and/or changed. Finally, type git push to push the files to Github and the Git LFS Repository in Artifactory. You can view large files in Artifactory on the Artifacts page.
