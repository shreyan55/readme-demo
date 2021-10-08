# HacktoberFest-2021 🏆

#### 🎯 HacktoberFest - The month long festival for developers

- This repository aims to give an introduction as to how the Open Source World functions. Use this project to make your first contribution to an open-source project on GitHub. Practice making your first pull request to a public repository before doing the real thing!

- Make sure to grab some cool swags during Hacktoberfest by getting involved in the open-source community and completing some simple tasks in this project.

- This repository is open to all members of the GitHub community. Any member can contribute to this project without being a collaborator. We encourage first time contributors, and also have interesting tasks for experienced developers.


# <b>What is Hacktoberfest?</b> 😕

A month-long celebration from October 1st to October 31st presented by Digital Ocean and DEV Community collaborated with GitHub to get people involved in Open Source. Create your very first pull request to any public repository on GitHub and contribute to the open-source developer community.

https://hacktoberfest.digitalocean.com/

## Rules ⚓

To earn your Hacktoberfest tee or tree reward, you must register and make four valid pull requests (PRs) between October 1-31 (in any time zone). PRs can be made to participating public repos on GitHub, those that have the Hacktoberfest topic. If a maintainer reports your pull request as spam or behavior not in line with the project’s code of conduct, you will be ineligible to participate. This year, the first 70,000 participants who successfully complete the challenge will be eligible to receive a prize.

- <b>Read the participation details to learn how to earn your Hacktoberfest tee or tree reward. </b>

- <b>Those who have not registered yet for hacktoberfest can get themselves registered <a href="https://hacktoberfest.digitalocean.com/register">HERE</a></b>
<hr>

# How to Setup & Contribute 

<details>
 <summary> click here</summary>
 
 ### 0. Star The Repo :star2:

Star the repo by pressing the topmost-right button to start your wonderful journey.


### 1. Fork it :fork_and_knife:

