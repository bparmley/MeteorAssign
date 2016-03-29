#Meteor Assignment
## Build Instructions
Get Meteor at [https://www.meteor.com/](https://www.meteor.com/)

In your project root, in the command line type
```
meteor npm install
meteor
```

You can populate your list in the app or open a second command line in your project root and type 

```
meteor mongo
```
And then in the mongo database control tool which launches type
```
db.tasks.insert({ text: "Hello world!", createdAt: new Date() });
```

Open a browser window at localhost:3030

##What I learned
I learned that Meteor potentially can make app building simpler providing plenty of packages for app development.

##What I found difficult
As a developer on a Windows 10 machine I found that the program was slow and clunky. I had to hack my way to get it to work, but once it was working it worked well. I just wish it would be better optimized for windows.

##What are advantages to branching in Git?
It baffles me that this even needs asking. Not only can you sandbox your development and testing environments/code base from your production but you are able to branch specific aspects or bits of code. This allows for a non-linear development system that may be more benneficial as many pieces may progress faster than others. It also allows for permissions to be set on a branch by branch basis to ensure that code can be reviewed before merging.

##Gitflow
This is a great workflow. If you want to make a feature or a hotfix you specify the git flow feature/hotfix start and finish with the feature name or hotfix number at the beginning and end of your work and it will merge the hotfix or the feature into your master and develop branches and cleans up the extra branch behing you to keep a clean set of branches.

##Forking Workflow
This is a great workflow for open-source and collaborative programming. The premise is that you first fork a repo, make a branch, test things locally, and once they have something of worth, they push to their own repository and make a pull request to submit their suggested changes. While the original developer may not want your changes, someone else may want it or think they can improve on your code so they can fork your repo and start the process all over again. This has the potential to provide many differing versions of the code out there if the original developer isn't actively reviewing and maintaining his code but if that is the case, chances are you don't want it anyway...