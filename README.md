*Please, if you are reading this, refrain from posting it on social sites until Monday, December 2nd.  I am editing, reviewing, and bringing up the whycoffeescript.com site.  In the meantime please feel free to add constructive contributions or feedback.*

*Sincere thanks,*

*__Charles__*



#Why CoffeeScript Will Make You a Better Programmer

I love CoffeeScript.  It has made programming fun again, like when I was a child.  It has improved my quality of life and made problem-solving more interesting, because I now solve problems in a better way.  How is this possible?


##CoffeeScript forces a JavaScript programmer to admit that they are wrong.

They could be solving problems in a better way.  Sit down and write a piece of code in JavaScript and in CoffeeScript.  CoffeeScript generates the most performant JavaScript code.  Does your JS code look exactly like what Coffee generated?  Why not?  Did you forget to cache the array length and Coffee remembered?  Did you forget a semicolon and CoffeeScript didn't?  Are you not following good formatting practices?  If there is a 'best practice', CoffeeScript does it automatically.  There are endless JS performance articles I have read over the years, but that shouldn't be a precursor to writing good code.  That is the point of using a higher-order language.


##CoffeeScript is JavaScript.

Debugging CoffeeScript is no different than debugging JavaScript -- CoffeeScript is just *syntax* for JavaScript.  Any trouble debugging CoffeeScript is due to a misunderstanding of  JavaScript.  If the function is too deeply nested or too complex to debug, it should be rewritten.  Named, modular, single-purpose functions are very easy to debug in any language.


##CoffeeScript is Functional Programming.

