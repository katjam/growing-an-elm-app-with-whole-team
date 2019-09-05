# Growing an Elm app with the whole team
![](img/team-pic.png)
PIC: team non-descript but working in silos

---

## Katja Mordaunt
![](img/neontribe-logo.png)
I like being nice.


Note:
**JOURNEY to here --> why I care about leading good teams**
- Practical tips, how and why Elm helps
- Developing software in small teams for over a decade - alongside parenting
- Noticed some things about how people work together / behave in groups/ treat each other
- Involved in projects that break down because of communication
- Much of talk, things you know - but important to give teams & people confidence to spend effort making a "be nice" atmosphere. Hopefully something you didn't know too!

---

## 2 years ago...

PIC: New project! Path to framework choice...

Note:
**Set up how I got to Elm**
- Suspiscious of js following some jquery and angular projects
- Not confident I wouldn't make a mess
- Same time was playing with colojure and haskell and feeling like funtional was a safe / predictable space
- PIC: haven't looked back since. Someone mentioned Elm

+++

## So we're going with Elm?

PIC: haven site with some code & elm seasons

Note:
**Had some ups and downs, but be built a thing**
- Learn to trust each other's tech - and knowlegde
- Ability to evaluate and make choices in good faith
- Remember that sometimes things made along time ago or in a hurry (there's always a story)
- We are all capable of making mistakes
- Unfortunately not everyone agreed with me and we tied the project off - released and on the shelf.

+++

## All happily going about our work

PIC: The team with labels busy and silos (Server Gnome, Javascript Ninja, Rockstar Dev, Junior Illustrator)

"Is there anything anyone needs help with?" - Junior Illustrator <!-- .element class="fragment" data-fragment-index="1" -->


Note:
**See original notes here**
- **One year on - Success, now make some more**
- Translate the original & roll out some clones
- Upgrade to 19 - Manager I think we can handle the transation & upgrade but we better port the app to js for the clones so more people can work on it
- Working with charity partners - user research took longer due to delays in comms
- Manager thinks port the app to js for the clones so more people can work on it
- Remote lead to roll out clones, no developers available - *mention labels a little*
- Yes! There is something I need help with.

---


## Stumbling down the path together...
PIC: github?

Note:
- So we set off with myself and another developer with very little time here and there
- A user researcher with a maths degree who'd done a bit of coding
- A junior illustrator who wanted to help
- Might work if we do it like this? Github set up.
- 5 problems common to software projects
- Didn't all go swimmingly .. This is what worked well.

+++

## We need beginners

- What do new team members need to know<!-- .element class="fragment" data-fragment-index="1" -->
- Check in regularly<!-- .element class="fragment" data-fragment-index="2" -->
- Set guidelines for Pull Request review<!-- .element class="fragment" data-fragment-index="3" -->


Note:
- Projects will always need beginners - keep healthy fresh perspectives coming in.
- Common sense
- TICK: Keep minimal - what new team members need to know
- TICK: Have short converstions often
- TICK: Easier in Elm. Gives newcomers more confidence. (e.g. changes to the model, does it introduce duplication? feldman elm conf 2018, naming Ally Elm 2018, unipod strategy elm eu 2019)
- https://speakerdeck.com/izumisy/our-journey-with-the-biggest-elm-app-in-japan?slide=30

+++

## Beginners welcome
- CODE: psuedo stubs
- CODE: debugging

Note:
- London Elm code night woman - "Only coding meetup that said beginners welcome"
- TICK: psuedo code and placeholders are great - with a few rules, none of that will make it to production.
- TICK: New developers and non-developers productive quickly. Why/ how Elm helps. relatedInfo == example?
- Elm framework does not get in the way - easy to set up - no millions of files to navigate round.
- Much of engineering constraints taken care of by constraints of Elm
- No more need to know how ot configure a postfix server than we do need to know how to write safe js in order to be good at our jobs (Charlie star inn)

+++

## Everyone's voice 

PIC: code going in circles - output same.

Note:
- CODE: Collaboration means everything should not be in your style and the project's style should evolve
- PIC: Tom after a year - seems like all we do every day is go round in circles rewriting each other's code in our own style
- What is the value in being competative? Co-production is the opposite of heroic leadership.)
- Maybe you come to the code and don't understand. Ask.

+++

## Team style not indy style
- Declarative style of Elm allows people to discover own "how". Many routes to same endpoint. Give everyone ownership of own journey - don;t instruct people on how, give them a framework that guides them.
- MOVE? (Remember - some things are easy for some people "Even a female baby could do that!")
- MOVE? If you label something as X... people will be lazy about assigning value/ use cases to it. If you don't label, people use own experience/ imagination.
- More people in the team means less burden on the individual. can be outside of core team and be there for bouncing ideas off occassionally or jump in when deadlines loom.
- We don't often put user needs of devs to top priority of scoping. e.g. better install docs, less assumptions of project specific knowledge

