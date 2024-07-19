The story/journey of the talk
- This talk is about a recursive topic
- Thinking about your own thinking can make you a better software developer, a better teacher, a better learner, and a better person
- Think about thinking about thinking can help you
    - model other people's thoughts and feelings and understand the motivation behind their actions
    - understand the reasons behind your own actions
    - shape habits
    - learn
    - teach
    - empathize
    - be more compassionate
- our brain makes mental mental models... some mental models you can't really control, but some you can
- my students sometimes have trouble understanding how Python's variables work because it's easy to assume a mental model that doesn't match up with how Python actually works
- TODO need a story here maybe?
- Story about recording video and experiencing sunk cost bias
- Cognitive biases happen... we can't completely avoid them, but we can acknowledge them and try to work around them
- The next time I have an urge to edit a video, I think I might remember publicly admitting my own sunk cost bias on stage at PyOhio and *hopefully* I'll pause for a moment to seriously consider whether I should re-record my video instead of editing it
- So our brains form mental models about the world and use heuristics to patterns in the world... Both our mental models and our brain's mental heuristics can have bugs that bias toward making undesirable decisions
- This is both a part of being human and it's something that we can and *should* try to recognize and work around when possible
- But we also use language to communicate mental models to *others*...
- And sometimes we might accidentally *imply* a mental model that we didn't *mean* to
- TODO maybe shorten names and words section to ...
    - naming variables in your code is important for the sake of readability (as is using variable names instead of indexes)
    - it's hard for me to teach Python's many asterisk syntaxes because they lack clearly defined names that everyone agrees on... unlike the "walrus operator" which we all call "the walrus operator". It has a name, it looks like the name, and it's memorable.
    - name things, well
    - names paint mental models, both explicitly and implicitly
    - Years ago, while teaching I used to use phrases like "x contains a list" or "x is a list". I found that these phrases made it harder to explain the way Python's variables work.
    - There is a repeated interaction I've had over the years: "I changed x and y changed, but here when I change x, y doesn't change". The word "change" is the problem here. That word is accidentally playing two different roles... it's like the word biannually or "ounces"... are we talking weight or volume?
    - So instead of using the word "change", I encourage folks learning with me to be more explicit (as the Zen of Python says)
    - Note whether we're assigning (changing a variable) or mutating (changing an object)
    - The words we choose are important, especially when we use certain words and phrases habitually or when our words will be heard or read by many people
    - Thinking about the mental models behind your words can make you a better documenter, a better technical writing, and a better teacher
    - And more generally thinking about the words and phrases we use can make you a better coworker and a better friend (see Ned Batchelder's keynote on interpersonal interactions, April, and Jesse too?)
    - ...
- we've talked about how deliberately considering your mental models can improve your understanding of the world around you, how trying to recognize your cognitive biases can improve your decision-making abilities, and how considering the words we use is important for the sake of hinting at more accurate mental models and also to improve our interpersonal communications...
- Now let's talk about iterating (for loop)
    - But not that kind of iterating...
    - We're talking about making progress
    - PSF CoC
    - Years ago I read a book called "Make it Stick"... I've read many other books on learning since then, but that book happened to be my introduction to a number of important topics related to teaching and learning
    - There's one idea that stuck out to me in that book and both excited and upset me...
    - Blocked vs interleaved practice
    - My courses at the time were in such a way that when it came time to write code, we would write code that practiced one specific topic.
    - Based on what I'd learned, this fairly common teaching style sounded like blocked practice... but I'd just learned that this is inefficient
    - Bouncing between multiple topics is a *more efficient* way to learn than focusing on just one topic...
    - After this realization, I felt as if I had two choices...
    - ... I still haven't updated my curriculum to embraced interleaved practice as much as I'd like... I *have* made *some* progress though.
    - Don't be afraid to acknowledge that *you* are *your actions* are a work-in-progress, all the time. Being a work-in-progress means you're moving forward and that's excellent. Moving forward requires us to acknowledge that there's progress to be made.
- Whether you're trying to adapt to a new mental model, work against your brain's natural cognitive biases, or change your habits around the words and phrases you use, you're not going to suddenly change overnight. Acknowledge that there's progress to be made and take your first step down the slow path of change.
- Change feels uncomfortable, both the change you make yourself and the change the happens *to* you.
- CoC discussion at meetup years ago
- Sometimes making growth and progress *require* sitting in discomfort
- I have my own story about sitting with discomfort that I'd like to share, but first I'd like to briefly talk about fences...
- Do I need to donate my money to be a good person? Do I have a moral obligation to donate one of my kidneys? Am I supporting animal cruelty by eating chicken?
- 4 years ago, I read a book called The Life You Can Save. 


- This is the meta portion of the talk, where I tell you what this talk is about... it's about metacognition
- Learning about learning is probably the thing that initially got my interested in metacognition
    - What's effective for learning isn't always aligned with what we *think* is effective
- Mental models
- Mistakes happen... introduce moral philosophy here?
- Cognitive biases (sometimes our mental models are hard to control)
- Naming things... a shortcut to a mental model, sometimes accidentally
- Living with the status quo and occasionally questioning it
- Making progress
- Be kind to yourself, be kind to others
    - Being a human isn't easy. We hold ourselves to high standards... standards that are a bit higher than just "let's not kill each other".

- Python's `functools` module has a function called `wraps` which is a helper for making decorators
- `wraps` is a function that accepts a function and returns a function that accepts a function and returns a function... that's a pretty confusing way to explain `wraps`
- `wraps` is better explained by using an abstraction: it's a decorator that accepts a function as an argument
- We already think about thinking automatically... I think we should do it more often and more deliberately
- I find thinking about metacognition really useful
- If I didn't know the *word* metacognition, I'd need to say that I find thinking about thinking about thinking really useful
- Which is kind of confusing...

- Having names for concepts is *very* helpful
- But our *choice* of names is also important
- Not only is our choice of names important, but how we phrase things can be very important
- Python code, the output of Python code, and the English language are the primary ways I attempt to convey ideas to the folks I teach
- We use words as an attempt to convey a mental models
- The words we use can sometimes subtly convey the wrong idea
    - "Let's update the list" but then we assign to a new list
    - "x contains 4"
    - "x is 4"

- Focus on outcomes
    - Stop focusing on your moral worth. Try to maximize the good in the world.
    - Outcomes matter a lot more than intent
    - Selfish versus selfless doesn't matter nearly as much as maximizing outcomes
    - In 100 years, most likely no one will remember anything that any of us did... but we *can* leave the world a little bit better off in the process
- Admit fault
    - The unfortunate balance of ego:
        - Inflated self-worth: I am good, so if I did something bad there was a good reason.
        - Deflated self-worth: If I did a bad thing, that means I'm bad. I can't handle being bad.
    - A focus on "self" is a slipper slope toward not being able to handle the fact that you made a mistake
    - We all cause harm
        - You did someting that caused harm. Maybe it was a "bad" thing or maybe a "good" thing that had some sort of negative outcome.
        - Doing a "bad" thing or simply causing harm does not mean you're "bad".
        - Your moral worth doesn't matter... at least it doesn't matter to anyone else.
    - Apologizing is hard. It's a learned skill and it's not trivial.
- Work toward improvement
    - Improve your understanding of the world
    - Improve your understanding of yourself
    - Improve your understanding of others
    - Try to improve the world


Why?

Harness metacognition for good

- Think about thinking about thinking (metacognition)
- It can help you model other people's thoughts and feelings and understand the motivation behind their actions
- It can help you understand the reasons behind your own actions
- It can help you shape habits
- It can help you learn
- It can help you teach
- It can help you empathize
- It can help us all be more compassionate

My reasons for this talk are selfish

- I am really interested in metacognition
- I'm a nerd who loves spreading my own interests
- Because the idea that some of you may be interested in what *I'm* interested is exciting
- The more folks in the Python community talk about different aspects of metacognition, the more I get to learn and 
- So I'm hoping to spread my interest of metacognition in the hope help grow your appreciation for this topic
- How metacognition has helped me...

We undervalue metacognition and I want to talk about it myself more often and I'd like the Python community to talk about it more often. Metacognition is at the root of

- The reckoning that stems from confronting difficult realizations
- Self-compassion that we extend ourselves when we realize that our brains are beautiful but also imperfect
- Improved emotional intelligence
- Successful habit formation
- Successful learning and teaching
- Empathy and compassion toward others who have a different model and experience of the world than we do
- Our emotions, including the uncomfortable ones

Naming a thing can be powerful.

You're thinking in terms of mental models all the time, both implicit and explicit ones. You convey meaning through words and you make an impact through actions.



My belief is that thinking about thinking makes me a better person
And learning about learning makes me a better learner and a better teacher

And if this belief holds true for everyone then metacognition is how we become better people, better learners, and better teachers.


Deontology is about "doing what's right"
"It's the thought that counts"
Consequentialism: doesn't matter what you do but what the result is
"The road to hell is paved with bad intentions"
Deontology has a clear right/wrong
Consequentialism leans toward accepting that we might weight things incorrectly


---

Notes after rehearsal with Michael...

Reminding folks what we're talking about and what we're going to talk about... especially toward the end extend that


Perfection is the enemy of the good

Maxmizing versus satisficing

MVP

Example: Starting Python Morsels as a mailing list


Someone tried to accomplish something there.
Sometimes the fence isn't what it was intended to do. Question why things are the way they are. Don't assume that something is as it should be, but also don't assume that it has no purpose.


Inventing your own library feels good in the moment until afterward when you realize you now have your own somewhat flawed library to maintain.
