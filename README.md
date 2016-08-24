# Manual-to-BRT-manual

Describes how to contribute to the the-on-line-Bus-Rapid-Transit-Manual

### _Online collaborative version of the BRT Planning Guide_

Is a work in progress, that shall soon be hosted under ITDP's github account.

###### Newcomers to git

- [Git](https://en.wikipedia.org/wiki/Git_%28software%29) is a computer program [ideally] to be installed on a contributor's computer, where it shall manage a copy (clone) of the required content to produce the BRT Planning Guide (this repository) and submit proposals for changes. Git is originally a command line tool, but there are several graphic tools. It may require a two hour effort to install it and learn the basics of using it without assistance and 20 minutes with assistance. More about git in the [Pro Git book](https://git-scm.com/book/en/v2). Git is a useful tool to work alone and control versions of your own work, and (when colaborating) it does not depend of a server (like GitHub or GitLab) to centralize the work of many people. 

- [Github](github.com) is a website that centrally host repositories like this one, it is free for open-source projects. Contributors to the BRT Planning Guide are required to have a *github* account, with that only it is possible to submit changes proposals to the guide, although it is not practical for large ones.

_To simply navigate through foloders and files make sure you click on the file name (in light blue on the left side) and *NOT* in the gray message in the middle of the same container (that will lead you to the last changes on the file)_

###### Files structure in the repository for the online brt planning guide

*Generator* directory holds code files that will process the content in the *Guide* directory, which contains the source (text files and assets as images referenced in the text files) for the BRT Planning Guide, the *dot files* have configuration information (describing where and how processing the repository must take place and about git itself).

###### The content in the guide 

At the moment, the entry point of processing is in the file [`guide/the-guide.src`](guide/the-guide.src), where other files are pointed with the `\include{point/to/other/file.src}` command. A user manual on how to contribute and of the supported syntax is being developed in the chapter called [Manual for Collaboration](https://brt.robrt.io/branch/development/guide/manual-to-collaboration/).

###### Motivation 

If you are an editor dealing with dozens of contributors and revisions, each one placing revision marks over different named files,
you sure understand why colaborators should undergo learning how to use this platform. While wikipages could be an alternative, at this point such tools do not allow parallel working flow distributions.

###### Split content from display.

#######


First step: **Try GitHub**

- Create a GitHub account
	- will require an email account...
	- ..where you will receive an email to confirm that it is really yours
- Sign in to GitHub
- Try the hello world (branch-change-pullrequeste-merge)


Second step: **Fork the-on-line-brt-planning-guide project from ITDP's profile**

- make a change in your fork (edit-commit)
- submit it to the editor (pull-request)

Third step: Install Git and Git LFS