+++

## Different perspectives
- Everyone's voice is valid. Sometimes with less knowledge, we can point out a much simpler way. Especially if we are looking at a small part of the big picture in collaboration. More overview sometimes makes it seem more complicated than it needs to be.
- CODE: Tick / Sync model - Nick mentioned, then 2 years later elm EU games

+++

## Language forms culture
- Labels can be confusing. "I'm not a rockstar?", "Kev the German", "Brain size of planet", "Gnome", "ninja". Team without labels is just "team"
- Rockstars: veteran = learned stuff over time, bit by bit = unforgettable knowledge, baby = natural skill, self tagged = someone who doesn't know what tey don't know, boss tagged = pressure to cover gaps in knowledge / keep up appearabce of deep knowledge.
- Why does community encourage people to hide knowledge or guard it or hide lack of knowledge/ Academic culture suffers this
- If some behaviour is totaly unacceptable, maybe there is a gentle guide way rather than a slam. We all mean well.
- Elm encourages unclusivity / collaboration. Supportive compiler etc... mitigates fear of failure and makes us more equal (Emma Elm EU)
- Elm good language for communicating ideas to different types of "expertese" or "experience" (Jono Elm EU)
- Prototyping in paper means you don't have to "get it right" the first time. Elm has that too. Trainee never coded before, confident to let them loose. Hardly had to explain anything.
- What's better? (ref elm-lang slack ~25 Aug) "oh, no this is too difficullt for you" or "sure, let me explain"
- conclusion - If the company supports, should be able within 3 months to eliminate a lot of the vocab that diminishes peoples identity junior, trainee, etc. can be developer

+++

## Code for people
- We are humans, not robots. Our efficiancy needs are different to theirs. PIC - "Mum you are not a computer"
- Think about the future readers and writers of your codebase
- refactor/ review should focus on maknig easier for everyone
- CODE: Functional peices are atomic. Someone can fix/ implement a part without knowing the whole. No hidden effects, nuances.
- CODE: Easy to read the code and see what it does. No behind the scenes functional magic. More predicatble. the only magic is turning it into js.
- CODE: Invest time in modelling your use case up front. Noisy boiler plate not always helpful.
- experienced developers have more trouble reading Elm than beginners
- Elm makes people friendsly code - good for beginners, teams + future for evey project no matter level of experience/ time.

+++

## Nature of bugs
- PIC: compare vue.js, php, react vs. Elm cards/ issues (counts?)
- Translation framework turned out to be a useful step on way to branding
- CODE: Keys file also good for copy. Anyone can edit, 1/2 way to cms - don't need the extra mapping layer
- CODE: syntax error in json ended up in release - manual testor visited the page. Similar error was causgt at deploy with Elm... still got merged in.
- CODE: react vs Elm vs vue vs drupal i18n - json is hard to read, database is a comlpicated abstraction to keep in sync
- CODE: Olso Elm rakuten - emoji trick for missing translations
- CODE: Naming stuff is hard, refactoring in Elm is easy. Demo search replace in another language + use Keys file evolution

---

## Started to see the light...
- Posing some quesstions we can all think about... first raise hands if anyone evern cried or made someone cry as a result of how project was going.
- Started making a list of things I want to explore about how we can work in teams better... Questions started asking myself - turn into questions.
- Starts to make you happy sooner. With other languages/ frameworks, there is a lot more head banging and theory before we can reach the happy point.
- We are all trynig to be our professional best. Give each other a break. Rupert's code review tips.
- Single track hierarhies are meaningless. We all have parallel skills etc. We are building a compilatoin, not a tower.
- We all want to be great at something and it should not matter what that something is.
- If everyone had to know everything to acheive success... nonsense, you don't need to know chemistry to bake a cake, but it might help you invent a better one.
- People have different levels of confidence (arbitrarily determined). Why intimidate each other? Encourage everyone to speak.
- No more those who git and those who do not - dividing lines in the teams we work in. Clients included - it's their product, share your code with your clients. The appreciate knowing a little.
- Having an illustrator in the team has benefits - pics from HH / CA
- Everyone has skills/ knowledge/ experience to bring to the table
- Joy evidence from slack/ github/ pull requests around being included and writing code.
- I realised: All different people with different knowledge, interests and levels of experience
- easy to hurt each other's feelings / judge each other's tech
- base 64, a11y, i18n
- the project lead is probably not the best at anything
- Together we can build a thing, right?

Note:
- Starts to make you happy... sooner

+++

## What we can do as a community
- labeling each other doesn't help - let's stop doing it<!-- .element class="fragment" data-fragment-index="1" -->
- the variety of our knowledge is valuable - let's keep learning and sharing <!-- .element class="fragment" data-fragment-index="2" -->
- no one should feel left out - let's work on inclusivity <!-- .element class="fragment" data-fragment-index="3" -->

Note:
-

