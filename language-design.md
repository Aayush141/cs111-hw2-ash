_Fill in each this file with your responses, placing each response after its
corresponding question._

---

**Question**

Pick three quotes from the readings about language design. Good candidates
are:

- Something you agreed with / resonates with your own experience
- Something you disagree with
- Something that is interesting, a new idea or perspective you'd like to remember
- Something you didn't understand

For each quote, describe what it was about the quote that led you pick it.

**Response**

"He said that their usability testing showed that simply finding natural-language replacements for some of the more abstruse syntax went a long way." [Pavlus, 2012]

Here, when the author is talking about evidence based PLs, I feel like they overlook programmers that do not speak English - or whatever natural language replacement is being used. Sure, it will make things easier for 25% of the population - but having to write programs in a more verbose nat-lang might make it harder for the 75% of the world that does not speak English. While I do agree with the points in this paper, I felt it overlooked a major component/population. 

I also felt like, while the natural language code might seem more intuitive to novices - most programmers are not novices, and I wonder if there is any significant benifits that experienced programmers see. To me, I like Java's loop syntax a little more because of how stuctured and precise it is. Natural languages are open to ambiguity and rephrasing.

"I should not design a small language, and I should not design
a large one. I need to design a language that can grow" [Steele, 1998]

I found this very interesting. It is something I will remember for the future, as it feels like good advice.
I also thought how the author explained this via analogies with Natural Languages, and via the examples and trichotomy between Pascal,PL/I and Fortran - was really cool too.
I wonder though, how relevant it still is today. One of the reasons why we need languages that can scale up is to match progress, but is there really that much progress being made in Programming Languages today? 

"APIs should be self-documenting: It should rarely require documentation to read code written to a good API. In fact, it should rarely require documentation to write it."

I mostly agree with this. It is great when the syntax and naming just makes sense. I do think that these are very lofty and unrealistic goals though. Beyond that, I still think it is important to have good documentation. Even if your API is soooo good that you don't need it, it is good practise to have everything well documented. 



**Question**

How would you know a well-designed language? What are the symptoms? How would
you know a poorly designed language? What are the symptoms?

**Response**

> How intuitive it is. It should be intuitive whether, say, "gray(100)" is white or black - and what gray(100) means. As we see in the grayscale article, names/wording are an important thing to take under consideration while building an intuitive language or API. The Bloch article talks about the importance of naming too. 

> "I think that whenever you make a product design simpler there’s a potential danger of removing features that experts need” [Bloch, 2006]. A well designed language balances and tries to achieve both. It is, obviously, important to have functionality but you can still make things simpler by not having a lot of jargon, weird syntax, and keeping in mind what the user wants(by constantly getting feedback). 

**Question**

How might the themes of _Growing a Language_ relate to ideas from the Fowler reading?

**Response**

TODO

**Question**

In what way is an API a language?

**Response**

A language is used for a human to communicate with another human, an API is used for communication between one computer program and another. This makes an API analogous to a language. API has syntax, structure and commands much like a language has syntax, grammar and vocabulary. These features allow computer programs/humans to communicate with one another. 

**Question**

What does the post on grayscale tell us about the process of API design?

**Response**

There is a lot of thought that goes into even the "little details" of designing an API. Or at least what we think of us as just "little detals", but can be important in making sure that using it is intuitive and doesn't require re-learning by looking up online each time what, say, 0 is and what 100 is. It reminds of this Vox piece I had seen on doorways. Doorway design may seem pretty straightfoward and banal - but there are a lot of important things to take under consideration. When opening a door, we often have to check whether we have to push or pull to open it. But a well designed door does not need to tell you, as it is intuitive. On the flip side, a poorly designed door will have you consistantly doing the exact opposite of what is required to open. (This is akin to intuitively figuring out if 100% is white, or 100% is black based on the name alone)

Naming goes a long way in building intuition. "Names matter. Strive for intelligibility, consistency, and symmetry. Every API is a little language, and people must learn to read and write it. If you get an API right, code will read like prose. " [Bloch, 2006]

**Question**

The Pavlus article mentions the researchers' comments that people preferred
"natural-language replacements for some of the more abstruse syntax". In other
words, people found it easier to work with code that looks more like a human language (e.g.,
English). Consider the following quote by William R. Cook, one of the creators
of AppleScript:

> The experiment in designing a language that resembled natural languages (English
> and Japanese) was not successful. It was assumed that scripts should be
> presented in “natural language” so that average people could read and write
> them. … In the end the syntactic variations and flexibility did more to confuse
> programmers than to help them out. It is not clear whether it is easier for
> novice users to work with a scripting language that resembles natural language,
> with all its special cases and idiosyncrasies. The main problem is that
> AppleScript only appears to be a natural language: in fact, it is an artificial
> language, like any other programming language. … even small changes to the
> script may introduce subtle syntactic errors that baffle users. It is easy to
> read AppleScript, but quite hard to write it.
> [[Cook 2007, page 1-20]](https://dl.acm.org/citation.cfm?doid=1238844.1238845)

Are these two experiences of natural languages at odds with one another? Would
you choose to include natural language in the design of a DSL? If so, how might
you do so? If not, why not?

**Response**

I really like this question. I touched up on this in a previous response of mine : 
" I also felt like, while the natural language code might seem more intuitive to novices - I wonder if there is any significant benifits that experienced programmers see. To me, I like Java's loop syntax a little more because of how stuctured and precise it is. Natural languages are open to ambiguity and rephrasing." 

I do not think these experiences are at odds with one another. While nat lang code is easier to read, it is harder to write. While "random syntax" code is harder for novices [Pavlus, 2012], it is easier once you have some experience working with it. I think a close-ish analogy for the latter might be MS Paint vs. Adobe Photoshop. While MS Paint is easier to pick up, it is harder to grow much in it while the latter gets more intuitive with time as you build muscle memory. 

There aspects of natural language inclusion that I find really appealing, and there are aspects I dislike. On the one hand, reading and understanding code in natural languages is so satisfying and easy. But natural language is ambiguous, open to interpretation and open to being rephrased. You, ultimately, still have to memorize the correct way of doing it - and memorize the ways that may seem correct but are not. 

If I had to make a DSL today, I would likely go the "Java"/"Perl" route (while also including some Natural Language elements where it makes sense). I personally like being "structered and organized", and I feel like the natural language route allows variations and flexibility where it would only make things confusing. Some natural language elements here and there might make the code more readible. Striking a balance between the two is important. 


