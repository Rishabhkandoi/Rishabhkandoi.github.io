# Codecademy: HTML &amp; CSS Final Project.
## Description
A portfolio website created for the [Codecademy HTML &amp; CSS Final Project.](https://www.codecademy.com/learn/web)

![html-css-final-project](https://github.com/RicardoEscobar/portfolio/blob/development/img/html-css-final-project.png?raw=true)

## About

This project is about learning HTML &amp; CSS by building a static website.

The use of HTML &amp; CSS is complemented with Bootstrap for layout purposes.

All technologies used here, including Bootstrap are being used on the [Codecademy HTML &amp; CSS Course.](https://www.codecademy.com/learn/web)

## Tools used

I use an old [Lenovo Thinkpad T430](https://www.amazon.com/Lenovo-Thinkpad-T430-Certified-Refurbished/dp/B01BPEM714/ref=sr_1_3?ie=UTF8&qid=1465402220&sr=8-3&keywords=lenovo+thinkpad+t430) with [Ubuntu Mate 16.04](https://ubuntu-mate.org/download/) as the operative system.

My text editor is Github's official text editor [Atom](https://atom.io/).

I use [GIT](https://git-scm.com/downloads) &amp; [Github](https://github.com/) to keep track of my source code.

I use both [Mozilla Firefox](https://www.mozilla.org/en-US/firefox/new/) &amp; [Google Chrome](https://www.google.com/chrome/) as web browsers to test the code.

## Web hosting

At this point, the site is not being hosted on the Internet.

I'm considering several options to do that:

- [Digital Ocean](https://www.digitalocean.com/). Rent a server, and install server software to host the site.

- [Amazon AWS](https://aws.amazon.com/). I been reading great things about Amazon Web Services, and at this point, I'm unable to confirm my account on AWS. So I may not try the service yet.

- [Namecheap](https://www.namecheap.com/). I do rent domain name services there, and they do have hosting plans, keeping the domain and the hosting on the same place, may be an advantage.

## Deploy

I'm planning to choose and deploy the website once it's completed. I need to solve the Amazon AWS issue with my account, before making a decision about the hosting service I'm going to use.

## Git Branches

I have two main branches for this project:

- __master__. This branch contains the commits of the production code. This is the most stable branch and the branch used to publish the website.

- __development__. This branch contains the day to day work and tests on the website. From this branch, I do branchout to other shorter branches to work on different features of the project. If the change is small enough, I may use the __development__ branch to commit those changes. This branch merges with __master__ once it's work is completed and stable for production.

For __development__ subbranches, I use this naming convention: `nameOfFeature`

Where `nameOfFeature` may be `footerSection`, `portfolioUpdate`, `coloringHeader`, etc.

After the work on the __development__ subbranches is done, I do merge those changes back into __development__. After checking for merge conflicts, or any issues, I do merge __development__ into __master__.

![git-branching](https://github.com/RicardoEscobar/portfolio/blob/development/img/git-branching.png?raw=true)
