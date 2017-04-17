---
layout: post
title: "The Drupal Way Part 8.3.x"
modified:
categories: blog
excerpt: Finding sanity and best practices in Drupal land
tags: 
image:
  feature: the-drupal-way.jpg
date: 2017-04-17T08:00:00-00:00
comments: true
share: true
---

Holey moley what happened?  I was just sitting here, minding my own business, spelunking through a Drupal 7 render array, and when I looked up a techtonic shift had taken place.  One minute "there was a module for that". You could tweak that module by digging in and twisting a hook to do what you need.  Then Drupal 8 dropped and it all got real.

Once we just had easy-to-remember hook names like:

````
hook_field_attach_prepare_translation_alter(&$entity, $context)
````

Now we're supposed to create endless yaml files and "just write a plugin".  A what?
 
I'm no Luddite.  I came to Drupal from the land of objects (and IDE's and integrated debuggers & profilers) and unlearned my 'objectivity', embracing Drupal like a slightly eccentric family member. You might say that for the past 11 or so years I've had an ongoing, rather intense, love-hate relationship with Drupal. I love what I've been able to accomplish.  From time to time I've had issues with various design decisions, but by and large if I stayed close to the current Drupal Way of doing things I've always been able to get done what I needed to with a minimum of muss and fuss. It might have been a bit quirky, but Drupal had a way about it.

There has always been [The Drupal Way](https://www.jeffgeerling.com/blogs/jeff-geerling/the-drupal-way).  Over time a person could discover The Way, stay close to it and leverage some incredible technology to create wonderful things.  If you skew toward [MBA-Speak](http://www.cipsum.com) you might call it a set of *Best Practices* for Drupal.  I shy away from that kind of hifalutin talk whenever possible. I just like to get things done and I like to repeatedly get predictable high quality results with minimal stress. Am I lazy? If going out of my way to automate and streamline and create things that work and are extensible so they can handle the unforseen so I can do other fun things makes a person lazy, then yes. Count me in. Until recently if you had the slightest inclination to do the least amount of work possible TDW was a wonderful thing and laziness was rewarded.

And then, Drupal 8. Chaos! Bedlahm! Pandemonium! Don't get me wrong, it's some damn fine code, but it's a huge shift. I think `The Way` is still out there -- evolving, but it's damn hard to find. I'm having trouble and I have a feeling I'm not alone.  In the past year I've been to a DrupalCon, a Drupal Camp and several user group meetings and I keep running into people with basically the same problem:  There ain't no way!

Peoples... We're going to find it!  The sooner we do, the sooner we can pop the footrest of our lazyboys back up and do what we do best. [The Lazy Drupalist](http://thelazydrupalist.com) will explore my attempts to keep sane and discover best practices for Drupal development while:

  1. Migrating several Drupal 6 sites to Drupal 8
  2. Managing feature requests for existing Drupal 7 sites
  3. Creating and deploying sites in D8

Is this even possible?  Hell if I know.  Check back in from time to time and see.