You can get your own fork/copy of [Hacktoberfest-21](https://github.com/ietebitmesra/Hacktoberfest-21) by using the <a href="https://github.com/helios1101/HacktoberFest_20/new/master?readme=1#fork-destination-box"><kbd><b>Fork</b></kbd></a> button on top-right of your screen.

 [![Fork Button](https://help.github.com/assets/images/help/repository/fork_button.jpg)](https://github.com/ietebitmesra/Hacktoberfest-21/)


### 2. Clone it :busts_in_silhouette:

`NOTE: commands are to be executed on Linux, Mac, and Windows(using Powershell)`

You need to clone (download) it to local machine using

```sh
$ git clone https://github.com/Your_Username/Hacktoberfest-21.git
```

> This makes a local copy of the repository in your machine.
Once you have cloned the `Hacktoberfest-21` repository in Github, move to that folder first using change directory command on Linux, Mac, and Windows(PowerShell to be used).

```sh
# This will change directory to a folder Hacktoberfest-21
$ cd Hacktoberfest-21
```

Move to this folder for all other commands.

### 3. Set it up :arrow_up:

Run the following commands to see that *your local copy* has a reference to *your forked remote repository* in Github :octocat:

```sh
$ git remote -v
origin  https://github.com/Your_Username/Hacktoberfest-21.git (fetch)
origin  https://github.com/Your_Username/Hacktoberfest-21.git (push)
```

Now, let's add a reference to the original [Hacktoberfest-21](https://github.com/ietebitmesra/Hacktoberfest-21/) repository using

```sh
$ git remote add upstream https://github.com/ietebitmesra/Hacktoberfest-21.git
```

> This adds a new remote named ***upstream***.
See the changes using

```sh
$ git remote -v
origin    https://github.com/Your_Username/Hacktoberfest-21.git (fetch)
origin    https://github.com/Your_Username/Hacktoberfest-21.git (push)
upstream  https://github.com/Remote_Username/Hacktoberfest-21.git (fetch)
upstream  https://github.com/Remote_Username/Hacktoberfest-21.git (push)
```
`In your case, you will see`
```sh
$ git remote -V
origin    https://github.com/Your_Username/Hacktoberfest-21.git (fetch)
origin    https://github.com/Your_Username/Hacktoberfest-21.git (push)
upstream  https://github.com/ietebitmesra/Hacktoberfest-21.git (fetch)
upstream  https://github.com/ietebitmesra/Hacktoberfest-21.git (push)
```

### 4. Sync it :recycle:

Always keep your local copy of the repository updated with the original repository.
Before making any changes and/or in an appropriate interval, run the following commands *carefully* to update your local repository.

```sh
# Fetch all remote repositories and delete any deleted remote branches
$ git fetch --all --prune
# Switch to `master` branch
$ git checkout master
# Reset local `master` branch to match the `upstream` repository's `master` branch
$ git reset --hard upstream/master
# Push changes to your forked `Hacktoberfest-21` repo
$ git push origin master
```

### 5. Ready Steady Go... :turtle: :rabbit2:

Once you have completed these steps, you are ready to start contributing by checking our `Help Wanted` Issues and creating [pull requests](https://github.com/ietebitmesra/Hacktoberfest-21/pulls).

### 6. Create a new branch :bangbang:

Whenever you are going to contribute. Please create a separate branch using command and keep your `master` branch clean (i.e. synced with remote branch).

```sh
# It will create a new branch with name Branch_Name and switch to branch Folder_Name
$ git checkout -b BranchName
```

Create a separate branch for contribution and try to use the same name of the branch as of folder.

To switch to the desired branch

```sh
# To switch from one folder to other
$ git checkout BranchName
```

To add the changes to the branch. Use

```sh
# To add all files to branch Folder_Name
$ git add .
```

Type in a message relevant for the code reviewer using

```sh
# This message get associated with all files you have changed
$ git commit -m 'relevant message'
```

Now, Push your awesome work to your remote repository using

```sh
# To push your work to your remote repository
$ git push -u origin BranchName
```

Finally, go to your repository in the browser and click on `compare and pull requests`.
Then add a title and description to your pull request that explains your precious effor
 
 
 
 
 
</details>
# Teini

[![Deploy with Vercel](https://vercel.com/button)](https://vercel.com/new/clone?repository-url=https%3A%2F%2Fgithub.com%2Fzeekrey%2Fteini&env=STRIPE_SECRET_KEY,NEXT_PUBLIC_STRIPE_PUBLISHABLE_KEY,SHOP_NAME,SHOP_CONTACT,SHOP_HEADLINE,SHOP_SUBHEADLINE&envDescription=You'll%20need%20Stripe%20API%20key.&envLink=https%3A%2F%2Fstripe.com%2Fdocs%2Fkeys&project-name=teini-copy&repo-name=teini-copy&redirect-url=https%3A%2F%2Fkrey.io&demo-title=Teini%20-%20The%20smallest%20eShop%20in%20the%20world&demo-description=A%20real%20online%20store.%20But%20without%20the%20costs%20and%20without%20complexity.&demo-url=https%3A%2F%2Fteini.co&demo-image=https%3A%2F%2Fimages.unsplash.com%2Fphoto-1494256997604-768d1f608cac%3Fixid%3DMnwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8%26ixlib%3Drb-1.2.1%26auto%3Dformat%26fit%3Dcrop%26w%3D1829%26q%3D80) 

## Installation

### ...if you're not a developer

#### Accounts needed

Running Teini should be easy and for free. Although you'll need to create some accounts to make it work:

| Account       | Description/What it does                                                   | Link                |
| ------------- | -------------------------------------------------------------------------- | ------------------- |
| Vercel        | Deploys and keeps the actual website running. It's awesome.                | https://vercel.com/ |
| Stripe        | Provides the whole checkout and payment infrastructure. It's awesome, too. | https://stripe.com  |
| Github/Gitlab | The place where the source code is stored. Awesome - yep.                  | https://github.com  |

> 🤑 While Vercel and Github should be free while respecting their fair use policies, Stripe will cost some money. Fortunately, these are transaction-dependent.
#### Environment Variables

To configure your store you need to set some meta data and credentials upfront. The following data needs to be set:

| Environment Variable               | Description                                                                                          | Default |
| ---------------------------------- | ---------------------------------------------------------------------------------------------------- | ------- |
| STRIPE_SECRET_KEY                  | The Stripe secret key: https://stripe.com/docs/keys#obtain-api-keys                                  |
| NEXT_PUBLIC_STRIPE_PUBLISHABLE_KEY | The Stripe publishable key: https://stripe.com/docs/keys#obtain-api-keys                             |
| SHOP_NAME                          | Will show up in the browser tab and in the seo config.                                               |
| SHOP_CONTACT                       | A way customers can contact your. Could be an email or a Twitter handle. Will show up in the footer. |
| SHOP_HEADLINE                      | Will show up on the index (start) page and in the seo config.                                        |
| SHOP_SUBHEADLINE                   | Will show up on the index (start) page and in the seo config.                                        |

Once you got everything together you can finally deploy your own version for Teini:

[![Deploy with Vercel](https://vercel.com/button)](https://vercel.com/new/clone?repository-url=https%3A%2F%2Fgithub.com%2Fzeekrey%2Fteini&env=STRIPE_SECRET_KEY,NEXT_PUBLIC_STRIPE_PUBLISHABLE_KEY,SHOP_NAME,SHOP_CONTACT,SHOP_HEADLINE,SHOP_SUBHEADLINE&envDescription=You'll%20need%20Stripe%20API%20key.&envLink=https%3A%2F%2Fstripe.com%2Fdocs%2Fkeys&project-name=teini-copy&repo-name=teini-copy&redirect-url=https%3A%2F%2Fkrey.io&demo-title=Teini%20-%20The%20smallest%20eShop%20in%20the%20world&demo-description=A%20real%20online%20store.%20But%20without%20the%20costs%20and%20without%20complexity.&demo-url=https%3A%2F%2Fteini.co&demo-image=https%3A%2F%2Fimages.unsplash.com%2Fphoto-1494256997604-768d1f608cac%3Fixid%3DMnwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8%26ixlib%3Drb-1.2.1%26auto%3Dformat%26fit%3Dcrop%26w%3D1829%26q%3D80)

## Usage

Once your store is up and running you definitly what to add your own products. Here is how to do this:

### 1. Access the repository

To make changes you need to access the repository and change the actual source code. To do this you'll need the following tools (all of them are for free):

- Git -> https://git-scm.com/
- VSCode -> https://code.visualstudio.com/
- Prisma Studio -> https://www.prisma.io/studio

Once you got everything installed open a terminal and type the following command:

```bash
git clone https://github.com/username/reponame
```

> 💡 The repo url depends on your choosen service, username and repo name.
### 2. Make changes to the product database

Open Prisma Studio and open the product.db file. It is located at the root level of your repo and called `products.db`. Once the database add, update or delete products.

### 3. Add product images

Teini holds all its static files like product images in the `public` folder. Product images in particular are store under `public/prodcuts/[productid]`. To add product images you just need to add a folder with the corresponding product-id (see your products.db) and put all product images in there.

> 💡 Google recommends using the WebP as image format. You can convert your files here: https://cloudconvert.com/webp-converter
### 3. Make changes to the store itself

Open a terminal and navigate (cd) to your local repository copy. Run this command:

```bash
code .
```

Now VSCode should open and you can change what ever you want.

### 4.Push your changes

To make your changes visible you need to run the following commands:

```bash
git add .
git commit -m "A message describing your work like; Added images for product 1."
git push
```

If your go to https://vercel.com and open your project you should see that a deployment is started. If it is successfull you customers can see your changes. If it failed feel free to create an issue: https://github.com/zeekrey/teini/issues/new/choose

### ...if you're a developer

Clone, Edit, Push. Do what ever you want.


## Notes

Credits for the used photos:

Product photos
Photo by <a href="https://unsplash.com/@boxedwater?utm_source=unsplash&utm_medium=referral&utm_content=creditCopyText">Boxed Water Is Better</a> on <a href="https://unsplash.com/@boxedwater?utm_source=unsplash&utm_medium=referral&utm_content=creditCopyText">Unsplash</a>

Success Page photo
Photo by <a href="https://unsplash.com/@jdent?utm_source=unsplash&utm_medium=referral&utm_content=creditCopyText">Jason Dent</a> on <a href="https://unsplash.com/s/photos/celebrate?utm_source=unsplash&utm_medium=referral&utm_content=creditCopyText">Unsplash</a>

