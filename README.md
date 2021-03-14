# WeCanCode
Let's code together to show that, yes we CAN code!

## Purpose
The WeCanCode Club is meant to bring people together of all skillsets, and give them a place to learn more about web development, git, github, and collaboration.

WeCanCode is a website that is hosted by Amazon Amplify and will deploy code that is merged into the main branch of this repository. This means you can fork this code, create a new branch, and add your own profile. Then if you create a pull request and it is approved and merged into main you will see your code live on the internet!

If you are still kind of confused, don't sweat it! This is all about inclusion. Anyone can contribute as long as they don't add any hateful, offensive, or otherwise inappropriate content. What is inappropriate will be determined on a case by case basis by those who have merge access.

# How To Get Started
To Get started Fork the this repository so you can have a local copy and make changes. Don't know what that means? It's okay, check out the **Forking** section below. Then you can create a **Pull Request** and have your code **Merged** into the main branch. This will kick off a process handled by **Amazon Amplify** which will publish the code to the website WeCanCode.club. You will then be able to see your updates live on the internet! Feel free to share in your portfolio and with family and friends. By having this repository on your GitHub profile it will also show future employers work that you have done to collaborate with others.

## Forking
In the upper right hand side of this page, underneath your profile picture, is a badge that says "Fork". What this does is creates a "Fork" or a copy of this repository. Think of it like making a copy of a word document that you and a friend are working on for class. By making a copy you can go off and make your own changes to your section of the paper. Then when you are ready to combine your changes with your friends copy, then you can create a **Pull Request** (as detailed out below). This is a request to *pull* in your changes to the code (or in this metaphor the work you did on the paper). Once someone with **Merge** access does a **Code Review** and **Approves your Pull Request** then it will be **Merged** into the main branch. Think of the main branch like the final copy of your paper that you are going to hand in to the teacher.

It is called merging because you could have made changes throughout the entire document, not just you specific chapter. A spelling change here, a punctuation addition here, maybe even some grammar adjustments. Well, what should happen if you both made *different* changes to the same word or sentence? That would be handled as a **Merge Conflict**

A merge conflict is what occurs when there are different changes to the same aspects of the code. The git system can't and won't make an automatic judgement on whose changes are *correct*. So what do you do? Well as detailed out in the **Merge Conflicts** section a tool is used to determine whose changes are correct and each conflict is handled by the person who created the pull request. Then once they have decided whose changes are deemed correct the pull request can be updated and then the code can be merged.

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

## Adding Your Code
Once you have the repository forked you need to clone (download) that code onto your computer. This can be done two ways. The first way is through the terminal (command line). You should see a green button near the top of the page that says "Code". Once you click that you will see some options.

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

TBD

### CLI
>GitHub CLI will allow you to clone the repository using GitHub's official CLI tool

TBD

### GitHub Desktop
The other method you can use is by using the GitHub Desktop app. This will utilize their GUI (Graphic User Interface) to manage the local copy of the repository. If you click this option it will take you to a page to download the GitHub Desktop app or open it on your computer.


## Pull Requests
TBD (which stands for To Be Determined) This is something you can help with!

## Merge Conflicts
TBD

## Issues
TBD

## Wiki
TBD

## Templates
TBD
