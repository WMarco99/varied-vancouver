## 'Varied Vancouver'
A 'crowd-sourced' collection of places of interest in Vancouver (and anywhere vaguely nearby). Please offer us places that you find interesting but are likely yet unknown to most of us. **Working together in groups,** you're to use the 'GitHub flow' you were learning about and practicing in your preparation for class to figure out how to add your to points to the page. This one will be much more of a 'real world' exercise, and not everything will be immediately clear, but the goal is to figure it out with each other and with me... and you will! Also note there are many notes below that help take you through the process!

### Exercise criteria:

* Many of these "places that you find interesting but are likely yet unknown to most of us" are going to be represented as points, but some of them may be polygons or lines. One GeoJSON file can store points lines and polygons at once--unlike most GIS data formats. *All points should have some attribute data filled out.* Note that in GeoJSON each entity can have an entirely different set of attributes, so you don't have to follow your neighbors--you can add your own attribute types that are relevant to your point! And do [remember](https://canvas.ubc.ca/courses/60053/assignments/syllabus), you don't have to contribute personally identifiable information. Also, note that you can explore the styling options!

* Each student in 472 contributes at least one point.

* **This is key:** You each have the obligation to collaboratively and constructively ensure that every member of the group has an adequate understanding of what exactly you all did today, _such that any of your group members could be chosen to explain what was done and why._

#### Warnings:
  * Must use GitHub Desktop and geojson.io to commit your changes. You can't use the GitHub.com interface--except for the final pull request, if you wish.
  * **No manual uploading or downloading of files. No pasting of GeoJSON into the GitHub.com website.** Why? Those don't give you the experience of actually using GitHub in a deep or powerful way. We want you to experience *version control* and the GitHub flow, which are powerful tools of collaboration used in contemporary communities of visualization. 
  * Make sure your pull request doesn't rename any files in (or add any new files to) the 'remote'/online version of Varied-Vancouver that we're all contributing to. If it does, I'll need you to change it.
  
#### Hints on process:

1. You want to *fork* the Varied Vancouver repo first (using GitHub.com is easiest: click the 'Fork' button on the upper right side of the screen). Why? I haven't given you 'write' permissions to my original Varied-Vancouver repository. 'Forking' makes you your own copy of the repository within your own account. Then, you can make a branch, make changes, commit changes, and push those changes to your own 'forked' repository before setting up the pull request to me. This is a GitHub flow similar to [what you did in your "Hello, World" reading/exercise recently.](https://guides.github.com/activities/hello-world/) The rest of these hints below will help you do this.
   1. Note that you may wish to delete this forked repository when done--I'll tell you when/how below. But if you are uncomfortable having a copy of Varied-Vancouver in your account even briefly, contact me, and I will offer you an alternative approach.
