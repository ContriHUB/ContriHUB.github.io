# ContriHUB Official Website

Hello Noobs :wave:

Use this project to make your first contribution to the world of Open Source on GitHub :octocat: . Practice making your first pull request to a public repository before doing the real thing!

Join us by getting involved in the open source community solving some interesting tasks along the way.

This repository is open to all students of MNNIT.

Also note that this repository is part of ContriHUB, MNNIT's first OpenSource event in Avishkar :smiley:

Other repositories which are part of ContriHUB can be accessed here -
[ContriHUB](https://github.com/ContriHUB/)

**Make sure to get your GitHub Student Pack here:** [https://education.github.com/pack](https://education.github.com/pack)

## What is ContriHUB?

A 25 days long contest from October 5th - October 29th to get people involved in [Open Source](https://github.com/open-source). This repo is just the guide to get started on GitHub. We have a lot of different projects coming up. So start contributing and while you are at it, keep checking for more projects as they are added!

Choose any project and start fixing the issues. You can propose new features too !! Every feature you add or an issue you fix will fetch you some points according to the difficulty. At the end of the month, one who has the most points will be the winner. There are goodies waiting for you :P. Also, there are special arrangements just for first year. So, Stay tuned and keep checking the repos [here](https://github.com/ContriHUB) for more projects and issues :smiley:

So, if you want to contribute to a particular project by either fixing an issue or adding a feature, all you have to do is

-   Fork the project
-   Create a new branch
-   Add a feature /fix the issue
-   Create a Pull Request
-   Submit the link to your Pull Request [here](https://contrihub21.herokuapp.com/)
-   Wait for it to accept and grab your points :smiley:

Also, please make sure to follow the proper formatting such as

```markdown
fixes #1
```

if you want your PR to be approved. The correct formatting should be followed. We won't help you there.

If you don't know what the above means , just keep reading ... you'll get there.

We will not be accepting more PR's until the formatting of the current files is fixed. Please fix those, referencing the issues present. Also note that the issues and the PR have common # numbers , so the first issue might not be #1 but could be #138 . Please check this before referencing the issue. Incorrect # numbers will not be merged.

## How to contribute to this project

Here are 2 quick and painless ways to contribute to this project:

-   Add your name to the `CONTRIBUTORS.md` file
-   Add your entry to the `participant.html` file

Choose one or both, make a pull request for your work and wait for it to be merged!

## Getting Started

-   Fork this repository (click the Fork button in the top right of this page, click your Profile Image)
-   Clone your fork down to your local machine

```markdown
git clone https://github.com/your-username/XXXXX.git
```

-   Create a branch

```markdown
git checkout -b branch-name
```

-   Make your changes (choose from any task below)
-   Commit and push

```markdown
git add .
git commit -m 'Commit message'
git push origin branch-name
```

-   Create a new pull request from your forked repository (click the `New Pull Request` button located at the top of your repo)
-   Wait for your PR review and merge approval!
-   **Star this repository** :star: if you had fun!

## Choose from these tasks

### 1. Add your name

Add your name to the `CONTRIBUTORS.md` file using the below convention:

```markdown
#### Name: [YOUR NAME](Your Profile Link)

-   Place: City, State, Country
-   Bio: Who are you?
-   GitHub: [Github account link](GitHub link)
```

### 2. Add name inside HTML

Firstly add your profile picture in 'profile' directory present under 'img' directory. Then in the `participant.html` file, look for the 'div' which contains the sample participant info. Then insert a new 'div' inside it with your profile details, in the format shown below -

```html
<div
    class="
        col-xs-12 col-sm-12 col-md-6 col-lg-3
        mb-3
        d-flex
        align-items-stretch
        justify-content-center
    "
>
    <div
        class="
            card
            justify-content-center
            align-items-center
        "
    >
        <img
            src="{Link To Your Image}"
            class="card-img-top"
            alt="Card Image"
            style="max-height: 250px; max-width: 250px"
        />
        <div class="card-body d-flex flex-column">
            <h5 class="card-title">{Your Name}</h5>
            <p
                id="member-intro"
                class="
                    custom-scrollbar-js
                    card-text
                    mb-4
                    sm-6
                "
                style="
                    max-width: 250px;
                    max-height: 200px;
                    overflow-y: auto;
                "
            >
                {Your Bio}
            </p>
            <a
                href="https://github.com/pirateksh"
                class="btn btn-primary"
                style="margin-top: auto"
                >See Profile</a
            >
        </div>
    </div>
</div>
```

Please do not remove the sample participant info otherwise your Pull Request will not be merged.

## Reference links

Here is a great tutorial for creating your first pull request by [Roshan Jossey](https://github.com/Roshanjossey):
[https://github.com/Roshanjossey/first-contributions](https://github.com/Roshanjossey/first-contributions)

Managing your Forked Repo: [https://help.github.com/articles/fork-a-repo/](https://help.github.com/articles/fork-a-repo/)

Syncing a Fork: [https://help.github.com/articles/syncing-a-fork/](https://help.github.com/articles/syncing-a-fork/)

Keep Your Fork Synced: [https://gist.github.com/CristinaSolana/1885435](https://gist.github.com/CristinaSolana/1885435)

Checkout this list for README examples - Awesome README [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)

Github-Flavored Markdown [https://guides.github.com/features/mastering-markdown/](https://guides.github.com/features/mastering-markdown/)

## Contacts

For any query head on to dedicated Gitter Channel - [ContriHUB](https://gitter.im/ContriHUB/Lobby#)

If you still have more doubts then feel free to ping any of the student co-ordinator.

Coordinators -

-   [Abhey Rana](https://github.com/Abhey)

-   [Akshay Sharma](https://github.com/akshay31057)

-   [Deepak Bharti](https://github.com/dbads)
