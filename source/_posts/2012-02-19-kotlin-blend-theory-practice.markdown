---
layout: post
title: "Kotlin: A Nice Blend of Theory and Practice?"
date: 2012-02-19 18:06
comments: true
categories: kotlin java programming_languages
---
Why We're Interested in a New Language
--------------------------------------
In college we were introduced to SML and OCaml. We became enamored with
functional programming and strong static type systems. "Bugs are found for you!" is an expression one frequently
hears from the *new functional convert*. After school, we began programming large and complex systems with other developers.
The amazing functional languages we loved suddenly seemed lacking: e.g. OCaml isn't widely used, suffers from poor library support,
and lacks good supporting tools.

We ended up programming a lot of Java. We've found that there's a lot to like:
strong community support, great libraries ([Netty](http://netty.io/), [Guava](http://code.google.com/p/guava-libraries/), 
[cglib](http://cglib.sourceforge.net/), [Joda](http://joda-time.sourceforge.net/)), excellent tools (build, test,
continuous integration, code coverage) and the JVM is an amazing piece of software. This ecosystem should not be understated:
the gestalt is enormous gains in productivity and allows developers to ship high quality code. However, we are continually
left unsatisfied with the Java language -- algebraic data types? Nope.

Clearly our frustration isn't new. These points are hitting on well tread territory. Others have appreciated the high quality that
the JVM ecosystem provides, but were frustrated by Java -- these people created new languages on the JVM. Clojure and Scala are two
which initially excited us. Clojure has some nice features (lisps can be fun), but we cannot get behind a dynamic type system.
Scala has many awesome ideas, but too many. So much of our lives are spent making decisions about the interesting
problems we program on, we don't want to be spending time deciding what subset of a language to use. The language should make it clear.

Enter Kotlin
-------------
[Kotlin](http://confluence.jetbrains.net/display/Kotlin/Welcome) is a new (beta) JVM-based language from Jetbrains.
We were very excited when we read about Kotlin. Kotlin is an object oriented language
incorporating functional paradigms. Kotlin appears to have an eye on the kind of theory we like: higher-order functions, algebraic data types,
function literals, type aliases, and [more](http://blog.jetbrains.com/kotlin/2012/01/the-road-ahead/).
 Kotlin also has an eye towards pragmatism: there are numerous features which are backed up by real world usage patterns. The inclusion
of many of the features show that the developers have experience writing software e.g. *first-class delegation* (see [Delegation](http://confluence.jetbrains.net/display/Kotlin/Classes+and+Inheritance)),
*classes do not allow inheritance by default* (see [Inheritance](http://confluence.jetbrains.net/display/Kotlin/Classes+and+Inheritance)).

The designers of Kotlin have aesthetics which appear to be in line with our own: the exciting thing about programming is
the ability to make magic a reality. Computer Science gives us theory that allows us to talk about magic,
we need programming tools which help us make that magic. Kotlin's proposed language features, the choice to run on the JVM and its
blending of programming language theory with a motivation to get things done make us super excited to see where this project goes.