Forked from https://github.com/brunohaid/houseofcards

- allow card content to scroll
- put more sample content in to see how it behaves with scroll
- demo: [http://ezl.github.io/houseofcards/](http://ezl.github.io/houseofcards/)

To do:

- catch scroll events on the .tagline and send them to the .card behind it -- right now, this screws up if your mouse is over the tagline because it just wants to scroll the card instead of hitting the overflow-y content on the card
- at medium sized viewports, if you scroll down from the cover card for 1 or more cards then scroll back up, the bottom cards are getting affixed to the top of the page without the initial padding so they're visible behind the title card.  doesn't happen at mobile or very wide viewports (just tried and was able to replicate at window.innerWidth==617px)

# House of Cards

Simple landing page framework which doesn't scream "Look, i'm a bootstrap landing page like every other"

## Why?

The majority of landing pages looks pretty similar, and as the cost of whipping one up has come down to less than an hour, your project runs the risk of drowning in a sea of similar ones. For the user it becomes hard to discern if you put the sweat of months into your project or a half assed afternoon.

From a UX perspective, House of Cards tries to do everything to be perceived as different.

## Why the stack metaphor?

Beside of the slight tinder feel, there's a more important reason: If you ever worked at McKinsey et al, you'll know the ritual of nearly every meeting concluding with someone trying to sum it up on, at least an imaginary, PowerPoint deck. While that's easy to mock, it's also a great exercise:

**What is it you really want to communicate? In n uniform arguments ( = slides)?**

Tis forces you to really think about and condense your arguments, as opposed to segments with arbitrary length in the typical landing page.

## Technical details?

House of Cards doesn't have any external dependencies, uses global event event handlers and should be safe to use with any other libraries, frameworks or build tools.

## Status

It's not ready for production yet, as we're working on a few touchdevice quirks, but should be in early Feb 2015.
