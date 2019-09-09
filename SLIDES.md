# Growing an Elm app with the whole team
![](img/blank-team.jpg)

---

## Katja Mordaunt
![](img/neontribe-logo.png)

I like being nice & getting good stuff done.


Note:
- Developing software in small teams for over a decade with Neontribe. We build work a lot with non-profits to build digital tools that compliment their over-stretched services.
- I've also been rasing children for a quarter of a century and dabbled in other industries.
- I've noticed some things about how people work together/ behave in groups/ treat each other & been involved in projects that break down because of communication
- Going to share some practical tips - how and why Elm helps make happier, more productive teams
- Much of talk, things you know - but important to give teams & people confidence to spend effort making a "be nice" atmosphere. Hopefully something you didn't know too!
- Besides if you already know this stuff - I'll make you feel good about what you are already doing.

---

## 2 years ago...

PIC: New project! Path to framework choice...
- back: ~~python, php, wordpress, drupal, symfony, laravel~~, 
- front: jquery, handlebars, angular, vue -> elm

Note:
- Usually projects have lead front and lead back
- No backend...
- Suspiscious of js following some jquery and angular projects
- Not confident I wouldn't make a mess
- Same time was playing with clojure and haskell and feeling like funtional was a safe / predictable space
- Someone mentioned Elm

+++

## So we're going with Elm?

PIC: haven site with some code & elm seasons

Note:
**Had some ups and downs, but we built a thing**
- Learn to trust each other's tech - and knowlegde & ability to evaluate and make choices in good faith
- Unfortunately not everyone agreed with me and we tied the project off - released and on the shelf... and most of the company forgot about it.

+++

## All happily going about our work
![](img/labelled-team.jpg)

"Is there anything anyone needs help with?" - Junior Illustrator <!-- .element class="fragment" data-fragment-index="1" -->


Note:
**See original notes here**
- **One year on - Success, now make some more**
- Translate the original & roll out some clones
- Upgrade to 19 - Manager I think we can handle the translation & upgrade
- Maybe better port the app to html/js for the clones so more people can work on it?
- Manager was thinking in terms of labels but
- I had a hunch I'd be able to rely on people in my team who didn't yet identify themselves as coders.
- TICK: Yes! There is something I need help with.

---


## Stumbling down the path together...
PIC: github?

Note:
- Historically - we were developer skilled - but all from backgrounds
- The company used to be nearly all devs filling in the non-developer jobs, recently, we've hired a few people with little to no coding experience.
- So we set off with myself and another developer with very little time here and there
- A user researcher with a maths degree who'd done a bit of coding and had lots of experience in the charity sector.
- A junior illustrator who wanted to help (recent arts graduate)
- FIX Might work if we do it like this? Github set up.
- We hit all the same problems every software project has...
- It didn't all go swimmingly .. but this is what worked well and how Holly helped me reflect on where our process could be better

---

## Beginners welcome

- What do new team members need to know<!-- .element class="fragment" data-fragment-index="1" -->
- Check in regularly<!-- .element class="fragment" data-fragment-index="2" -->
- Set guidelines for Pull Request review<!-- .element class="fragment" data-fragment-index="3" -->
- Talk about how to talk about code<!-- .element class="fragment" data-fragment-index="4" -->



Note:
- London Elm code night woman - "Only coding meetup that said beginners welcome"
- We need beginners in our community and in our teams
- Projects will always need beginners - keep healthy fresh perspectives coming in.
- Common sense tips
- TICK: Keep minimal - what new team members need to know
- TICK: Have short converstions often
- TICK: Easier in Elm. Gives newcomers more confidence. (e.g. changes to the model, does it introduce duplication? feldman elm conf 2018, naming Ally Elm 2018, unipod strategy elm eu 2019)
- https://speakerdeck.com/izumisy/our-journey-with-the-biggest-elm-app-in-japan?slide=30
- TICK: Felienne how code sounds


+++

## Brand new to coding

PIC: or text TODO

Note:
- When Holly first joined the project - no ide set up. That came later. 
- Afterall it's only text and the first few issues were editing that text.
- I even got our testing manager to submit directly to github when noticed there were no issue templates in place.
- TICK: New developers and non-developers productive quickly. Why/ how Elm helps. relatedInfo == example?
- psuedo code and placeholders are great - with a few rules, none of that will make it to production.
- Elm framework does not get in the way - easy to set up - no millions of files to navigate round.
- Much of engineering constraints taken care of by constraints of Elm
- No more need to know how ot configure a postfix server than we do need to know how to write safe js in order to be good at our jobs (Charlie star inn)

---

## Everyone's voice 
PIC: code going in circles - output same. TODO<!-- .element class="fragment" -->
Comment and code review examples<!-- .element class="fragment" -->

