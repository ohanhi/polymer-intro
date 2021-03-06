Polymer is not an experiment anymore
=========================================

_A quick look at what's going on in the world of [Polymer](http://www.polymer-project.org/), based on [this article and the referred talk](http://updates.html5rocks.com/2015/01/polymer-state-of-the-union)._

Ossi Hanhinen, 23 Jan 2015


> Polymer helps developers build awesome applications faster, easier, better.


# Library, not a framework

- Builds on (upcoming) standards
- "The framework is the DOM"
- Very little "special syntax"
  - Only the declarative syntax is Polymer-specific

# tl; dr

- 5x faster on Chrome and 8x faster on Safari
- From 123kB down to 15kB (6kB gzipped)
- Two-way data binding is now opt-in
- 0.8 release due in Q1 2015
- 1.0 release due in Q2


# How did they do that?

- Refactored into **layers**
- Core features are **lean**
- Advanced functionality is **opt-in**
- Simplified data binding
  - Two-way is now opt-in
  - Explicit property types
- Polyfills moved to [webcomponents.org](http://webcomponents.org)
  - Polymer now only provides a **shim**
- **Some** breaking changes
- No need for rewrites

[Perf demo](http://youtu.be/0LT6W5QVCJI?t=13m2s)


# Who's using Polymer?

- QuickOffice (removed **10k LOC**)
- SalesForce (waaat!)
- News Corp
- YouTube - related videos
- Google Translate
- Google Play Music

