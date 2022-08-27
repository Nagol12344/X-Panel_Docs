---
title: Install page 1
description: Learning how to install the panel, one step at a time.
layout: ../../layouts/MainLayout.astro
---

### Installing X-panel

So, you want to install X-panel? Well you came to the right place!

In this step we will

- **Download the source code**
- **Install the modules**
- **Install mongodb**

Lets get started!

#### <span style="color:red">WARNING</span>
We dont install [Pterodactyl](https://pterodactyl.io/), [Node.js](https://nodejs.org/en/), [Git](https://git-scm.com/) in this, but it is required.
This is also for linux, i hope this works on all distro's but its only tested on ubuntu, so your milage may vary.

And with that out of the way, lets start!

#### Download the source code

To download the source code all that is needed is this command:

```
git clone https://github.com/ForceHosting/X-Panel-free.git
```

Then wait, it will download the source code.

When its done, go to the next step!

#### Install the modules

Now your going to cd into the folder where the source code is, this command should do that:

```
cd X-Panel-free
```

Then your going to need to go into both folders, the server folder, and the frontend folder.

We will start with the server folder. You can use the same cd system that we used to get in here:

```
cd server
```

After that you need to install everything, this can be done with npm.
```
npm install -y
```

Then you repeat the steps for the frontend folder, just cd into it and then use the install commmand.

#### Install mongodb

As this changes from os to os, you can use the mongodb install place found [HERE](https://www.mongodb.com/try/download/community), or use a docker image, make sure its accessible, becuause its required for the panel.