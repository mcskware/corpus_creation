# Introduction

In almost all machine learning tasks, having a high quality corpus
to train on is essential.

This book aims to provide one possible method of natural language
corpus creation. There's not really a "right way" to do this that
works for all langauges or all corpora. Feel free to adjust, fix,
or eliminate anything that doesn't quite work for your domain and
problem space.

The general idea has several steps:

* Understand what data is available
  * Including its licensing
* Understand what format the data is in
  * Each provider will often have their own conventions
* Understand what format you want the data in
  * Your problem space will determine how you need to change the raw data

I'll go through each of these steps in sequence throughout this
book, and hopefully it'll give you a good framework for building
your own corpus creation system.

## Classical Tibetan

In this book, I'm going to use the Classical Tibetan language as
the example corpus. There's a fair amount of data available here,
and it should serve as a good basis for your own work.

## Setting Expectations

Creating a good natural language corpus is a big task. It's not
something that you can just throw together, nor is it something
that ever really has an explicit end. As you work with your data,
you'll catch things that you hadn't before, revising your cleaning
scripts, adding more corpora as they become available, and creating
custom converters for your corpus for specific tasks.

This is a pretty complicated endeavor as well, so it's considered
best-practice to keep track of everything you do, and equally
important, why you're doing it that way. This is natural language,
so there are infinite ways you might want to work with the data.
Clearly documenting your decision process can inform others about
when they may need to change or augment your work, and the best
places to this.