This is a huge change in thinking about how to solve problems -- every function returns a value.  Functional programming is lauded by academics and praised for its performance and reusability, yet many programmers never learn FP style [\[1\]](http://www.cse.chalmers.se/~rjmh/Papers/whyfp.html "Why Functional Programming Matters")[\[2\]](http://weblog.raganwald.com/2007/03/why-why-functional-programming-matters.html "Why Why Functional Programming Matters Matters").  When a function returns a value, it has a defined purpose.  If a function has multiple purposes, it therefore can be split into multiple methods.  Small, simple functions are easier for the compiler to optimize, and more likely to be reused by the programmer.


##CoffeeScript is a DSL.

CoffeeScript is English.  Why create a DSL or write out problems in pseudocode?  Because it's easier for most to express their thoughts in their native language [\[3\]](http://amix.dk/blog/post/19614 "Domain Specific Languages in CoffeeScript").  It removes the pieces of programming that only computers need (braces, etc.), enhancing focus on the real issue that needs to be solved.

Because CoffeeScript is in English, it is easier to talk about the problems I am solving.  Whether I am discussing with a fellow programmer, or summarizing my current work to describe my day to my girlfriend, I often speak the code verbatim.  Storytelling makes problems easier to solve [\[4\]](http://blog.bufferapp.com/science-of-storytelling-why-telling-a-story-is-the-most-powerful-way-to-activate-our-brains "What Storytelling Does to Our Brains").


##CoffeeScript debugs itself.

Many libs exist to help JavaScript be less "tricky".  CoffeeScript does not need linting -- CoffeeScript has the compile-time syntax checking that devs in other languages rave about.  It even has typing available with Contracts.coffee [\[5\]](http://disnetdev.com/contracts.coffee/ "Contracts.coffee").  If a programmer considers themselves good at JavaScript, why do they need a linter?  Perhaps it's time to admit that JavaScript's shortcomings are holding us back.


##CoffeeScript saves time.

A recent project is 8500 lines of CoffeeScript, compiling to 14000 in JavaScript.  No linting, little debugging, less keystrokes.  I raised my rates by 1/3 when I learned Coffee.  When I became good at it, I raised them by another third.  My clients are happy because I complete projects faster.  So are my friends, and my bank account.  *(Plus, better efficiency means less electricity wasted on long hours, and [I love sustainability](http://designersaccord.org).)*  Anecdotal, but many feel the same way:

"And I believe the vast majority of JS developers will see productivity gains by embracing CoffeeScript." [\[6\]](http://www.quora.com/CoffeeScript/What-are-disadvantages-of-using-CoffeeScript "What are disadvantages of using CoffeeScript?").

"...easier to read and a lot faster to produce." [\[7\]](http://www.ibm.com/developerworks/web/library/j-coffeescript/index.html "Functional JavaScript with CoffeeScript and Node")

"Lines of code are, and always have been, the enemy." [\[8\]](http://www.codinghorror.com/blog/2007/12/size-is-the-enemy.html "Size Is The Enemy")

"Succinctness is Power" [\[9\]](http://www.paulgraham.com/power.html "Succinctness is Power")


##CoffeeScript is ES.next.

List comprehensions, default values, destructuring assignments, rest/spread, classes, are all in ES6, and also in CoffeeScript [\[10\]](http://www.slideshare.net/BrendanEich/esnext "CoffeeScript as a JS/Next / ES.next").  Anyone who is serious about moving JavaScript forward should appreciate the usefulness of these features.


##CoffeeScript has a powerful effect on others.

I'm not the only one who thinks CoffeeScript is a life-changing experience.  Just look at these answers to *"Has anyone found CoffeeScript to be lifechanging?"* [\[11\]](http://news.ycombinator.com/item?id=2442743 "patio11 comments on: Rails 3.1 shipping with CoffeeScript").  JavaScript rarely elicits these adjectives (emphasis mine):

*"After a few months of CoffeeScript development... Jeremy, et. al., have done a __beautiful__ job with it."*

*"Yes, CoffeeScript is __amazing__."*

*"...CoffeeScript is a __joy__ to use."*

*"...it's class system and function binding (=>) is something I feel __I can no longer live without__."*

*"Coffeescript makes it __fun and productive.__"*

*"Yes, it's my __favorite__ language. __Very fun and nice__..."*

And more across the web:

*"CoffeeScript makes jQuery more __fun__ than ever."* [\[12\]](http://buhrmi.tumblr.com/post/5371876452/how-coffeescript-makes-jquery-more-fun-than-ever "How CoffeeScript makes jQuery more fun than ever")

*"Writing JavaScript becomes __fun__ again."* [\[13\]](http://www.mikkolehtinen.com/blog/2012/05/25/rewindy-tech-stack/ "Rewindy Tech Stack")

*"...CoffeeScript is __Awesome__."* [\[14\]](http://www.slideshare.net/jocranford/why-i-think-coffeescript-is-awesome "Why (I think) CoffeeScript is Awesome")

Such statements are rather common.  There is even a site dedicated to CoffeeScript Love [\[15\]](http://www.coffeescriptlove.com/ "CoffeeScript Love").  I wake up in the morning excited to continue development.  To me, this is the most valuable trait of all.

-----------------------------
###About the author:

*Charles Phillips (aka [doublerebel](http://doublerebel.com)) has been writing JavaScript for at least 15 years, and is the author of [TigerJS](http://tigerjs.com), a port of [Spine.JS](http://spinejs.com) to [Titanium Mobile](http://appcelerator.com) in CoffeeScript.  Charles advocated for server-side JavaScript before it was cool, and looks forward to when the whole world runs on ES6.*

-----------------------------
###References:

[1] "Why Functional Programming Matters" http://www.cse.chalmers.se/~rjmh/Papers/whyfp.html

[2] "Why Why Functional Programming Matters Matters" http://weblog.raganwald.com/2007/03/why-why-functional-programming-matters.html

[3] "Domain Specific Languages in CoffeeScript" http://amix.dk/blog/post/19614

[4] "What Storytelling Does to Our Brains" http://blog.bufferapp.com/science-of-storytelling-why-telling-a-story-is-the-most-powerful-way-to-activate-our-brains

[5] "Contracts.coffee" http://disnetdev.com/contracts.coffee/

[6] "What are disadvantages of using CoffeeScript?" http://www.quora.com/CoffeeScript/What-are-disadvantages-of-using-CoffeeScript

[7] "Functional JavaScript with CoffeeScript and Node" http://www.ibm.com/developerworks/web/library/j-coffeescript/index.html

[8] "Size Is The Enemy" http://www.codinghorror.com/blog/2007/12/size-is-the-enemy.html

[9] "Succinctness is Power" http://www.paulgraham.com/power.html

[10] "CoffeeScript as a JS/Next / ES.next" http://www.slideshare.net/BrendanEich/esnext

[11] "patio11 comments on: Rails 3.1 shipping with CoffeeScript" http://news.ycombinator.com/item?id=2442743

[12] "How CoffeeScript makes jQuery more fun than ever" http://buhrmi.tumblr.com/post/5371876452/how-coffeescript-makes-jquery-more-fun-than-ever

[13] "Rewindy Tech Stack" http://www.mikkolehtinen.com/blog/2012/05/25/rewindy-tech-stack/

[14] "Why (I think) CoffeeScript is Awesome" http://www.slideshare.net/jocranford/why-i-think-coffeescript-is-awesome

[15] "CoffeeScript Love" http://www.coffeescriptlove.com/