Note:
- Once Holly was set up - she started submitting more than just text changes.
- "because of Tom's experience, I was careful to try and let her do it her way"
- I remembered a time when another colleague had been coding for about a year - one day he said - seems like all we do every day is go round in circles rewriting each other's code in our own style
- CODE: Collaboration means everything should not be in your style and the project's style should evolve
- What is the value in being competative? Collaboration is the opposite of heroic leadership.
- TICK: Maybe you come to the code and don't understand. Ask.
- We talked about not being afraid to write more than "Looks good" + emoji in code reviews

+++

## Team style not indy style

<blockquote>"You must have faith in your colleagues' competence and good intentions. Very likely the problem you perceive is an indication of tradeoffs you don't yet understand" - Rupert (Neontribe)</blockquote>

Note:
- Declarative style of Elm allows people to discover own "how". Many routes to same endpoint. Give everyone ownership of own journey - don't instruct on how, give them a framework that guides them.
- When Holly comes back to this codebase in 6 months or a year, she'll appreciate that she had a hand in these decisions.
- More people in the team means less burden on the individual. can be outside of core team and be there for bouncing ideas off occassionally or jump in when deadlines loom.
- Remember that sometimes things made along time ago or in a hurry (there's always a story)
- We are all capable of making mistakes

+++

## Different perspectives

- CODE: Tick / Sync model - Nick mentioned, then 2 years later elm EU games

Note:
- I had a valuable learning exp with another colleague from that original Elm project.
- Because of that I am not so quick to dismiss the thoughts of newcomers to the project - no matter what their experiece.
- Everyone's voice is valid. Sometimes with less knowledge, we can point out a much simpler way. Especially if we are looking at a small part of the big picture in collaboration. More overview sometimes makes it seem more complicated than it needs to be.

---

## Language forms culture
![](img/labelled-team.jpg)

- Labels can be confusing. "I'm not a rockstar?", "Kev the German", "Brain size of planet", "Gnome", "ninja"<!-- .element class="fragment" -->
- Team without labels is just "team"<!-- .element class="fragment" -->

Note:
- If we'd stuck to thinking of Holly as an illustrator - we'd probably not have been able to deliver this project on time.
- If you label something as X... people will be lazy about assigning value/ use cases to it. If you don't label, people use own experience/ imagination.
- TICK: Rockstars: veteran = learned stuff over time, bit by bit = unforgettable knowledge, baby = natural skill, 
- labels can be put there by self or others self tagged = someone who doesn't know what they don't know, boss tagged = pressure to cover gaps in knowledge / keep up appearance of deep knowledge.
- Kids expect you to be able to do everything. So bosses who have labelled you.
- Remove? base 64, a11y, i18n - wanted to call this talk ... but pointed out no one would get the joke

+++

## Elm (language and the community) encourages inclusivity & collaboration.
- Instead of "oh, no, this is too difficult for you" we'd say "sure, let me explain"

Note:
- Supportive compiler etc... mitigates fear of failure and makes us more equal (Emma Elm EU)
- Elm good language for communicating ideas to different types of "expertese" or "experience" (Jono Elm EU)
- Prototyping in paper means you don't have to "get it right" the first time. Elm has that too. Trainee never coded before, confident to let them loose. Hardly had to explain anything.
- conclusion - If the company supports, should be able within 3 months to eliminate a lot of the vocab that diminishes peoples identity junior, trainee, etc. can be developer
- FIX - combine with Language/ culture - focus on labels and knowledge

---

## Code for people
- "Mum you are not a computer"
- "OK, thanks google."
![](img/todo.png)

Note:
- My daughter likes to remind me that I am not a robot
- From the lists I made when I was a kid, I'm not so sure...
- There were certainly times where I was talking to Holly saynig things like thats just a function, TODO more here... and then had to pause "You're not following, are you? Nope.
- We do need to remember we are humans, not robots - both when we speak to each other and when writing the code.
- Think about the future readers and writers of your codebase
- Our efficiancy needs are different to theirs.
- refactor/ review should focus on making easier for everyone
- The people matter more than the cleverness of the code.

+++

## Send "You got this" to future us

- CODE: Functional peices are atomic<!-- .element class="fragment" -->
- CODE: Easy to read the code and see what it does<!-- .element class="fragment" -->
- CODE: Invest time in modelling your use case up front<!-- .element class="fragment" -->

Note:
- It applies to all of us, not just people who are new to coding.
- If your code confuses another developer - no matter what their level of experience, consider adding comments about why you did it that way.
- Remember we don;t all have knowledge of all the domains we work in.
- Ironically, experienced developers seem to have more trouble reading Elm than beginners
- Let's try to make them less suspicious / guarded
- Elm makes people friendsly code - good for beginners, teams + future for evey project no matter level of experience/ time.
- TICK: Someone can fix/ implement a part without knowing the whole. No hidden effects, nuances.
- TICK: No behind the scenes functional magic. More predicatble. the only magic is turning it into js.
- TICK: Noisy boiler plate not always helpful. Holly didn't need to navigate through hundreds of directories with many files to find the one that mattered.

---

## Nature of bugs
- CODE: syntax error in json ended up in release
- PIC: compare vue.js, php, react vs. Elm cards/ issues (counts?)

Note:
- Holly's story is the syntax error from before editor installed.
- remember when I said it didn't matter that Holly had no ide when she started - not entirely true.
- manual testor visited the page. Similar error was caught at deploy with Elm... still got merged in.

+++

## Naming stuff blah, blah, blah...
- CODE: Naming stuff is hard, refactoring in Elm is easy. Demo search replace in another language + use Keys file evolution

Note:
True - decisions are hard.
Jam study?
- TODO - Holly's story let the names start off how they think of them and evolve naturally
- Letting Holly name stuff means I understand more about what she is thinking
- TODO - Talking about it and letitng them choose helps you nuderstand how much your colleague understands

+++

## Verbose can be good
- CODE: Keys file also good for copy. Anyone can edit, 1/2 way to cms - don't need the extra mapping layer
- CODE: react vs Elm vs vue vs drupal i18n - json is hard to read, database is a comlpicated abstraction to keep in sync

Note:
- Translation framework turned out to be a useful step on way to branding
- CODE: Keys file also good for copy. Anyone can edit, 1/2 way to cms - don't need the extra mapping layer
- CODE: react vs Elm vs vue vs drupal i18n - json is hard to read, database is a comlpicated abstraction to keep in sync
- TODO - combine wth another section? Holly's story?

---

## It starts to make you happy...
Elm starts to make you happy<!-- .element class="fragment" data-fragment-index="1" -->

...sooner<!-- .element class="fragment" data-fragment-index="2" -->

![](img/first-pr.png)<!-- .element class="fragment" data-fragment-index="3" -->

Note:
- At Elm europe I was trying to explain to someone why I like using Elm...
- TICK: My colleague ponited out that you get happy With other languages/ frameworks too, but there is a lot more head banging and theory before we can reach the happy point.
- TICK: Holly isn;t the only one feeling that joy!

- **Before next** Pretty sure every one in the room has experienced ...gotten upset or made someone upset - or even cry as a result of how project was going & how your team was communicating.
- I want to share some questions with you that I've been asking myself since I started this exploration of how we can work better in our teams
- I can't tell you what the answers are for you and your situation. But I think it's worth taking some time to think about them in the context of your own teams and projects.

---

### How can we create spaces and cultures where we don't feel pressure to appear to "be the best at everything, all the time"?

Note:
- We are all trying to be our professional best. Give each other a break.
- People have different levels of confidence (arbitrarily determined). Why intimidate each other? Encourage everyone to speak.
- Single track hierarhies are meaningless. We all have parallel skills etc. We are building a compilation, not a tower.
- We all want to be great at something and it should not matter what that something is.
- the project lead is probably not the best at anything

+++

### How can we improve the democracy of our collaborations?

Note:
- No more those who git and those who do not - dividing lines in the teams we work in.
- Clients included - it's their product, share your code with your clients. The appreciate knowing a little.
- Everyone has skills/ knowledge/ experience to bring to the table
- We should be encouraging people to try stuff and showing them how. Not pretending it's too hard.

+++

### Do labels and job roles prevent us from sharing knowledge openly?

Note:
- easy to hurt each other's feelings / judge each other's tech
- If everyone had to know everything to acheive success... nonsense, you don't need to know chemistry to bake a cake, but it might help you invent a better one.
- We don't often put user needs of devs to top priority of scoping. e.g. better install docs, less assumptions of project specific knowledge
- Why does community encourage people to hide knowledge or guard it or hide lack of knowledge/ Academic culture suffers this

+++

## What we can do as a community
- labeling each other probably doesn't help - let's stop doing it<!-- .element class="fragment" data-fragment-index="1" -->
- the variety of our knowledge is valuable - let's keep learning and sharing <!-- .element class="fragment" data-fragment-index="2" -->
- no one should feel left out - let's work on inclusivity <!-- .element class="fragment" data-fragment-index="3" -->

Note:
- TICK: We all feel dumb and vulnerable sometimes. The important thing is not to box others in or judge them.
- TICK: Ignorance is a universal condition - no one knows everything.
- TICK: Within this community, at least - I am pretty certain that we all mean well - so let's listen to anyone that finds themselves next to us in this space, no matter what their journey here.
-
- TODO add readme with links to the talks and resources mentioned.
