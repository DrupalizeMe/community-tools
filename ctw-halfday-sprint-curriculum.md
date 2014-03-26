# The Curriculum

The curriculum itself is presented below, in various states of completion. Here are quick links to each section:

- Introduction and Community Sites
- Issue Queues and Dreditor
- Internet Relay Chat (IRC)
- Local Development Environment

## Community and Communication tools

Before we get into website building tools, one of the biggest barriers for many people is being unaware of, or overwhelmed by, the way the our community talks to each other and get work done. Connecting with people is where we start.

### Introduction and Community Sites

The first section of the slides introduces the workshop, and gives a quick tour of the Drupal community websites, and then we finish up with getting everyone who doesn't have a Drupal.org account to make one. The websites we look at are:

- [Drupal.org][1]
- [groups.drupal.org][2]
- [api.drupal.org][3]
- [association.drupal.org][4]
- [DrupalLadder.org][5]

We introduce the Drupal Ladder site because, even though it is not an official Drupal property, we will be using lessons from the Ladder for portions of the workshop today, and it is just generally a great initiative.

### Issue Queues and Dreditor

In addition to a community tour and creating accounts, we'll also give a tour of the Drupal.org issue queue and how it works, because this is a main part of communication and getting stuff done, but many people don't know it's there or are afraid of using it. Explain what an issue queue is and why we use them. The hands-on section begins with a logging in and finding the Drupal core issue queue. We also show how you can find the issue for any project on D.o, and that there are also projects, and queues, for things like Documentation and Webmasters.

**Find the issue queue**

You should emphasize searching in the issue queue as a best practice.

  1. Log in to Drupal.org, if you aren't already

  2. Navigate to Download & Extend, then click on the Download Drupal button

  3. Once on the project page, point out the "Issues for Drupal core" block in the sidebar and explain the "All issues" link versus the search box.

  4. Click on Advanced Search

  5. Quickly skim over explaining the "people" search boxes. Focus on the confusing stuff: Status, Version, Component in particular. (Look at how the issues listed show some of this info, and are color-coded to match status)

  6. Point out the tag field, and look up "novice"

  7. There is another fast way to get to this queue. Go back to Dashboard, and discuss the Contributor Links block.

  8. Every project on Drupal.org has a queue. Go to a project of your choosing, e.g. Views, see the issue queue block, and go to the issue queue.

**Use the issue queue**

To introduce people to actually using the issue queue, have everyone do the very first part of the Drupal Ladder [Getting started in the issue queue lesson][6] ([free video][7]), Post a sample issue.

**Use Dreditor for easier patch reviews**

[Dreditor][8] is a browser user script that you can use to make patch reviews, and general work in the Drupal.org issue queue, more efficient. It's a little tricky because it isn't a Drupal module, but is instead installed in your browser, so we will walk through the installation process for at least one or two browsers. There is an [Installing and Using Dreditor video][9] which shows installation on Chrome and Firefox, and then walks through all of the features Dreditor provides. Once it is installed, find an issue in the issue queue with a patch attached (preferably in the Drupal Ladder sandbox so you don't mess up live issues) and show how to use the Review and Simplytest.me links it adds to patches. There are other handy tips for using Dreditor, but how far to go will depend on the amount of time available.

### IRC

_IMPORTANT: If you will have a large group of people all connecting to Freenode at the same time, from the same IP, you should let Freenode staff know this ahead of time so that they don't block access from too many connections._

We wrap up the communication hands-on by having everyone in the class hop on IRC using an IRC client. We'll have a little chatter on IRC and see how useful the channel bot can be. IRC is another major communication tool that many people are unaware of, or uncomfortable with, but it is such a great way to get to know other people and work collaboratively in real-time. There is a [video lesson on Using IRC][10]. After the slides that explain IRC, and the major pieces you need to work with it, have everyone download an IRC client, if they don't have one already. We use Pidgin (Adium on Mac) because it is a free, cross-platform client. Once everyone is connected to Freenode, have everyone log in to the #drupalladder channel. We use this channel because it is generally very quiet (so we don't disturb people) and it has Druplicon in it.

**Install Pidgin/Adium**

**Connect to Freenode and #drupalladder** 

**Chat on IRC**

For more info on using IRC, check these resources on Drupal.org:

  - [Setting up IRC][11]
  - [IRC channel list][12]

### Local Development Environment

There is a short presentation to explain what a local dev environment is and why to use one. We cover the pieces for the server (AMP), and the commonly used pre-packaged ones for the various operating systems. Then we hop over to talk about Git and why we use that. After the intro presentation, everyone will split into groups to begin installing and setting up their local dev. This is where mentors need to fill in and get people ready to sprint. To split the groups up, do a series of questions to find out:

  1. Who already has an AMP stack, Git, and Drupal 8 installed? These people are ready to go to the main mentoring room and begin sprinting now.

  2. Who already has an AMP stack and Git? These people need to get Drupal 8 installed.

  3. Who already has an AMP stack but NOT Git? These people need to get Git, and then Drupal 8, installed.

  4. Who does NOT have an AMP stack? These people need to get a local AMP stack, Git, and then Drupal 8, installed.
For groups 2-4, have people get up and move to the same table(s) so that they are physically grouped together in the room. This makes it much easier for mentors to help, and for people to pair up with a buddy next them who is at the same place as they are. For anyone having problems, buddy them up with someone from their group. If you have a very large group, you should probably also have people group together by operating system. As each group, or buddies within a group, finally get set up with the full environment, they can begin sprinting. It's a good idea for all instructors and mentors to at least be somewhat familiar with the AMP stacks on different operating systems. We have a number of free videos for the various operating systems out there, so you can at least see what people may encounter.

**AMP stacks**

- [MAMP for Mac][13]
- [WAMP for Windows][14]
- Ubuntu: [Installing on Ubuntu][15] and [Ubuntu Web Server Configuration][16]

**Git**

- [Install Git on Windows][17]
- [Installing and Configuring Git on Mac][18]

[1]: http://drupal.org
[2]: http://groups.drupal.org
[3]: http://api.drupal.org
[4]: http://association.drupal.org
[5]: http://drupalladder.org
[6]: http://drupalladder.org/lesson/1d498fa2-d3e4-5754-9160-757d219e8032
[7]: http://drupalize.me/videos/getting-started-issue-queue
[8]: https://dreditor.org/
[9]: http://drupalize.me/videos/installing-and-using-dreditor
[10]: http://drupalize.me/videos/using-irc-internet-relay-chat
[11]: http://drupal.org/irc/setting-up
[12]: http://drupal.org/irc
[13]: http://drupalize.me/videos/installing-mamp-web-server
[14]: http://drupalize.me/videos/installing-wampserver
[15]: http://drupalize.me/videos/installing-web-server-ubuntu
[16]: http://drupalize.me/videos/ubuntu-web-server-configuration
[17]: http://drupalize.me/videos/install-git
[18]: http://drupalize.me/videos/installing-and-configuring-git