OK good morning welcome to my talk on building high performing engineering teams we'll go ahead and get started here

[ Slide - Biography ]

First here's a biography slide you can see a little bit about myself my name is Benjamin Spain.  I have been in the field of software engineering for 25 years now you can see up there a couple of the different companies that I've worked at.

I have been an Engineering Manager of seven different engineering teams.  In that time some of those teams were brand new and I had to build them up from scratch, some teams were well established with seasoned veterans. I've had to manage teams that have gone through significant reorganizational structure, which sometimes this involved some of those very difficult conversations with engineers who finding themselves needing to be managed up or managed out. 

Currently I am a Principal Engineer at Thrivent corporation working in the Engineering Productivity space.  Even though I've moved back into what would be considered an individual contributor role I still actively mentor a couple of engineering within the company today.

[ Slide – Dense Topic]

So this topic here today this is dense.  I'll tell a little bit of story, last year I spoke here Open Source North about skills for Developers around AI usage.  For that topic, I had to do quite a bit of research.  

With this talk, I wanted to pick something, not “lighter”, but something that I had a lot of experience with.  I figured that my research would be simpler to do.  However as I sat down to do prepare and research, I realized “Wow!” There is clearly more then what is reasonable to cover at a 40 minute presentation.  We could go into a talk about having difficult conversations, situational leadership, or the importance of psychological safety and trust.  Those are really important concepts.  But in this talk I'm really looking to provide 12 distinct things that I believe, Engineering Managers in particular, should be consistently drilling into.

[ Slide – Sinek Quote ]

So here's where I want to anchor our presentation or discussion here. This comes from “Leaders Eat Last” by Simon Sinek where he says “when a leader embraces their responsibility to care for people instead of caring for numbers then people will follow.”  During my growth as an Engineering Manager I read a great amount of material from Simon Sinek in particular and I'll quote some of the resources as we go through this talk here today.   But this talk is really then anchored on applying this idea of “caring for people” in the context of someone leading a highly technical profession like software engineering.

[ Slide – Roadmap : Three Ways ]

So with that I'm going to take a page out of the DevOps handbook and align this idea of managing teams against the three ways of DevOps.  We'll talk about FLOW and in the context of how critical it is that we visualize and understand the nature of the teams work. We'll talk about FEEDBACK, both in terms of getting feedback on the value proposition of the work but as well as feedback about the way the team works, and we'll talk about some of the signals and observability things that are key to high performing teams.    Then we'll talk about the notion of CONTINUOUS IMPROVEMENT and how we leverage the feedback cycle to ensure the team is growing while delivery on the value.

[ Slide - Flow ]

Let's start then with this nature of flow and how we apply this to the work that our engineering teams are doing

[ Slide – Visualize all work]

The first step here is to make sure that the team is able to visualize all of the work in flight ***and this should really mean ALL of the work***.   Regardless of if the team is operating in a style that's Agile, or Kanban, or even Waterfall, the intent here is that incoming work should be known, what's actively being worked on should be known, and that there is a record of what has been accomplished.

I've worked with engineering teams who will get into deep debates over how big should something be before it's represented on a board.   I've seen some engineering teams want to blow this process out exponentially and add all sorts of columns track all manner of different states of the work that's in flight.  Your job as the manager is then to try to find ***what's the elegant balance that fits your team***.  Make sure that no one's work remains *hidden*, but avoid overly complex work tracking process.

I've seen other teams that have been adamant that they want to eschew the idea of ***even having to track work to begin with***.  This may feel like a way of operating that is the most-flexible, but as I will talk about next, too often this leads into too many things in flight at the same time, and often with poorly understood value propositions.

[ Slide  - Know where work is coming from]

The second point to talk about here is knowing where all of the work is coming from.

I have observed managers who look at a board that contains a whole lot work where they themselves are confused as to how that work actually got on the board to begin with.   A good manager will help scrutinize and understand what kind of work should actually come into the team and what can be deferred or even rejected it because it sets up a team to be doing more than it should.  

If you discover tasks on the board that you don't understand where they came from it's ***your job as a manager to double click into them***.  Each piece of work should represent a clear deliverable of value.  

Look for the ways in which ***your engineers bringing work into the board***.  Often, engineers are being asked to do things by other people, this could be sudden changes in requirements coming from your product team this could be persistent requests from help from other engineers in the organization.

***Keep refining the method here.***   Similar to the way in which we talked about finding the right balance in the way that work gets visualized your job is also your job to help get your team to figure out what's the right way in which we allow work to come into the team to begin with.

