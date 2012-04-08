---
layout: post
title: "Preparing for Code Academy"
description: ""
category: 
tags: []
---
{% include JB/setup %}


So I've been trying to get familiar with both Ruby and Ruby on Rails before class at [Code Academy](http://codeacademy.org/) starts, and I wanted to share some of the resources I've been using in case anyone else finds them helpful.

The installation of all the equipment necessary for Rails applications was a beastly task.

[Chapter 1](http://ruby.railstutorial.org/ruby-on-rails-tutorial-book?version=3.2#top) of Michael Hartl's Ruby on Rails Tutorial was where I started the installation process, by installing [Git](http://git-scm.com/) and [Ruby Version Manager (RVM)](http://beginrescueend.com/).  Then, I tried to install Ruby 1.9.3 through [RVM](http://beginrescueend.com/), but failed.  Googled the error and found out that if you have [Xcode](https://developer.apple.com/xcode/) on your machine* prior to installing Ruby 1.9.3 with [RVM](http://beginrescueend.com/), your computer may have a small [seizure](http://gifsoup.com/view/176062/computer-explodes-o.gif).  

That's when I found the lovely website: [Installing Ruby 1.9 and Rails 3 on Mac OS X](http://pragmaticstudio.com/blog/2010/9/23/install-rails-ruby-mac).  It's written in plain English and walks you through the entire installation process of [GCC](https://github.com/kennethreitz/osx-gcc-installer/downloads), [Command Line Tools for Xcode](https://developer.apple.com/downloads/) (if you need it), [Git](http://git-scm.com/), [RVM](http://beginrescueend.com/), Ruby 1.9.3, [SQLite3](http://www.sqlite.org/), and [Rails](http://rubyonrails.org/).  

If I were to do it over again, I would start by following all the steps on [Installing Ruby 1.9 and Rails 3 on Mac OS X](http://pragmaticstudio.com/blog/2010/9/23/install-rails-ruby-mac).  Then, I would read [Chapter 1](http://ruby.railstutorial.org/ruby-on-rails-tutorial-book?version=3.2#top) of the Ruby on Rails Tutorial to check for other things that I still need to do - like creating [GitHub](http://github.com)** and [Heroku](http://www.heroku.com/) accounts.  

To get familiar with Ruby, I went through the [Chris Pines' Learn to Program Tutorial](http://pine.fm/LearnToProgram/).  It's a fun journey, and he gives really good examples.

For Rails, I've been going through the [Ruby on Rails Tutorial](http://ruby.railstutorial.org/).  You get to make a real web application with an attractive design, secure user registration, and sign-in/sign-out capabilities.  While teaching you to build your own web app, he also teaches about various Gems, Test-Driven Development (TDD), and the Model-View-Controller (MVC) paradigm.

I've also been pair programming with [Kori Roys](http://koriroys.com).  It's amazing how much faster you learn when you have someone to answer any question that pops into your head.  The other day we started a project where you build a client that interacts with [Twitter](http://twitter.com/) through Ruby.  I recommend going through the [tutorial](http://tutorials.jumpstartlab.com/projects/jstwitter.html) and referencing [GitHub](https://github.com/AaronVasquez/JSTwitter) if you get stuck. 

Alright, now it's back to the [Ruby on Rails Tutorial](http://ruby.railstutorial.org/) for me.  Can't wait to start [Code Academy](http://codeacademy.org/) tomorrow!

*Incidentally, there is no reason you *need* to have [Xcode](https://developer.apple.com/xcode/) on your machine.  [Xcode](https://developer.apple.com/xcode/) is an IDE, and the vast consensus I've heard among developers thus far is that text editors are the superior method for creating apps, simply because there are fewer limits with text editors.  However, after I got my Mac, I couldn't resist checking out the Developer section of the App Store, and downloading the "hottest" free developer tool.  Lesson learned.

**If you have problems installing Git and GitHub, [the GitHub set-up page](http://help.github.com/mac-set-up-git/) is extremely helpful.