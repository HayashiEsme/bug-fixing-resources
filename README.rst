#TODO: I'm going to try to make sure that this gets shown without getting rendered by gitbooks


# Syzkaller Bug Fixing Resources - Repo README

Welcome to the repo hosting the bug fixing resources' documentation and discussion about improving it

This repo is designed to address the Linux Community's long-standing need to get syzkaller bugs fixed (literature 1: the tim bird presentation, literature 2: greg kh)
Longstanding coverage about fixing these bugs have been reported (LKML). Many passionate developers have tried but abandoned the project hitting a stumbling block,
funding towards fixing these bugs exist in the form of a kernel mentorship program (link here) exists -- but yet again all share a common downfall (? bad wording): 
there exist many valid approaches in which one could fix bugs, get started learning but cannot find a centralized technical resource as well as a developer
community for which new developers can begin to help themselves and overcome stumbling blocks. This repo is designed to solve the issues of 
information asymmetry surrounding fixing these syzbot bugs, as well as to help new developers learn their way around the kernel and its 
development culture

The documentation on the repo works more like an anthology -- oftentimes, many of these guides have long existed in an uncurated fashion. The sum of these guides build 
both on the existing efforts of others as well as to strengthen their impact by combining them.

(TODO: Refine design statements/outcomes)

The documentation can be found here: #TODO: Link here 

The Chapters thus far are:

## Building the Repo Locally

#TODO: I'm not sure actually! 


In your forked copy of the repo, run 
`
sudo npm install gitbook-cli -g
gitbook serve
`

NOTE: Currently there's a package that gitbooks is dependent on that breaks, so for now you need to run these commands immediately after installing gitbooks-cli:
`
cd /usr/lib/node_modules/gitbook-cli/node_modules/npm/node_modules
sudo npm install graceful-fs@4.2.0 --save
`

More detailed instructions found here: https://github.com/GitbookIO/gitbook/blob/master/docs/setup.md 


## Contributing 
We absolutely welcome pull requests, subject to reviews and its benefiting the project. Please have a look at 
issues (TODO: Link here) for conversations 

If you are interested in helping, but not sure where to start, the kernel debugging discord #TODO: add link is a 
great place to get ideas. There are many like-minded hobbists, nerds and developers having discussions on where 
documentation can help improve the number of bugs being fixed - in this repo and beyond - so feel free to introduce
yourself there to get started

As with any collaborative environment, we have a code of conduct that we should adhere to. As this project relates 
itself to the Linux kernel, we expect you to adhere to its code of conduct (https://www.kernel.org/code-of-conduct.html)
as well as to remember to have an open mind when communicating with others. You have a role in creating a welcoming 
community for others to grow and learn -- never underestimate the impact you can have on others. 