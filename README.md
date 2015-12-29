# CLOJURE EXCHANGE 2015 - SkillsMatter, London


__Heard at Clojure eXchange:__
* _"Lisp is the best language"_ -> I think the context was: easy to write DSL (domain-specific languages)
* _"Cider rocks"_ -> well of course cause CIDER = Clojure Interactive Development Environment that Rocks!
* _"Emacs is the one true editor"_ -> choose your ~~religion~~ editor
* _"Prismatic schema ftw"_ -> heard in several talks
* _"Pure function is the solution"_ -> avoid state


__Videos recommended by speakers:__
* ["Thinking in Data"](http://www.infoq.com/presentations/Thinking-in-Data) by Stuart Sierra at Clojure/West
* ["Simplicity matters"](http://www.youtube.com/watch?v=rI8tNMsozo0) by Rich Hickey at Rails Conf 2012 (keynote)
* ["Simple made easy"](http://www.infoq.com/presentations/Simple-Made-Easy) by Rich Hickey at Strange Loop

__Other resources:__
[Clean up a messy ns with cider + Clj-refactor](https://benedekfazekas.github.io/2015/12/06/clean-up-namespace-with-cider-cljrefactor/) by Benedek Fazekas (@bfazek)


## Day 1 - 03/12/2015

#### Chris Ford, Dueling keyboards [Keynote] - [Video](https://skillsmatter.com/skillscasts/7240-keynote-dueling-keyboards), [Slides](https://skillsmatter.com/skillscasts/7240-keynote-dueling-keyboards)

Libraries references: [Overtone](https://overtone.github.io/)

My take-away:

The Baganda music has been research to illustrate the difference between the structure of its music and the rest of the world and more particularly between African music and Western European music. [Read more](https://en.wikipedia.org/wiki/Baganda_music)


#### J. Pablo Fernández, What is a Macro? [Talk] - [Video](https://skillsmatter.com/skillscasts/7245-what-is-a-macro), Slides

Other resource: [Blogpost](https://carouselapps.com/2015/08/13/macros-the-lisp-advantage/)


My take-away: 

1) macros are to be used carefully

"It's not about how many macros you write,
but how many functions you didn't write by writing a macro."

2) Lisps and AST

For Lisps the abstract syntax tree (AST) is accessible from a programme which makes it easy to extend the languages using macros. [Read more](http://www.braveclojure.com/read-and-eval/)


#### Bozhidar Batsov, CIDER: The journey so far and the road ahead [Talk] - [Video](https://skillsmatter.com/skillscasts/7225-cider-the-journey-so-far-and-the-road-ahead), [Slides](https://speakerdeck.com/bbatsov/cider-the-story-so-far-and-the-road-ahead)

Libraries references: [CIDER](https://github.com/clojure-emacs/cider)

My take-away:

Must try: [cider debugger](http://endlessparentheses.com/cider-debug-a-visual-interactive-debugger-for-clojure.html),
[clj-refactor](https://github.com/clojure-emacs/clj-refactor.el), [squiggly-clojure](https://github.com/clojure-emacs/squiggly-clojure) and other goodies from cider 0.10!


#### Kris Jenkins, ClojureScript: Architecting for Scale [Talk] - [Video](https://skillsmatter.com/skillscasts/7227-clojurescript-architecting-for-scale), [Slides](https://github.com/krisajenkins/ClojureScriptForScale/blob/master/ClojureScriptForScale.org)

Libraries references:

[Demo](https://github.com/krisajenkins/petrol/tree/master/examples) to handle two counters and Spotify events on the same UI
using [Petrol](https://github.com/krisajenkins/petrol) framework.

My take-away:

Must try Petrol framework!

Also this framework is inspired from the Elm architecture. See Kris' Elm architecture tutorial [here](https://github.com/evancz/elm-architecture-tutorial).

Must try and understand Elm =)


#### Ernestas Lisauskas - Garden: CSS in Clojure and ClojureScript [Lightning Talk] - [Video](https://skillsmatter.com/skillscasts/7250-lightning-talks-day-1), Slides

Libraries references: [Garden](https://github.com/noprompt/garden)

My take-away: Like [Hiccup](https://github.com/weavejester/hiccup) but for CSS


#### David Humphreys - Testing times in Clojurescript [Lightning Talk] - [Video](https://skillsmatter.com/skillscasts/7250-lightning-talks-day-1), [Slides](https://github.com/davidjameshumphreys/testing-times-in-clojurescript)

Libraries references:

[Doo](https://github.com/bensu/doo): easy to configure,

[DevCards](https://github.com/bhauman/devcards): provides an interactive visual REPL,

[Speclj](https://github.com/slagyr/speclj): TDD/BDD framework for Clojure


My take-away: I haven't worked with Cljs enough but those looks like good resources to try!


#### Dave Snowdon - Seeing With Clojure [Lightning Talk] - [Video](https://skillsmatter.com/skillscasts/7250-lightning-talks-day-1), [Slides](https://github.com/Davesnowdon/cljex-2015-opencv)

Libraries references: (= [Vision](https://github.com/nakkaya/vision) (+ [OpenCV](http://opencv.org/) Clojure) )

Other resources:

* Tutorial: [Intro to OpenCV with Clojure](http://docs.opencv.org/3.0-last-rst/doc/tutorials/introduction/clojure_dev_intro/clojure_dev_intro.html)

* [OpenCV in Python](http://www.pyimagesearch.com/)


My take-away: It's cool, but there are much more resources for OpenCV with Python


#### Mark Godfrey, Understanding our code with tests, schemas and types [Talk] - [Video](https://skillsmatter.com/skillscasts/7241-understanding-our-code-with-tests-schemas-and-types), Slides

Libraries references:
[Prismatic schema](https://github.com/Prismatic/schema)
[core.typed](https://github.com/clojure/core.typed/)


My take-away:

To make your code more easily understandable by your colleagues:

* Don't forget to write docstrings,
* Try and use maps as function arguments,
* Write more tests!
* Use Prismatic schemas,
* Use types (maybe)


#### Julian Birch, Beyond Reduce [Talk] - [Video](https://skillsmatter.com/skillscasts/7242-beyond-reduce), [Slides](https://github.com/JulianBirch/beyond-reduce-presentation)

Libraries references: []()

Misc:


#### Thomas Van Der Veen and Malcom Sparks, REST full web service in Clojure, two different approaches [Talk] - [Video](https://skillsmatter.com/skillscasts/7224-rest-full-web-service-in-clojure-two-different-approaches), Slides

Libraries referenced: [Yada](https://github.com/juxt/yada)

Misc:


#### James Reeves, Duct Covered [Talk] - [Video](https://skillsmatter.com/skillscasts/7229-duct-covered), Slides

Libraries referenced: []()

Misc:


#### Michiel Trimpe, Conversational Computing: How Okasaki made McCarthy right yet again [Talk] - [Video](https://skillsmatter.com/skillscasts/7277-conversational-computing-how-okasaki-made-mccarthy-right-yet-again), Slides

Libraries referenced: []()

Misc:


## Day 2 - 04/12/2015

#### Bridget Hillyer, A tour of the Clojure ecosystem [Keynote] - [Video](https://skillsmatter.com/skillscasts/7233-keynote-a-tour-of-the-open-source-clojure-ecosystem), [Slides]()

Libraries referenced: []()

Misc:


#### Nicola Mometto, Immutable code analysis with tools.analyzer [Talk] - [Video](https://skillsmatter.com/skillscasts/7239-immutable-code-analysis-with-tools-analyzer), [Slides](https://github.com/clojure/tools.analyzer.jvm/blob/master/docs/ClojureX_slides.pdf)

Libraries referenced: []()

Misc:


#### Martin Trojer, Best of both worlds, combining Cassandra and Elasticsearch to store and analyse time-series data [Talk] - [Video](https://skillsmatter.com/skillscasts/7234-best-of-both-worlds-combining-cassandra-and-elasticsearch-to-store-and-analyse-time-series-data), [Slides]()

Libraries referenced: []()

Misc:


#### Henry Garner, Expressive parallel analytics with Clojure [Talk] - [Video](https://skillsmatter.com/skillscasts/7243-expressive-parallel-analytics-with-clojure), [Slides](http://clojuredatascience.com/posts/2015-12-05-expressive-parallel-analytics-with-clojure.html)

Libraries referenced + resources:

* [reducers](http://clojure.org/reducers)
* [transducers](http://clojure.org/transducers)
* [xforms](https://github.com/cgrand/xforms)
* [tesser](https://github.com/aphyr/tesser)
* [core.async](https://github.com/clojure/core.async)
* [Slides in org mode](https://github.com/henrygarner/cljx-december-2015)


#### Glenn Mailer, Are you afraid of dependencies? [Lightning Talk] - [Video](https://skillsmatter.com/skillscasts/7251-lightning-talks-day-2), [Slides](https://glenjamin.github.io/afraid-of-dependencies/assets/player/KeynoteDHTMLPlayer.html#0)

Libraries referenced: []()

Misc:


#### Alejandro Gómez, Cats & Monads [Lightning Talk] - [Video](https://skillsmatter.com/skillscasts/7251-lightning-talks-day-2), [Slides](https://gist.github.com/dialelo/8964a5586d9dd54212e3)

Library referenced: [cats](https://github.com/funcool/cats)


#### Frankie Sardo, Revaluating Pedestal [Lightning Talk] - [Video](https://skillsmatter.com/skillscasts/7251-lightning-talks-day-2), [Slides]()

Libraries referenced: []()

Misc:


#### Hans Hübner, Datomic in Practice - [Video](https://skillsmatter.com/skillscasts/7228-datomic-in-practice), [Slides]()

Libraries referenced: []()

Misc:


#### Patrick Monteith, Building modular systems with asystant [Talk] - [Video](https://skillsmatter.com/skillscasts/7257-building-modular-systems-with-asystant), [Slides]()

Libraries referenced: []()

Misc:


#### Andrei Ursan, Actor systems in Clojure: What are your options? [Talk] - [Video](https://skillsmatter.com/skillscasts/7238-actor-systems-in-clojure-what-are-your-options), [Slides]()

Libraries referenced: []()

Misc:


#### Yann Esposito and Guillaume Buisson [Talk] - [Video](https://skillsmatter.com/skillscasts/7226-full-stack-real-time-social-media-analytics-with-clojure), [Slides]()

Libraries referenced: []()

Misc:


#### Ali King, ClojureBridge - Building a more diverse Clojure community [Talk] - [Video](https://skillsmatter.com/skillscasts/7235-clojurebridge-building-a-more-diverse-clojure-community), [Slides]()

Post referenced: [What is hacker culture?](https://mjg59.dreamwidth.org/38746.html)


#### William Hamilton, Event-based architecture with Kafka and Clojure [Talk] - [Video](https://skillsmatter.com/skillscasts/7300-event-based-architecture-with-kafka-and-clojure), [Slides]()

Libraries referenced: []()



-------------

<a rel="license" href="http://creativecommons.org/licenses/by-nc/4.0/"><img alt="Creative Commons License" style="border-width:0" src="https://i.creativecommons.org/l/by-nc/4.0/88x31.png" /></a><br />This work is licensed under a <a rel="license" href="http://creativecommons.org/licenses/by-nc/4.0/">Creative Commons Attribution-NonCommercial 4.0 International License</a>.
