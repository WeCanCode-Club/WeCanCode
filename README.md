# WeCanCode
Let's code together to show that, yes we CAN code!

## Purpose
The WeCanCode Club is meant to bring people together of all skillsets, and give them a place to learn more about web development, git, github, and collaboration.

WeCanCode is a website that is hosted by Amazon Amplify and will deploy code that is merged into the main branch of this repository. This means you can fork this code, create a new branch, and add your own profile. Then if you create a pull request and it is approved and merged into main you will see your code live on the internet!

If you are still kind of confused, don't sweat it! This is all about inclusion. Anyone can contribute as long as they don't add any hateful, offensive, or otherwise inappropriate content. What is inappropriate will be determined on a case by case basis by those who have merge access.

# How To Get Started
To Get started Fork the this repository so you can have a local copy and make changes. Don't know what that means? It's okay, check out the **Forking** section below. Then you can create a **Pull Request** and have your code **Merged** into the main branch. This will kick off a process handled by **Amazon Amplify** which will publish the code to the website WeCanCode.club. You will then be able to see your updates live on the internet! Feel free to share in your portfolio and with family and friends. By having this repository on your GitHub profile it will also show future employers work that you have done to collaborate with others.

## The Process
In the upper right hand side of this page, underneath your profile picture, is a badge that says "Fork". What this does is creates a "Fork" or a copy of this repository. Think of it like making a copy of a word document that you and a friend are working on for class. By making a copy you can go off and make your own changes to your section of the paper. Then when you are ready to combine your changes with your friends copy, then you can create a **Pull Request** (as detailed out below). This is a request to *pull* in your changes to the code (or in this metaphor the work you did on the paper). Once someone with **Merge** access does a **Code Review** and **Approves your Pull Request** then it will be **Merged** into the main branch. Think of the main branch like the final copy of your paper that you are going to hand in to the teacher.

It is called merging because you could have made changes throughout the entire document, not just you specific chapter. A spelling change here, a punctuation addition here, maybe even some grammar adjustments. Well, what should happen if you both made *different* changes to the same word or sentence? That would be handled as a **Merge Conflict**

If you do not have any merge conflicts, and your pull request is approved, then your code will be part of the main branch. Once this happens it will trigger the process on Amazon Amplify to recompile the project with the new code and deploy it to the website. It's kind of like saving the paper you have been collaborating on and that triggers the printer to print it out and it is displayed on a board in the hallway. You have made some changes, merged them in, and then published them. You are a developer!

## Adding Your Code
Once you have the repository forked you need to clone (download) that code onto your computer. This can be done two ways. The first way is through the terminal (command line) and the other way is through the GitHub Desktop App.

## Terminal
You should see a green button near the top of the page that says "Code". Once you click that you will see some options which correspond to the sections below.

### SSH
> SSH allows you to clone the repository using an SSH key pair. If you are familiar with GitHub this is the usual method

If you would like to use this method, but have not before make sure to checkout GitHub's [documentation](https://docs.github.com/en/github/authenticating-to-github/connecting-to-github-with-ssh) about adding SSH keys that will create a secure connection between your computer and your GitHub account. Once you do that you are ready to clone. Here are some basic commands for you to follow in your terminal. If you have a Development folder, change your directory to that. Otherwise make sure you are in whatever folder you want this project to live.

    ~yourComputer: cd Development
    ~yourComputer/Development: git clone git@github.com:WeCanCode-Club/WeCanCode.git
    ~yourComputer/Development: cd WeCanCode
    ~yourComputer/Development/WeCanCode: ls -al

That last command is essentially "list all" which will show you all the files in that folder you just downloaded to your computer.


### HTTPS
>HHTPS will allow you to clone the repository using your GitHub login

TBD (which stands for To Be Determined) This is something you can help with! Check out the issues section below, there is an issue to fill out this section.

### CLI
>GitHub CLI will allow you to clone the repository using GitHub's official CLI tool

TBD

## GitHub Desktop Application
If you click the green code button you will see underneath the clone section is the link to open this repository in the GitHub Desktop application.

### GitHub Desktop
The other method you can use is by using the GitHub Desktop app. This will utilize their GUI (Graphic User Interface) to manage the local copy of the repository. If you click this option it will take you to a page to download the GitHub Desktop app or open it on your computer. If you are downloading if for the first time make sure to follow their installation instructions.

It will first ask you to sign into your account, this is how it creates a secure connection between your computer and your GitHub account. It will ask you to authorize your GitHub Desktop application. This is allowing the program on your computer to access features of your GitHub account.

Configuring your Git account will allow you to change how your commits show up to the world. This is how your name or information will show up when you push code to the repository. I would suggest something professional for when you share your work with prospective jobs or friends.

Under your repositories it should show WeCanCode. if you select that repository it will give you the option to clone. This is how you download the code that exists in the cloud onto your computer. A popup will show you the details of the repository and there shouldn't be any changes you need to make. Once you click Clone it will ask you how you plan to use this fork. You want to select "To contribute to the parent project". This will ensure you are setup correctly to create pull requests with your updates.

