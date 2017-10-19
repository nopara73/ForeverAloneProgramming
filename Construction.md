![](https://github.com/nopara73/ForeverAloneProgramming/blob/master/Resources/Construction2.jpg)  
The goal is to build a working software.

# Time requirements  
At this point you should already know how much time this phase will consume, because previously you created a detailed schedule.  

# Workflow

## 1. (ProjectManagement) Prepare the project environment  

Ask for access to everything you might need to have. It is not ucommon that you have to wait for other people to take some action or for some processes to complete, so you probably will not have everything you need to build the product, but make the first steps to acquire them.  

## 2. (Testing) Prepare your testing environment

You are in the middle of developing a cross-platform application on Windows. You are not sure that one disk IO related function is going to give you the same results on Linux, but you did not set up a virtual machine in front, you said "I'll just set up a VM after I'm ready and test it." But now you are only 70% sure that function will work well. But meh, setting up a VM ideally takes half a day and it's always a hassle and I'm in the middle of something anyway.  
Now this is the situation you want to avoid. Do not be lazy and start preparing your testing environment now!  

After this step you might gain some new insight, if so, do not be rest and go adjust your test and cost models and your schedule.

## 3. (Implementation) Proof of concepts

Sometimes you know what is possible. Sometimes you are just guessing what is possible. Sometimes you know exactly the thing what you want to do is possible, but are not sure if it is feasible. You are not sure you are able to create it under the timeframe it still worth it.

Proof of concept work is very rewarding and can save you a lot of time in the long run. You do not need to do proof of concepts for every feature - just the ones you are not already confident you can do. If you have a project that needs to encrypt data in Java and send it to a web service written in C# that will decrypt it and you have not done this before you could do a very simple PoC that:

Encrypts 'hello world' using Java. You can then copy that encrypted text into a little C# console app that decrypts it. If you can get that to come out as 'hello world' again - you have proven the concept and have a couple of functions that you can use and extend upon in your project later. This will remove the stress from the later stages of the project. You don't want to get to 80% project completion only to find out that you can't find a library that can encrypt a string in a format that you can decrypt it in later and end up having to write one yourself at such a late stage in the game. Better to do the trickiest things up front.

|([Pragmatic Thinking](https://pragprog.com/book/ahptl/pragmatic-thinking-and-learning)) Stuck on a tricky problem?|
|---|
|1. Add sensory experience to engage more of your brain. Try fiddling with a paper clip [or with a ring or with your fingers] or some sort of tactile puzzle.|
|2. Talk to an egg, a cat or if you can catch one a real human being. Try to explain the problem.|
|3. If the egg does not understand you, you can try asking the oracle: [Oblique strategies](http://www.oblicard.com/) is a set of cards created by Brian Eno and Peter Schmidt used to break deadlocks in creative situations. |
|4. If everything else fails, turn off your left-brain and let your right-brain work on it for a while. Step away from the computer and do something else, something routine, like go for a thinking walk. Bear the problem in mind, but do not actively think about it. You want your left brain to get bored with the routine, mundane task and tune out. Leaving the right brain free to present its findings.|  

|([Pragmatic Thinking](https://pragprog.com/book/ahptl/pragmatic-thinking-and-learning)) Stuck on a tricky document?|
|---|
|Every now and then you will encounter some documents those are essential for the success of your project. It might be some academic paper, some theory in a blog post, a stackoverflow answer, what have you. The point is you find it very difficult to understand. You also could not acquire that information from a more digestable source. Here you could try to apply some techniques, like SQ3R, combine it with a mind map.|

Now get your architechture model and identify those parts what you feel problematic. You are going to implement proof of concepts for those hard parts. By knowing this adjust your schedule.  
Go on, study these subjects and create proof of concepts for them one by one.  
What you are doing here is called learning by synthesis. You are gaining new insights after every prototype you create. 
After every one of them evolve your architechture, test and cost models and schedule.

## 4. (Implementation) Code

Finally we arrived to the point where we can do what we are really good at. Coding. Coding a well-defined architechture **without the distraction** of worrying about not being able to deliver the product. At this point we (think we) know exactly what our product will and will not do. At this point basically we only have to put the lego pieces together.

Do not be distracted as you progress by any new features you think of - put them in the 'nice to have' list you made earlier and move on. You have to focus on the key deliverables at this stage. Once those are done you may well go back and see which of your 'nice to have' features you have time to add - but only when the key ones are delivered. 

It is also easy to get side-tracked by the introduction of new frameworks and ways to do what you have already committed to code. If you stopped every time a new release of a framework you are using came out and went back to upgrade what you have already done - or worse, abandon it and use a new one altogether - you will forever be in a game of catch up you can never win. 

Once you have picked a technology and framework set and started using it - stick to it until the project is completed. You can always go back to it and upgrade at a future date. Delivery of key features is more important than using the very latest release of something - your users will not really care what was used to deliver the solution - just that it was delivered and was delivered in a timely manner.

|Tip|
|---|
|Here you have a unique opportunity to simultaneously boost both the quality and the speed of development of your product. Newbies code mainly with reasoning, experts code more with instinct. Newbies with the left brain, experts code with both brain. Of course this is a huge oversimplification, but meh, you get the point. The left brain is verbal/analytic/logical/synchronous/... and slow. The right is non-verbal/synthetic/intuitive/asynchronous/... and fast. This is the very section where you are the closest to be able to call yourself an expert (you have already figured out and implemented the hard parts). As an expert you can speed up your coding by utilizing more of your right brain, but it also enables you to not get stucked with the details, so you will be able to keep the big picture in mind, as a result build a well-balanced product.  
So how can we utilize more of our brain power, especially the right one? My method is **caffeine and lyiricless music, like [this battle tested playlist](https://www.youtube.com/watch?v=0r6C3z3TEKw&list=RD0r6C3z3TEKw#t=9). Also depending on how much you are willing to sacrifice amphetamine and methamphetamine can help a lot. Cocaine might work, too, but I am not sure. Check out [this discussion](https://www.quora.com/Would-coding-under-the-effects-of-cocaine-make-you-more-productive-Has-anybody-tried-it), might give you an idea.  
An other method could be pair programming. The one who codes is the left brain, lost in the details and the one who sits behind is the right brain, who keeps the context in mind, who's looking for patterns, who's thinking out of the box. Also note, the pairs should have the same level of expertise.|

## 5. (ProjectManagement) - Does your product satisfy the requirements?  

If so you can archive that document and your architecture modelling documents already, don't let them distract you anymore.

It is worth checking this every few days or before you start a new piece of work and ask yourself 'am I still working on things that I set out at the start as my key requirements?'. If you find yourself being distracted because some little issue led you down a rabbit hole then you must pull your attention back to the task at hand.

Developers are natural problem solvers. One minute you are writing code to save a file to disk and notice an odd way in which the date format you chose for the filename was being written out and three hours later you are deep in the code writing your own solution for a universal decimalised time protocol! If you find yourself doing things like this often it is worth setting an alarm every 30 minutes - 'look up and think!'. Maybe you didn't even need to use a date/time in the filename - you could have used something else and you just lost 3 hours because you are inquisitive. Break that habit if you can.

## 6. (Testing <-> Implementation) Pre-production testing <-> Bug fixing

This section is self-explanatory. Test the product and fix the bugs you find.

As developers we often test the app to see if it follows the logic we wrote into it. Our users may not know what our intention was with something we have added and so it is often useful to get friends or family to try using the app as well. Do not instruct them as they use it - just let them open it and see what they do. What seems obvious to you (because you wrote it) may not be obvious to everyone else. Remember - you will not be there to sit and explain how to use the app to everyone who downloads it. Observe people unfamiliar with it using it. 

## 7. (ProjectManagement) Reach agreement on milestones

|Template|
|---|
|[Milestones](https://docs.google.com/spreadsheets/d/1Du0ZyJNEk_0sKSfAKMe3H6vMxC6S8520Nag32If0BRY/edit?usp=sharing)|
