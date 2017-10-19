![](https://github.com/nopara73/ForeverAloneProgramming/blob/master/Resources/Inception2.jpg)  
The goal is to identify the initial scope of the project. 

# Time requirements
This phase usually takes 1 hour to 3 days to me depending on the communication overhead and the nature of the project.

# Workflow
Modelling, Implementation, Testing, Deployment, Project Management: the AUP terminology calls them **disciplines**, so do I.  
I only include the most relevant disciplines under every **phase** (Inception, Elaboration...), if you feel like you need to work on the other ones, you are free to do so.  

## 1. (ProjectManagement) Gain general understanding over your project  
|Template|
|---|
|[Lean Canvas](https://docs.google.com/spreadsheets/d/1HTz5RHYRFxHEfB-0ZlRJPw5l_qQaYGIj4VRbATSVy0c/edit?usp=sharing)|  

First fill out a Lean Canvas. It forces you to think about the relevant questions you would otherwise skip. **Be superfical.** Feel free to leave some sections empty, do not get lost in details. Later it will be used as a reminder, not as a recipe. Also it will be soon discarded.

![](https://github.com/nopara73/ForeverAloneProgramming/blob/master/Resources/LeanCanvas.png)  

|Stop|
|---|
|**Do you have the freedom to choose what project you are going to work on?** If the answer is yes, take a step back and reconsider the one you currently have in mind. This is the perfect time to open that old folder where you have collected the milliondollar ideas you had during the years, but you have never actually bothered to review them. Look them up, quickly select 3 [to 7](http://phys.org/news/2009-11-brain-magic.html) with your right brain (instinctive decision making) and complete this first step for every one of your selected ideas. (Scratch lean canvases.) Finally choose the winner.|

## 2. (ProjectManagement) Setup project directory structure

|Template|
|---|
|[Project Directory](https://drive.google.com/folderview?id=0B2Y-ddI1xJy7ZjY1SzE0Sk5MaGM&usp=sharing)|

I organize the directory structure of my projects by disciplines. In every discipline folder I have an `_Archived` folder for those items I do not actively need anymore, therefore they would only be distractions.  
Now grab your lean canvas and put it in the ProjectManagement folder.

## 3. (Modelling) Define high level requirements  
What the system will and will not do? I usually just make a list in a .txt for this.

Separate key deliverables from ones that would be nice to have. If you start off listing everything as essential you will never finish your project. 

Key deliverables are ones that solve the problems you listed in the Lean Canvas. These are the things your end users will want to use your system for - they are the key selling points. Everything else should go in to other lists: 'nice to have' and 'later versions'. It is worth noting that by delivering just the key deliverables and pushing your software out there you may well get feedback from users on what extra features they would like to have added and that these may not be ones you envisaged in the beginning. Often it is a good idea to let your users evolve the product's feature set instead of pushing out things that are on your 'nice to have' list.

## 4. (ProjectManagement) Estimate cost and schedule

With each key deliverable listed at high level it is now time to break the deliverable down into smaller sub-deliverables. Thinking about the steps needed to achieve each key deliverable will come in useful later on when you start doing proof-of-concept work. You don't need to go into too much detail here - that will come later in the Elaborate phase. An example might be:

Key Deliverable:

1.  Allow users to message everyone in their contacts all at once or per-group.

    1.1 Allow users to create groups

    1.2 Allow users to assign contacts to one or more groups

    1.3 Add a 'send to group' option which lets users pick which group/s to send to

At this point it is fine to give a gut feeling estimation on how long every phase will take.  
You can get a more accurate estimation for the Construction (and Deployment) phase by giving an time estimation to every high level requirements you defined.  
Regarding the costs, try to identify the main ones. But remember the motto of this phase: do not get lost in details.

## 5. (ProjectManagement) Determine project feasibility

> (AUP) Your project must make sense from technical, operational, and business perspectives. In other words, you should be able to build it, once it's deployed you should be able to run it, and it should make economic sense to do these things.  If your project isn't feasible, it should be cancelled.

## 6. (ProjectManagement) Reach agreement on milestones
|Template|
|---|
|[Milestones](https://docs.google.com/spreadsheets/d/1Du0ZyJNEk_0sKSfAKMe3H6vMxC6S8520Nag32If0BRY/edit?usp=sharing)|

To exit any phase participants must agree the project completed the current phase's milestones.  
This should not be taken lightly. Do you find it catastrophic when your whole project changes nearing its end, because the customer "made a little modification"? Well, agreement on the milestones will not eliminate this risk, but certainly will lower the chance of it happening.  
Keep in mind, not only the stakeholders have to agree, the participants, too. You do not want to end up like this guy:

<a href="http://www.youtube.com/watch?feature=player_embedded&v=BKorP55Aqvg
" target="_blank"><img src="http://img.youtube.com/vi/BKorP55Aqvg/0.jpg" 
alt="https://www.youtube.com/watch?v=BKorP55Aqvg" width="240" height="180" border="10" /></a>
