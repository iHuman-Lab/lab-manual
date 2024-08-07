# Overview

This repository contains the lab manual (and associated source code) for the `I`ntelligent `Hu`man and `Ma`chine `N`exus Lab (iHuman Lab) at Oklahoma State University. The lab manual describes the rights and responsibilities of all iHuman Lab members, and it introduces our general research approach and lab policies.

All new lab members are required to read (and modify!) this repository prior to joining the lab. New lab members are also required to complete a list of basic tasks (and signify that they have done so via a checklist at the end of the manual). The tasks are intended to ensure that every lab member is on the same page with respect to expectations and that every lab member has acquired a minimum viable set of skills needed to do research in the lab.


# Why are we sharing this repository with the public?

Our lab manual is, in one sense, intended to provide information that is specific to the iHuman Lab. So it's possible it'll be useful only to iHuman Lab lab members. However, we hope that others might find some aspects of the manual useful. Or maybe you don't like something, and you want to use our manual as a counterexample! Whatever you'd like to do with the contents, we offer this repository freely and in the spirit of openness and collaboration. By the same token, we make no claims as to the accuracy of the documentation or code herein, so we invite you to proceed at your own risk.

# Contributing

The way we develop collaborative documents and code in the iHuman Lab is to have a central repository for each project (e.g. this page) that everyone on the project has read access to. This repository is public, so everyone with an Internet connection has access to the contents of this repository, and anyone can (in principle) submit a pull request to change the contents. In practice, however, any substantial (e.g. beyond simple typo and grammar corrections) changes will need to be discussed by iHuman Lab lab members in person (e.g. during our weekly lab meetings). (So: feel free to contribute whatever you'd like, but before taking the time to do so please recognize that if you are not affiliated with the iHuman Lab, or planning to become affiliated, then it's unlikely that we'd incorporate major changes into the manual without having discussed it with you first.)

In order to modify the central code repository, you need to fork this repository, add your content to your fork, and then submit a pull request to incorporate your changes (from your fork) into the central repository. This allows us to maintain a stable working version in the central repository that everyone can access and rely on, while also allowing individual contributors to maintain (unstable) working versions. If these terms (forking, pulling, pushing, etc.) are unfamiliar or confusing, you should read through these Git Tutorials before proceeding.

To set up your fork:
1. Press the "fork" button in the upper right corner of the repository's website (link above).
2. Clone your fork to your local machine (`git clone https://github.com/<GitHub Username>/lab-manual.git`).
3. Set the central repository as an upstream remote: `git remote add upstream https://github.com/ihuman-lab/lab-manual.git`.
4. Each time you want to make changes to your local copy, sync it with the central repository by running `git pull upstream master`.
5. When you're done making changes, type `git commit -a -m "<MESSAGE DESCRIBING WHAT YOU CHANGED>` and then `git push`.
6. Repeat steps 4 and 5 until you have something to share with the world.  Note: you can push broken code to your local fork without damaging anything in the central repository, so we encourage frequent committing and pushing (even of broken code) to your local fork.  This will ensure that (a) you always have a recent online backup of your work and (b) there is a clear record of what you did and the path you took to accomplish it.
7. When you're ready to share your code with the world, go back to your fork's web page (`https://github.com/<GitHub Username>/lab-manual`), navigate to the "pull requests" tab (upper left), and press the "New pull request" button in the upper right.  Describe what you did and submit your pull request by filling out the prompts.  Then someone from the CDL will review the changes and merge them in, and everyone will have access to your changes.