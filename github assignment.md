# Getting started with Git Lab
## Instructions
In this lab, we'll be going through some basic tasks you'll need to do as you manage the GitHub repository for your CollectionBuilder site. The questions below are designed to help you learn and remember what you need to do to perform these tasks, as well as where you can go to look for help. 

## Creating your repository and editing files
**What did you click on to create a new repository in the web interface of Github (i.e., on Github.com)?**

On my personal repositories page, I clicked the green "New" button near the top right.

**What is the difference between a private and a public repository?**

A public repository is visible to anyone on the internet. A private repository is visible only to people with explicit access, such as organization members or people with whom the creator has shared it.

**Once your repository has been made and has at least one file, what button do you need to click on the web interface in order to create a new file in your repository?**

Near the "Go to File" search box, there is a "+" icon with "Create new file" as an option in the dropdown.

**Describe the steps you took to clone your repository on Github Desktop**

I was logged in on GitHub Desktop with my GitHub account. When I closed and reopened the program, it refreshed my repositories list. That allowed me to click "clone" for the new one.

**What is the title of GitHub documentation?**

GitHub Docs

**What is the URL for GitHub documentation on creating your first repository?**

https://docs.github.com/en/repositories/creating-and-managing-repositories/quickstart-for-repositories

**Where is your local repository versus the remote repository?**

On Windows, my local repository is in .../Documents/GitHub/xzy. The remote repository is on a GitHub server with a URL connected to my GitHub account name.

**What happens when you fetch?** 

You retrieve the updated file list from GitHub along with a changelog of new commits.

**What happens when you pull changes/commits?**

Pull brings the local branch up-to-date by merging local files with the remote repository.

**When working on GitHub Desktop, what order should you generally perform push, pull, and fetch?**

You should `fetch` to make sure your local copy is current and `pull` if there are any changes. Once you've made new changes, you should `commit` those to a branch and `push` the commit to the remote repository.

**What happens when you push commits from your local repository?**

The commits will merge with the remote repository, updating its contents and commit history.

**What is the URL for the Github glossary?**

https://docs.github.com/en/get-started/learning-about-github/github-glossary

**Where can you find a list of your commits?**

On GitHub.com, from the main repository page. To the top right of the file hierarchy, there's a clock icon with the number of commits made. Clicking on this pulls up the commit history. On GitHub desktop, the main view has its own history tab.

**What is the URL for documentation on reverting a commit?**

https://docs.github.com/en/desktop/managing-commits/reverting-a-commit-in-github-desktop?versionId=free-pro-team%40latest&productId=repositories&restPage=creating-and-managing-repositories%2Cquickstart-for-repositories

**How do you revert a commit?**

As a long time BASH addict, I'm now learning how much easier it is on GitHub Dekstop. All you need to do is right click on the commit and select revert. This appears to create a new commit with the revision as the changes.

## Git-flavored markdown
**What is the name of the page or URL in GitHub documentation where there's information on how to format your Markdown for GitHub?**

https://docs.github.com/en/get-started/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax

**What precedes a second-level heading in Github markdown?**

Two hashtags: \#\#

**How do you indicate text that has been struckthrough?**

With two tildas before and after: \~\~xx\~\~

**How do you create a hyperlink in your markdown?**

With two square brackets around the anchor text and parenthesis around the URL.

**How do you link to a section in the same or another markdown file?**

The format resembles a hyperlink, but the URL is a hashtag (only one) followed by the name of the section heading with hyphens in place of any spaces.

**What are the three possible symbols for indicating an unordered list?**

They are the hyphen (\*), asterik (\*), and addition sign (\+).

**Format the following text into a footnote:**
Main text: Alex Wingate went to William and Mary.[^1]  

[^1]: [William and Mary](https://www.wm.edu/) is a university in Williamsburg, VA founded in 1693.
