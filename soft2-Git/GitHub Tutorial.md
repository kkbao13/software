# GitHub Tutorial

​                    

1. [Intro](https://guides.github.com/activities/hello-world/#intro)
2. [What is GitHub?](https://guides.github.com/activities/hello-world/#what)
3. [Create a Repository](https://guides.github.com/activities/hello-world/#repository)
4. [Create a Branch](https://guides.github.com/activities/hello-world/#branch)
5. [Make a Commit](https://guides.github.com/activities/hello-world/#commit)
6. [Open a Pull Request](https://guides.github.com/activities/hello-world/#pr)
7. [Merge Pull Request](https://guides.github.com/activities/hello-world/#merge)

The **Hello World** project is a time-honored tradition  in computer programming. It is a simple exercise that gets you started  when learning something new. Let’s get started with GitHub!

在计算机编程中,`Hello World`项目有历史悠久的传统。它是你在学习新东西时一个简单的练习让你起步。让我们开始使用GitHub！ 

**You’ll learn how to:**

- Create and use a repository	创建并使用`repository`
- Start and manage a new branch     开始并管理一个新的`branch`
- Make changes to a file and push them to GitHub as commits    更改文件的更改并将它们作为commits
- Open and merge a pull request    打开和合并一个`pull`请求 


## What is GitHub?

GitHub is a code hosting platform for version control and  collaboration. It lets you and others work together on projects from  anywhere.

This tutorial teaches you GitHub essentials like *repositories*, *branches*, *commits*, and *Pull Requests*.  You’ll create your own Hello World repository and learn GitHub’s Pull  Request workflow, a popular way to create and review code.

`GitHub`是用于版本控制和协作的代码托管平台。它可以让您和其他人在任何地方协同工作。 

本教程教您GitHub基本知识，如存储库，分支，提交和Pull请求。您将创建自己的Hello World存储库并学习GitHub的Pull Request工作流，这是一种创建和检查代码的流行方法。 

#### No coding necessary

To complete this tutorial, you need a [GitHub.com account](http://github.com)  and Internet access. You don’t need to know how to code, use the  command line, or install Git (the version control software GitHub is  built on).

> **Tip:** Open this guide in a separate browser window (or tab) so you can see it while you complete the steps in the tutorial.

## Step 1. Create a Repository

A **repository** is usually used to organize a single  project. Repositories can contain folders and files, images, videos,  spreadsheets, and data sets – anything your project needs. We recommend  including a *README*, or a file with information about your  project. GitHub makes it easy to add one at the same time you create  your new repository. *It also offers other common options such as a license file.*

Your `hello-world` repository can be a place where you store ideas, resources, or even share and discuss things with others.

一个存储库通常用于组织单个项目，存储库可以包含文件夹和文件，图像，视频，电子表格和数据集 - 您的项目需要的任何内容。我们建议包括每个Repo包含一个README或文件说明项目信息。 GitHub可以在创建新存储库的同时轻松添加一个。它还提供其他常见选项，例如许可证文件。 

您的hello-world存储库可以是存储想法，资源，甚至与他人共享和讨论事物的地方。 

### To create a new repository

1. In the upper right corner, next to your avatar or identicon, click 

1.  and then select **New repository**.
2. Name your repository `hello-world`.
3. Write a short description.
4. Select **Initialize this repository with a README**.

![new-repo-form](https://guides.github.com/activities/hello-world/create-new-repo.png)

Click **Create repository**.

## Step 2. Create a Branch

**Branching** is the way to work on different versions of a repository at one time.

By default your repository has one branch named `master` which is considered to be the definitive branch. We use branches to experiment and make edits before committing them to `master`.

默认情况下，您的存储库有一个名为master的分支，它被认为是权威分支。在将它们提交给master之前，我们使用分支进行实验并进行编辑。 

When you create a branch off the `master` branch, you’re making a copy, or snapshot, of `master` as it was at that point in time. If someone else made changes to the `master` branch while you were working on your branch, you could pull in those updates.

This diagram shows:

- The `master` branch

- A new branch called `feature` (because we’re doing ‘feature work’ on this branch)

  一个名为feature的新分支（因为我们在这个分支上做'功能工作'） 

- The journey that `feature` takes before it’s merged into `master` 功能在合并到主服务器之前所经历的旅程 

![a branch](https://guides.github.com/activities/hello-world/branching.png)

Have you ever saved different versions of a file? Something like:

- `story.txt`
- `story-joe-edit.txt`
- `story-joe-edit-reviewed.txt`

Branches accomplish similar goals in GitHub repositories.

Here at GitHub, our developers, writers, and designers use branches for keeping bug fixes and feature work separate from our `master` (production) branch. When a change is ready, they merge their branch into `master`.

在GitHub，我们的开发人员，编写人员和设计人员使用分支来保持错误修复和功能工作与主（生产）分支分开。当更改准备就绪时，它们将其分支合并到主服务器中。

### To create a new branch

1. Go to your new repository `hello-world`.
2. Click the drop down at the top of the file list that says **branch: master**.
3. Type a branch name, `readme-edits`, into the new branch text box.
4. Select the blue **Create branch** box or hit “Enter” on your keyboard.

![branch gif](https://guides.github.com/activities/hello-world/readme-edits.gif)

Now you have two branches, `master` and `readme-edits`. They look exactly the same, but not for long! Next we’ll add our changes to the new branch.

## Step 3. Make and commit changes

Bravo! Now, you’re on the code view for your `readme-edits` branch, which is a copy of `master`. Let’s make some edits.

On GitHub, saved changes are called *commits*. Each commit has an associated *commit message*,  which is a description explaining why a particular change was made.  Commit messages capture the history of your changes, so other  contributors can understand what you’ve done and why.

#### Make and commit changes

1. Click the `README.md` file.
2. Click the 

1.  pencil icon in the upper right corner of the file view to edit.
2. In the editor, write a bit about yourself.
3. Write a commit message that describes your changes.
4. Click **Commit changes** button.

![commit](https://guides.github.com/activities/hello-world/commit.png)

These changes will be made to just the README file on your `readme-edits` branch, so now this branch contains content that’s different from `master`.

## Step 4. Open a Pull Request

​	Nice edits! Now that you have changes in a branch off of `master`, you can open a *pull request*.

​	很好的编辑！现在您在master的分支中有更改，您可以打开pull请求。 

​	Pull Requests are the heart of collaboration on GitHub. When you open a *pull request*,  you’re proposing your changes and requesting that someone review and  pull in your contribution and merge them into their branch. Pull  requests show *diffs*, or differences, of the content from both branches. The changes, additions, and subtractions are shown in green and red.

​	Pull Requests是GitHub上合作的核心 。当您打开拉取请求时，您提出了更改并请求某人审核并提取您的贡献并将其合并到他们的分支中。 拉请求显示来自两个分支的内容的差异或差异。更改，添加和减少以绿色和红色显示。 提交后，即使在代码完成之前，您也可以打开拉取请求并开始讨论。 通过在拉取请求消息中使用GitHub的@mention系统，您可以询问特定人员或团队的反馈，无论他们是在大厅还是10个时区之外。 您甚至可以在自己的存储库中打开pull请求并自行合并。在开展大型项目之前，这是学习GitHub流程的好方法。 

As soon as you make a commit, you can open a pull request and start a discussion, even before the code is finished.

By using GitHub’s [@mention system](https://help.github.com/articles/about-writing-and-formatting-on-github/#text-formatting-toolbar)  in your pull request message, you can ask for feedback from specific  people or teams, whether they’re down the hall or 10 time zones away.

You can even open pull requests in your own repository and merge them  yourself. It’s a great way to learn the GitHub flow before working on  larger projects.

#### Open a Pull Request for changes to the README

*Click on the image for a larger version*

| Step      | Screenshot |
| --------- | ---------- |
| Click the |            |

| **Pull Request** tab, then from the Pull Request page, click the green **New pull request** button. | [![pr-tab](https://guides.github.com/activities/hello-world/pr-tab.gif)](https://guides.github.com/activities/hello-world/pr-tab.gif) |
| ------------------------------------------------------------ | ------------------------------------------------------------ |
| In the **Example Comparisons** box, select the branch you made, `readme-edits`, to compare with `master` (the original). | [![branch](https://guides.github.com/activities/hello-world/pick-branch.png)](https://guides.github.com/activities/hello-world/pick-branch.png) |
| Look over your changes in the diffs on the Compare page, make sure they’re what you want to submit. | [![diff](https://guides.github.com/activities/hello-world/diff.png)](https://guides.github.com/activities/hello-world/diff.png) |
| When you’re satisfied that these are the changes you want to submit, click the big green **Create Pull Request** button. | [![create-pull](https://guides.github.com/activities/hello-world/create-pr.png)](https://guides.github.com/activities/hello-world/create-pr.png) |
| Give your pull request a title and write a brief description of your changes. | [![pr-form](https://guides.github.com/activities/hello-world/pr-form.png)](https://guides.github.com/activities/hello-world/pr-form.png) |

When you’re done with your message, click **Create pull request**!

------

> **Tip**: You can use [emoji](https://help.github.com/articles/basic-writing-and-formatting-syntax/#using-emoji) and [drag and drop images and gifs](https://help.github.com/articles/file-attachments-on-issues-and-pull-requests/) onto comments and Pull Requests.

## Step 5. Merge your Pull Request

In this final step, it’s time to bring your changes together – merging your `readme-edits` branch into the `master` branch.

1. Click the green **Merge pull request** button to merge the changes into `master`.
2. Click **Confirm merge**.
3. Go ahead and delete the branch, since its changes have been incorporated, with the **Delete branch** button in the purple box.

![merge](https://guides.github.com/activities/hello-world/merge-button.png) ![delete](https://guides.github.com/activities/hello-world/delete-button.png)

### Celebrate!

By completing this tutorial, you’ve learned to create a project and make a pull request on GitHub!

Here’s what you accomplished in this tutorial:

- Created an open source repository
- Started and managed a new branch
- Changed a file and committed those changes to GitHub
- Opened and merged a Pull Request

Take a look at your GitHub profile and you’ll see your new [contribution squares](https://help.github.com/articles/viewing-contributions)!

To learn more about the power of Pull Requests, we recommend reading the [GitHub flow Guide](http://guides.github.com/overviews/flow/). You might also visit [GitHub Explore](http://github.com/explore) and get involved in an Open Source project.

------

> **Tip**: Check out our other [Guides](http://guides.github.com), [YouTube Channel](http://youtube.com/githubguides) and [On-Demand Training](https://services.github.com/on-demand/) for more on how to get started with GitHub.

Last updated April 7, 2016