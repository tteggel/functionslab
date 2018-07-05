# Fn Functions Lab

In this lab you will also explore serverless computing using functions with the
Docker-based open source Fn project.

This document is meant to be an overview of the entire lab.  Throughout, you may
be directed to other labs, to run specific sections.  It is important that when
you finish each major section, you return to *this* document for the next
section.

As you make your way through the tutorials, look out for this icon.
![](images/userinput.png) Whenever you see it, it's time for you to
perform an action.

## Section 1 - Setting up a Docker Environment

* Log in to your lab machine. You will have been given a printout with your login details. You will need an ssh client to log in. If you are on Windows we reccommend [Putty]() or the [SSH Chrome Extension]().

## Section 2 - Lab Setup

We have already installed Docker and the Fn servers for you. If, after this workshop, you want to install this yourself on another machine the [instructions are here]().

### Your First Function

Now that the Fn server and CLI are installed we can dig into the creation and
running of functions.  In this tutorial you'll create, run locally, and deploy
a Node.js function.  If you aren't a JavaScript programmer don't panic! All the code is
provided and is pretty easy to understand.  The focus of this tutorial is on
becoming familiar with the basics of Fn, not programming.

Node.js is just one of the many language runtimes we support, and you can even use a 
docker image for ultimate flexibility.

So let's [create and deploy your first function](http://fnproject.io/tutorials/node/intro/).

### Fn Flow
Fn Flow provides a way to orchestrate functions to build sophisticated applications, initially using Java, and soon with other programming languages. Although the orchestration is currently written in Java, one of the coolest features of Fn is that while it's easy to write functions in various programming languages, you can also deploy Docker images as functions. This opens up entire world's of opportunity as you can package existing code, utilities, or use a programming language not yet supported by Fn.

Let's follow the [Flow 102](http://fnproject.io/tutorials/Flow102/) tutorial to get a feel for how this orchestration system works. Your environment already has the Flow server running so we can skip over the Flow 101 tutorial for now.

### Troubleshooting

If you've been following the instructions in the tutorials carefully you
shouldn't have run into any unexpected failures--hopefully!!  But in real life
when you're writing code things go wrong--builds fail, exceptions are thrown,
etc.  Fortunately the [Troubleshooting](http://fnproject.io/tutorials/Troubleshooting)
tutorial introduces techniques you can use to track down the source of a
failure.

### Function Applications

In some of the tutorials you've tried so far we've breezed over the concept
of an 'application'. In Fn, functions must belong to an application. They
function as a namespace, a place to set configuration common across functions,
and can be used as a deployment unit.  The
[Applications](http://fnproject.io/tutorials/Apps) tutorial shows how you can
use an application to organize and deploy functions.

## More Fn Tutorials!

If you've completed these tutorial and want to try
more you're in luck.  There's an ever expanding
collection of Fn tutorials you can try on your own time.

Check out these [Fn Tutorials](http://fnproject.io/tutorials) and just
skip the ones you've already completed.