1. You next want to use the local program *GitHub Desktop* to **clone your fork** to your local computer. (GitHub Desktop lets you carry out "the GitHub flow", but gives you easier access to the files in the repository, which will be helpful when we want to manipulate a geojson file.)
   1. To clone, you actually start from the GitHub.com webpage for *your forked version* of the Varied-Vancouver repository. Click on the big green button that says "Code". Some options appear. Cloning with "HTTPS" is more common in advanced situations (usually involving the command line), but let's use the newer, easier, most direct way, which is to [click on the "Open with Github Desktop" button.](https://help.github.com/desktop/guides/contributing-to-projects/cloning-a-repository-from-github-to-github-desktop/),  
   1. Note: The 'local path' is where you save that clone on your local computer (H: drive may be good if you're using geography lab computers). You'll soon be needing to manipulate the files in that folder/directory. And when you do alter that folder where GitHub Desktop thinks there is a repository, GitHub Desktop will track any changes you make to the files in that folder. If you forget where the folder is, you can click the "open this repository" link in the middle of GitHub Desktop.
   1. I'm linking you to specific chapters of the help site directly on this page, but if you need it, here is an overall site for [help on GitHub Desktop](https://help.github.com/desktop/guides/contributing-to-projects/).

1. Make a new *branch* on your local repo using GitHub Desktop. Here is help on how to [create a branch](https://help.github.com/desktop/guides/contributing-to-projects/creating-a-branch-for-your-work) and how to [switch into it](https://help.github.com/desktop/guides/contributing-to-projects/switching-between-branches). Name it something relevant to the fact you're adding data. This is the branch you'll make your changes to.

1. To add your points, you'll use [geojson.io](https://geojson.io). Use the Open -> File menu item (*not* the Open -> Github) to open the file from the location where you told GitHub Desktop to store the clone of the repository on your local computer. 

1. When you save your updated file from geojson.io as a GeoJSON file to your local computer (*not* the Save -> Github), you will have to copy it over and replace the original varied-vancouver.geojson file in your local repository's folder.

1. If you've done things right, you should be able to look at the Github Desktop application and see that it has tracked 'changes' to your repo. The desired changes are that the varied-vancouver.geojson file should now have your points in it. Those changes should display in green. 

1. 'Commit' the changes. There's a big blue button you can push on GitHub Desktop for this. It doesn't send them back to your remote repository at GitHub.com yet, but it stages the changes for us to upload in a minute. [Help on committing changes.](https://help.github.com/desktop/guides/contributing-to-projects/committing-and-reviewing-changes-to-your-project/)

1. Now it's time to upload the changes to GitHub. This can be called 'pushing' the changes, 'syncing', or 'publishing' (if it's a new branch that you've just made locally and isn't yet on the GitHub repository), among others. You are 'pushing' to the 'origin', which is your repository at GitHub.com. There is a button on the upper right side of GitHub Desktop that lets you push/publish. Click it. 

1. Now, you can issue a pull request for me to merge the changes you have made in your forked repository into my original repository!
   1. You've seen this happen on GitHub.com before in your "Hello, World" exercise, so feel free to (refer to that exercise page as well as to) go back to GitHub.com to issue the pull request. How? 
   1. At Github.com, go to the webpage of your forked repository. There should be a nice yellow 'recently pushed branch' banner toward the middle-top of the page. You can press the "Compare & pull request" big green button. 
   1. At that point, GitHub should have set up the process for you. You should see/verify that the 'base fork' is my UBC-GEOB472... repository with the 'base' being the master branch. The 'head fork' should be your fork in your account, with the 'compare' branch being whatever branch you were working in. You should see "Able to merge." 
   1. Please leave some brief informative comments as to what you're merging (here, this may be which points you're adding, etc.)
   1. Click the 'Create pull request' big green button! *Yay!!*

1. Once I verify that you've done things correctly, I'll merge the points in. If I have questions, I may leave them on the pull request and you'll be notified at your email. You can respond on the pull request page, or, if either of us has canceled/closed the request because it isn't going to work, you can create a different pull request, as needed.

1. Depending on how many pull requests I get and how quickly, you might have to wait until after class to verify the map. But once you receive the notice that it's been merged, please verify that it's worked correctly and your points are [on the map at my original repository.](https://github.com/UBC-GEOB472-Spring2021/Varied-Vancouver/blob/main/varied-vancouver.geojson) 
   1. At this point, feel free to delete your forked repo. You can do that by going to your repo's page, going into the 'Settings' at the top of your repo and scrolling down until you see the Delete Repo option in red. There's no reason you *need* to delete it--it's just something to do if you want to avoid having your account have a copy of this repository and its contents. If the repository says "Private" next to its name at the top of the page, then the public can't see it (only you and people you give access to, and here, by default, also any people able to access the original repository being forked, which includes the members of this class.)

1. [Tell me here which point you submitted!](https://canvas.ubc.ca/courses/60053/assignments/787497) *Great job!*

If you want to practice this workflow again later, that can be useful, as there's a lot going on above. I'm also happy to help!