To ensure you have the most up to date version of the code select the Current Branch tab at the top. Here you will see some options under branches. At the bottom there is an option to "Choose a branch to merge into main". Once you select that you will see under *other branches* upstream/main. When it says upstream it is referring to the parent repository, which is the one that lives on the WeCanCode Club organization on GitHub. You are wanting to merge any changes from that version of the code into your local version of the code. So Select upstream/main and then hit the button that says "Merge upstream/main into main". This will update your version of the code with any changes from the official version of main into your branch called main. You will now be in *sync* on your local machine.

In order to keep your personal repository updated in the cloud you will need to push your *local* copy of the code up to GitHub. The GitHub desktop app should ask you if you want to push the commits to origin remote. This is a fancy way of saying "push the changes on your local computer to your GitHub repository online". Click on the Push Origin button and it will send the changes up.

You can now verify the changes by going to GitHub in your browser and in your forked version of the repository you will see those updates. Don't forget that you will need to go through this process **every time** the parent repository updates it's main branch.

## Branching
A branch is a way to keep a separate version of the code to make new changes. By *branching* the code out you can create all kinds of havoc and always come back to the *main* branch to have a working version of the site. You are also able to have many branches which can correspond to different features or bugs that you are working on.

### Terminal
To create a branch in the terminal you would enter in a command similar to this

    ~yourComputer/Development/WeCanCode: git checkout -b "feature/NewPage"
Here you can see that we are in the WeCanCode main folder and we are doing **git checkout** with the flag **-b** which stands for branch. We then follow that up with the name of the branch we want. The name "feature/NewPage" is a common branch naming format which lets other contributors know that this branch is a feature and what the feature is.

### GitHub Desktop Application
If you are creating a branch using the GitHub Desktop application click on the current branch box at the top and select the **New Branch** and it will ask you to name the branch. If you enter in "feature/MyPage" and click create branch it will take you back to the main page with the suggestion to publish the branch. Click *publish branch* to push that branch to your GitHub repository online.

It may suggest to create a pull request from that branch, but we are not ready for that yet. At the top of the application you can confirm what branch you are on in the Current Branch box, which should now read "feature/MyPage" or whatever you named your branch.

## Add Your First Changes
A good first place to start with creating changes to the code is to add your profile page from the template to the main page.

- Copy the ProfilePageTemplate.html file
- Change the name of the file to YourNameProfilePage.html
- Ensure that the file is in the same folder as the index.html
- Jazz up your profile page however you like!
- Go to the index.html file and find a Player x div that hasn't been used
- Change the href from ProfilePageTemplate to your profile page file
- Test it out! You can open the index.html file and it should open in your browser

Next you will want to add your new file(s) to git and commit them using command line or the desktop app. Then you will craft the perfect **Commit Message** and push your changes to your branch.

Then you will follow the steps to create a pull request from your branch in your forked repository to the main repository. Once the pull request is reviewed and merged, and after a short wait, you will see your profile page live on the [WeCanCode.club](wecancode.club) site!


## Pull Requests
TBD

## Merge Conflicts
A merge conflict is what occurs when there are different changes to the same aspects of the code. The git system can't and won't make an automatic judgement on whose changes are *correct*. So what do you do? Well as detailed below a tool is used to determine whose changes are correct and each conflict is handled by the person who created the pull request. Then once they have decided whose changes are deemed correct the pull request can be updated and then the code can be merged.

Still confused? Let's think of it like this. Say you have the following sentence in your paper.

>"We decided to go to the store but we couldnt find the milk"

There could definitely be some adjustments here. Your friend *A* decided to change that sentence to the following.

>"We went to the store, but we couldnt find the milk"

You didn't realize they had fixed that sentence and you made the following changes

>"We decided to go to the store, but we couldn't find the milk"

While looking at your pull request you saw this come up as a conflict. What should be done here? Well, git allows you to track individual changes or **commits**. So in this example you could handle the merge conflict by taking some of *A*'s changes and some of yours. (It is more complicated than this, but this is a good example for beginners). You decided on the following result.

>"We went to the store, but we couldn't find the milk"

As you can see, you preferred *A*'s change to the beginning wording of the sentence, but wanted to make sure you fix to "couldnt" and the comma after "but" was carried over into the final copy of the paper.

See! Merge Conflicts aren't that scary...okay they can be.

### Detailed Merge Conflict Workflow
TBD

## Issues
If you scroll to the top of the page you will see a tab called **Issues**. This is where problems, enhancements, and bugs are submitted to be worked on. A problem is different from a bug because it could be an issue with cloning the repository or submitting a pull request. A bug would be something like "when you click on the home button, nothing happens". A request would be something like "add animations when selecting a profile". This is usually done by someone who uses the project, but doesn't have the skill to make that change.

### Best Practices
TBD

## Wiki
TBD

## Templates
TBD