A high-performing team certainly ***wants to be flexible and adaptive*** to the changes that may come from product and at the same time we want to see a culture of engineers who are very helpful to other engineers when they make requests but over indexing on any one of these two areas results in what the DevOps handbook refers to as the worst kind of work which is unplanned work

[ Slide – Steady direction at pace ]

According to the theory of constraints, if one part of a system to be fully utilized, every other part must have excess capacity.  This means that if a team is fully at capacity they will actually end up limiting other parts of the system.   ***Therefore, as a manager***, you are ensuring that the team is operating in a steady direction at pace.  Ensure the team is focused on a finite set of measurable deliverables and avoid ***planning for work at “max” capacity***.

We touched on this in the previous slide where we talked about scrutinizing what comes into the team as work but here it also applies in that you should be trying to ***avoid any frequent changes*** happening within the workstream of your team.  Every type of change requires a lot of effort in terms of context switching and knowledge transfer.  While being adaptable and flexible is important you should be aware of how frequently anybody on your team is being put in the position where the work that they're doing is changing frequently.

One excellent technique here is to make sure that the teams are working in ***very small iterative changes***.  Similar to what we talked about in the first slide in this section, your engineers may want to skip through the process of refinement and get straight to the implementation however your job as a manager should be to correct that behavior and enforce good task refining into small iterable easy to deliver increments of value.

[ Slide – Where two or more]

Last in this category we'll talk about ***avoiding single threaded engineering*** or this idea that every feature should be worked on by an individual engineer.

it's quite simple to talk about ***actually, pairs of engineers can design iterate ***and review the implementation of features much faster than individual can.   Note that you are quite likely to find engineers on your team who want to try to avoid this and would rather simply create all of the code for the feature themselves but this is an anti pattern that you should avoid.

Eventually, every feature should undergo a peer-review, and if members of the team need to stop their work frequently, in order to acquire the necessary context to perform an effective review, then the perceived momentum gained by having an engineer work as an individual is quickly lost when it comes time to review.

Another reason I avoid this is because I find that ***individual engineers working on a feature*** will often become far too attached to their implementation.  It's been noted quite clearly that if multiple engineers are working in tandem on a feature set, then the behavior of that feature is critiqued much more frequently and earlier in the process and the result is a higher quality deliverable with less emotional attachment to the way in which a feature was implemented.

[ Slide - Feedback ]

Let’s move on to the topic of Feedback

[ Slide – Daily Looking for Problem Signals ]

In sticking with the theme of DevOps we have to talk about what happens when a ***product eventually moves into operations***. One of the behaviors that you definitely want to see on your team is that there is daily inspection of the system that is also helping to gather data necessary to assert that the service is delivering value to the customers that are using it.  If you can,  establish a way in which the members of your team have access to a ***Direct Line of feedback from the customer***.   

Just as important however is that this daily inspection of the system is also helping to gather data necessary to assert that the service is delivering value to the customers that are using it.  If you can,  establish a way in which the members of your team have access to a ***Direct Line of feedback from the customer***.   

Even in cases where this is possible every team should be looking at ***something that represents an observability dashboard*** that is monitoring the health and error states of the service that they've built 
Develop a solution here that works best for your team.  I have found creating some form of an on-call rotation in which the on call person that week has a responsibility to look at all of the observability and any feedback from customers.  When they find something that indicates a problem, they have a responsibility to work on either fixing it immediately, or getting it accounted for in the backlog.

[ Slide – Andon Cord]

The Andon Cord concept, as discussed in the DevOps handbook, originates from Lean Manufacturing.   This is a cord that workers can pull that will instantly halt production whenever they detect any kind of a defect.  Studies have clearly found that when workers have the ability to halt production when they see anything that this ends up being a significant contributor to high performing output.

Your role as the manager is really to try to enforce a culture around this concept.  Assuming you have something akin to an on call rotation you should definitely encourage anybody who ***sees something to say something*** and get the attention of the team.  You should also ensure that your team's ***culture celebrates blamelessness*** when people raise issues. You will likely have to fight against the idea that this should be viewed as a distraction or that somehow engineers need to be hesitant in bringing up an incident out of fear that they'll get ridiculed.

Outside of incidents in production however, ***adopt this strategy for development work as well***.  One rule of thumb that we use in our organization is that any engineer should feel that after about 30 minutes of work on any particular task, if they find themselves blocked, they should raise a hand and ask for help from the broader community in our public chat channels.  There are some guidelines that we're trying out with this process, when asking for help, document the problem they are trying to solve and the actions they have already taken.  This means the community at large has an easier time getting context around the problem.  We, as the engineering leaders then, are also championing and recognizing those who do a good job at explaining what they've done and those that are able to come in and help out the person to become unblocked. We are also looking for people to document when a solution is found so others searching for an answer to a similar problem can quickly see what others had already tried and what they found that worked.

