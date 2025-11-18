# Licensing

While it's very understandable that you might want to get right into downloading data
and getting into some cleaning code, it's almost always a good idea to take a step
back, and think about your data, its sources, and the availability of those sources.

## Finding available data

The first thing you'll want to do is get a list of all the data sources available
that are relevant to your project. This can be a lengthy task in its own right, but
you'll be very glad you did it thouroughly up front, instead of having to go back
and redo a lot of work when a new data source turns up.

In the case of Classical Tibetan, there are several very well known resources for
digitized data. These include:

* rKTs
* BDRC
* Asian Legacy Library

Each has either a repository on GitHub or a downloadable archive of their data
available. But before we proceed with grabbing these data sources, there are a couple
of tasks to do first, for each source:

- Understand what data is available
  - How are you going to identify each document? Are there established conventions?
  - What formats are the documents available in?
  - Are there duplicates or variants of some documents?
- Understand what license the data comes with
  - There may be different licenses for different documents
  - A single document may be under multiple licenses
  - What licenses is your project ok with?
  - For licenses you accept, do these licenses come with requirements, like providing attribution or license forwarding?

This list isn't complete, and it definitely isn't static. Each project is going
to have to make decisions about a lot of things that aren't strictly core to the
project's goal. But being aware of the places where decisions need to be made can
prevent a lot of headaches down the road. Imagine you are about to publish a
paper with some really amazing results - and you find out only then that the data
you used to train on was not licensed for re-use. Avoiding these kinds of
situations early in the process not only keeps your team aware of what limitations
might be present, but also ensures your work is actually useful when it's done.
