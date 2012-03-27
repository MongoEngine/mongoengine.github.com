---
layout: page
title: "Roadmap"
tagline: "upcoming and new"
---
{% include JB/setup %}

Initially published on the [mongoengine-users](https://groups.google.com/d/topic/mongoengine-users/Or_LkpB5WYQ/discussion) usergroup.

### 0.7

- Performance - Dirty data tracking
- Allow inheritance default to off
- Chainable QuerySet slice
- Serialization / deserialization
- Raw method for pyMongo

See [github](https://github.com/hmarr/mongoengine/issues?milestone=4&state=open) for all the issues assigned to the 0.7 (not all will make it).

### 0.8

- Performance - Configurable lazy references
- Transparent pymongo connections - lazy ones at that :)
- Bug fixes
- Code quality

### 0.9

- Python 3 support
- Test refactor
- Polish and clean
- Website

### 1.0 - Party! :)

Anything missing or you would like in - let me know!

## MongoEngine framework support

MongoEngine is used with various different frameworks and there are numerous projects out there for integration in varying states of completeness.  I would like to bring framework support into the project - so that we can provide similar levels of functionality to whichever framework you are using.

At the weekend I did a quick review and found:

* Django has 6 projects on Github providing Forms, Views, Admin and debug toolbar support.
* Flask has 2 projects providing Generic Views, Forms and Debug toolbar support
* Pyramid has a project providing project scaffolding.
* Bottle has a project / example for integration

I will need help from the community with this and I will be reaching out to people who have already published code on github.  If you are interested let me know!

To help with this I have added a new organisation in Github: http://github.com/mongoengine - this will host the code going forward (don't worry any changes to the core will be pushed upstream to http://github.com/hmarr/mongoengine/) I'm hoping that all the new framework libraries will be hosted under this organisation so that they are easy to find and cross repository issues can be tracked.

I'm really excited about pushing towards getting MongoEngine to 1.0 and with your help we'll get there soon, I would also love some feedback - anything you think MongoEngine could do better / shouldn't be doing let me know!