[ Slide - Retrospectives]

I say often that one of the greatest concepts in the agile framework is the ceremony of retrospective. I won't go into the mechanics of what a retrospective is here, as there's plenty of material that you can find.

As a manager I believe he should insist that these retrospectives happen on a predictable schedule.  Predictability means that engineers on your team know that there will be a forum where impediments or ideas for improvement will be discussed.

As a manager you should make sure that this is a safe space for people on your team to deliver feedback.  Some managers I've worked with have chosen to not be in the room while the retrospective is happening and others choose to be there. I don't have a strong opinion on it either way.  What I will recommend is that you treat anything brought up within the team's retrospective as important.  Especially use your one-on-one times with engineers to discuss these topics.

You should be making sure that your team is using the retrospective to focus on actionable improvements that are within their team's control.  I believe you're likely to find a lot of engineers will use the retrospective to explain how they could get their job done better if some other team would deliver or change or do such and such.  This is important feedback to get from your team and you should make sure that your team knows their concerns are heard but your role should also be to challenge the team to look deeper into the tangible things that they can do to either, improve the system that they have to work with, improve the communication mechanism that they need to have with the team, or gather the data that they need to indicate how other parts of the system are impeding their abilities to make progress

[ Slide – Performance Goals ]

OK a little confession time. In my 25 years as an engineer I have always struggled to write individual performance goals.  If you are in an organization that is asking engineers to write performance goals part of annual review plan, then I hope you will find this idea useful. 

About a year ago that I came up with this idea to ask all of the engineers on my team establish a performance goal describing ***how they will perform as a member of the team***. This idea ties back into the importance of a team retrospective because I believe that done well some of the elements of the team retrospective will turn into “working agreements” or “ways of working” for the team itself.   As an example, when somebody submits a request for peer review the team should have an expectation that gets reviewed within 4 hours or 8 hours or whatever it is depending on the type of the nature of your team.

In addition I've seen retrospectives that have said,  “well in order to start preventing these type of bugs from getting into the system we need to perform more design reviews before we start implementing”.  I love when my teams create agreements to a way of working, therefore I believe it makes sense to ask an individual engineer write a performance goal that says “I will uphold the working agreements of my team.”  It is my strong opinion, that an individual performance goal that is written this way, is far more valuable then one that relies on an engineer delivering such and such by a certain date.  Results can easily take the form of feedback from peers on the team.

The second performance goal that I often find myself working with engineers on is the idea about ***how can they can incorporate learning new skills***.  We'll talk about this a bit more in the final section on continuous improvement but I've seen a lot of engineers write a performance goal that was akin to “I will go take a course” or “I will go study a topic”. I always react with, “that's great! What can I do to provide time, resources, or materials to help?”  Rather than simply leave the engineer to go off and learn a thing however I ask them to include as part of their performance goals a commitment to bring that new learned skill back into the team either in the form of applying it to the future project that we have or at the very least carrying out their learnings to the team in a forum of some kind.

***In both cases***, the results can simply be measured by peer feedback.

[ Slide – Continuous Improvement ]

Let’s move on to the final section of Continuous Improvement

[ Slide ]

Every good engineering manager should be deeply investing in and ***finding a good technical lead for the team***.  You've probably heard stories to this effect and I've certainly observed it in my own experience, that a highly skilled and capable individual contributor will take the role of an engineering manager and for a long period of time they act as the technical expert within the team.  And in many cases rightfully so, however going back to the first established principle that we talked about which is about caring for people, I strongly believe that the moment at which an individual contributor becomes a manager they should begin a quest in earnest to ensure that their own technical expertise is not only quickly transferred into the members of their team but that the members of their team are ultimately surpassing them in terms of technical knowledge.

In fact I have met and interacted with other engineering managers who did not come from a highly technical background, but have found them to be exceptional managers in their own right, and I strongly believe it's because they understood this principle in earnest.  Whether you come from a highly experienced technical background or not the net result within your team should be the same, in which case your leads are the ones being responsible for ensuring that the technical skills with the team are growing and evolving in a way that makes the team effective.

in either case however it is important for an engineering manager to be ***improving their own technical capabilities as well***.  As an engineering manager I'm sure you will find yourself involved in conversations that will often require you to submit some form of a technical analysis.   If you don't feel equipped to offer a good analysis you should certainly make sure that you have time to bring your technical lead into the discussion, however you'll likely see that if you needed to do this all the time you really would create a lot of randomization for your tech lead, and so part of taking care of your people is making sure that your expertise is sufficient to handle these types of situations.

