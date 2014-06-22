---
layout: exercise
title: Command Line
description: Command line exercises
permalink: /exercises/command-line/
javascript:
  - /assets/js/hint.js
---

![Drag Folder](http://media.24ways.org/2013/coyier/drag-folder.gif)

# Listing Directories

Change to the desktop. List all the directories on the Desktop

{% highlight ruby %}
$ cd ~/Desktop
$ ls -d */
{% endhighlight %}

# More Listing

Change to the desktop. List all files and directories, 1 per line.

{% highlight ruby %}
$ cd ~/Desktop
$ ls
{% endhighlight %}

# Making Directories

Create a directory named demo.

{% highlight ruby %}
$ mkdir demo
{% endhighlight %}

# Making Deep Directories

Change to the desktop. Create the following directory structure using one command: demo/foo/bar/praxis

{% highlight ruby %}
$ cd ~/Desktop
$ mkdir -p demo/foo/bar/praxis

{% endhighlight %}

# Creating Files

Change to the demo folder. Create a file named hello.txt in the demo directory.

 {% highlight ruby %}
$ cd ~/Desktop/demo
$ touch hello.txt
{% endhighlight %}