This is also important because in your role as the manager of a team while you are not implementing the work you do have a responsibility ***to be reviewing the work***.   How much you choose to review, and how deeply you go into that review is largely up to you.  But you'll certainly want to establish enough technical expertise around the problem domain to ask important questions around value, complexity, and other kinds of things for the work that your team will be doing.

[ Slide – Mentoring Culture ]

Moving on from the technical leads expertise conversation let's talk about another important skill that your tech leads must have and that is their ability to mentor junior members of your team.

I'm simply going to tell a story here that actually really framed the way that I think about this that happened about two years ago.  I had a Senior member on my team who was, very much, the subject matter expert.  I felt I had a good technical understanding but this Senior engineer was much more knowledgeable I.   Then hired some Junior engineers onto the team and I needed my Senior to be able to train and mentor those Juniors on this technology stack.  The team operated this way for a while, and if I look back in hindsight I can see some indication that the skills transfer wasn't happening quite effectively, but at the time I didn't suspect that it was a major problem.  I just simply assumed that, since the technology space was fairly new, there was just a large learning curve that we had to be patient with.

That following quarter, I hired a staff engineer onto the team who had experience in mentoring others on the team.   This staff engineer was new to our tech stack, but was able to bring in several other techniques valuable to our stack. It was not long after the staff engineer joined that I happen to observe that Junior engineers seem to be picking up the skill sets from the Staff engineer much quicker. I decided to drill into this in my 1:1’s with the team.  I will never forget the conversation that I had with one of the Junior engineers on this topic.  They had stated that working with the Senior engineer they didn't feel like they were getting the opportunity to actually learn the skill, and this was because in pairing sessions, the senior engineer was getting closed much faster and feedback from the juniors is that they felt great they were learning so much more.

This was profound for me because I realized that the Staff engineer providing options for the mentee that would create an environment in which the mentee could describe how they felt they could learn best.  I'm pleased to say that this story has a happy ending because I was quickly able to give this feedback to the Senior, which was quite welcomely received, and once they started incorporating that technique into their own way of pairing with mentees, the skill gap was getting closed much faster and feedback from the juniors is that they felt great they were learning so much more

[ Slide – Training as Non Negotiable ]

Outside of simply relying on your tech leads and their mentoring capacity, you as the manager should also make sure that continuous learning and training is core within your engineering team.   It should be no surprise that in our industry we face the ever rapidly increasing need to keep up with advancements in technology.  If your organization does not already adhere to some form of dedicated learning time make sure that you end up ***creating a predictable schedule of time*** which allows your engineering team to update and refresh their skill set.

Even if the schedule is predictable, one of the best ways that you as a manager can care for your people is to ensure that that ***learning time is protected***.  You are certainly going to face pressure from Product, and quite likely even from your own management to increase the pace of delivery, but I would strongly recommend to make sure that learning time is treated as a non negotiable

I’ll have some resources available with this presentation that you can use to look at how other industries like Target adopted a model of 50 days of learning, as well as another approach that I found that I thought was novel which is using the “way of seven” to setup every 7th week of a cycle as an opportunity for learning and improvement

[ Slide ]

Last thing I'll touch on in this continuous improvement topic comes from Gene Kim who is one of the authors of the DevOps handbook.  He recently released a new book last year that he wrote with Dr Steven Spear called “Wiring the Winning Organization”.  In the book, they talk about several things, but two key topics they discuss is the idea of AMPLIFYING a problem and then another term they invented called SLOWIFICATION to solve for the problem.  

There's an interesting anecdote in the book about how they coined the term SLOWIFICATION, that they actually could not find a good word in the English language that reflected this concept, but they did end up ***finding a good German term*** for the core notion of “emphasizing improvement through slowing down”.

The key component behind AMPLIFICATION is that when a team encounters some form of a delivery problem it's important that leadership ***makes it known*** that they're aware of the issue.  In the book they talk about the beneficial effect this has in letting the team know that their concerns have been heard.  The next act then, is for leaders to provide ***proper amount of time and resources to fixing the problem***.    They state that it's very important that management avoid dictating direct solutions and mandating a timeline in which the problem must be solved.  Obviously the needs of the business and the specifics on a case by case basis must be factored into it, but in this book they're quite clear that many of the problems that face organizations and trying to become high performing is the inability to create time and space to be able to solve the problems effectively.

They assert that done well, when problems of this nature are solved, they will actually ***get integrated back into the organization*** in a way that has a net benefit throughout the organization.

I recommend this book for any manager was looking for a good indicators of how they can operate in a management role, especially when their teams encounter problems or blocking issues

[ Slide - Recap ]

[ Slide – Thank You ]
