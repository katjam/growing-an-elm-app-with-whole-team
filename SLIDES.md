# Growing an Elm app with the whole team
![](img/blank-team.jpg)

---

## Katja Mordaunt
![](img/neontribe-logo.png)

I like being nice & getting good stuff done.


Note:
- Developing software in small teams for over a decade with Neontribe. We build digital tools that compliment over-stretched services in the charity sector.
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
- Historically - we were developer skilled - but all from backgrounds.
- But we'd never before thought - this - what we do is too hard for anyone
- So we set off with myself and another developer with very little time here and there
- A user researcher with a maths degree who'd done a bit of coding and had lots of experience in the charity sector.
- A junior illustrator who wanted to help (recent arts graduate)
- A Storyteller / copywriter 
- FIX Might work if we do it like this? Github set up.
- FIX 5 problems common to software projects
- FIX Didn't all go swimmingly .. This is what worked well.

---

## We need beginners

- What do new team members need to know<!-- .element class="fragment" data-fragment-index="1" -->
- Check in regularly<!-- .element class="fragment" data-fragment-index="2" -->
- Set guidelines for Pull Request review<!-- .element class="fragment" data-fragment-index="3" -->
- Talk about how to talk about code<!-- .element class="fragment" data-fragment-index="4" -->



Note:
- FIX (Beginners in our teams and newcomers to our community)
- Projects will always need beginners - keep healthy fresh perspectives coming in.
- Common sense tips
- TICK: Keep minimal - what new team members need to know
- TICK: Have short converstions often
- TICK: Easier in Elm. Gives newcomers more confidence. (e.g. changes to the model, does it introduce duplication? feldman elm conf 2018, naming Ally Elm 2018, unipod strategy elm eu 2019)
- https://speakerdeck.com/izumisy/our-journey-with-the-biggest-elm-app-in-japan?slide=30
- TICK: Felienne how code sounds

+++

## Beginners welcome
- CODE: psuedo stubs<!-- .element class="fragment"-->
- CODE: debugging<!-- .element class="fragment" -->

Note:
- London Elm code night woman - "Only coding meetup that said beginners welcome"
- TICK: psuedo code and placeholders are great - with a few rules, none of that will make it to production.
- TICK: New developers and non-developers productive quickly. Why/ how Elm helps. relatedInfo == example?
- Elm framework does not get in the way - easy to set up - no millions of files to navigate round.
- Much of engineering constraints taken care of by constraints of Elm
- No more need to know how ot configure a postfix server than we do need to know how to write safe js in order to be good at our jobs (Charlie star inn)

---

## Everyone's voice 
PIC: code going in circles - output same.

Note:
- CODE: Collaboration means everything should not be in your style and the project's style should evolve
- PIC: Tom after a year - seems like all we do every day is go round in circles rewriting each other's code in our own style
- What is the value in being competative? Co-production is the opposite of heroic leadership.
- Maybe you come to the code and don't understand. Ask.

+++

## Team style not indy style

<blockquote>"You must have faith in your colleagues' competence and good intentions. Very likely the problem you perceive is an indication of tradeoffs you don't yet understand" - Rupert (Neontribe)</blockquote>

Note:
- Declarative style of Elm allows people to discover own "how". Many routes to same endpoint. Give everyone ownership of own journey - don't instruct on how, give them a framework that guides them.
- More people in the team means less burden on the individual. can be outside of core team and be there for bouncing ideas off occassionally or jump in when deadlines loom.
- Remember that sometimes things made along time ago or in a hurry (there's always a story)
- We are all capable of making mistakes

+++

## Different perspectives

- CODE: Tick / Sync model - Nick mentioned, then 2 years later elm EU games

Note:
- Everyone's voice is valid. Sometimes with less knowledge, we can point out a much simpler way. Especially if we are looking at a small part of the big picture in collaboration. More overview sometimes makes it seem more complicated than it needs to be.

---

## Language forms culture
- PIC: Labels can be confusing. "I'm not a rockstar?", "Kev the German", "Brain size of planet", "Gnome", "ninja". Team without labels is just "team"
- T18n in E1m...

Note:
- If you label something as X... people will be lazy about assigning value/ use cases to it. If you don't label, people use own experience/ imagination.
- Rockstars: veteran = learned stuff over time, bit by bit = unforgettable knowledge, baby = natural skill, self tagged = someone who doesn't know what tey don't know, boss tagged = pressure to cover gaps in knowledge / keep up appearance of deep knowledge.
- base 64, a11y, i18n - wanted to call this talk ... but pointed out no one would get the joke
- If some behaviour is totaly unacceptable, maybe there is a gentle guide way rather than a slam. We all mean well.

+++

## Elm (language and the community) encourages inclusivity & collaboration.
- Instead of "oh, no, this is too difficult for you" we'd say "sure, let me explain"

Note:
- Supportive compiler etc... mitigates fear of failure and makes us more equal (Emma Elm EU)
- Elm good language for communicating ideas to different types of "expertese" or "experience" (Jono Elm EU)
- Prototyping in paper means you don't have to "get it right" the first time. Elm has that too. Trainee never coded before, confident to let them loose. Hardly had to explain anything.
- conclusion - If the company supports, should be able within 3 months to eliminate a lot of the vocab that diminishes peoples identity junior, trainee, etc. can be developer

---

## Code for people
- "Mum you are not a computer"
- "OK, thanks google."
- PIC: schedule note

Note:
- My daughter likes to remind me that I am not a robot
- From the lists I made when I was a kid, I'm not so sure...
- But we do need to remember we are humans, not robots. Our efficiancy needs are different to theirs.
- Think about the future readers and writers of your codebase
- refactor/ review should focus on maknig easier for everyone

+++

## Send "You got this" to future us

- CODE: Functional peices are atomic<!-- .element class="fragment" -->
- CODE: Easy to read the code and see what it does<!-- .element class="fragment" -->
- CODE: Invest time in modelling your use case up front<!-- .element class="fragment" -->

Note:
- Ironically, experienced developers seem to have more trouble reading Elm than beginners
- Let's try to make them less suspicious / guarded
- Elm makes people friendsly code - good for beginners, teams + future for evey project no matter level of experience/ time.
- TICK: Someone can fix/ implement a part without knowing the whole. No hidden effects, nuances.
- TICK:No behind the scenes functional magic. More predicatble. the only magic is turning it into js.
- TICK: Noisy boiler plate not always helpful.

---

## Nature of bugs
- PIC: compare vue.js, php, react vs. Elm cards/ issues (counts?)
- CODE: syntax error in json ended up in release - manual testor visited the page. Similar error was caught at deploy with Elm... still got merged in.

+++

## Verbose can be good
- CODE: Keys file also good for copy. Anyone can edit, 1/2 way to cms - don't need the extra mapping layer
- CODE: react vs Elm vs vue vs drupal i18n - json is hard to read, database is a comlpicated abstraction to keep in sync
- CODE: Olso Elm rakuten - emoji trick for missing translations

Note:
- Translation framework turned out to be a useful step on way to branding
- CODE: Keys file also good for copy. Anyone can edit, 1/2 way to cms - don't need the extra mapping layer
- CODE: react vs Elm vs vue vs drupal i18n - json is hard to read, database is a comlpicated abstraction to keep in sync
- CODE: Olso Elm rakuten - emoji trick for missing translations

+++

## Naming stuff blah, blah, blah...

- CODE: Naming stuff is hard, refactoring in Elm is easy. Demo search replace in another language + use Keys file evolution

Note:
True - decisions are hard.
Jam study?

---

## It starts to make you happy...
Elm starts to make you happy<!-- .element class="fragment" data-fragment-index="1" -->

...sooner<!-- .element class="fragment" data-fragment-index="2" -->

PIC: joy evidence from slack/ github/ pull requests around being included and writing code.<!-- .element class="fragment" data-fragment-index="3" -->

Note:
- At Elm europe I was trying to explain to someone why I like using Elm...
- TICK: My colleague ponited out that you get happy With other languages/ frameworks too, but there is a lot more head banging and theory before we can reach the happy point.

- **Before next** raise hands if you've ever gotten upset or made someone upset - or even cry as a result of how project was going.

---

### How can we create spaces and cultures where we don't feel pressure to appear to "be the best at everything, all the time"?

Note:
- Leave you with some things we can all think about...
- Started making a list of things I want to explore about how we can work in teams better... Questions started asking myself - turn into questions.
- We are all trying to be our professional best. Give each other a break.
- People have different levels of confidence (arbitrarily determined). Why intimidate each other? Encourage everyone to speak.
- Single track hierarhies are meaningless. We all have parallel skills etc. We are building a compilation, not a tower.
- We all want to be great at something and it should not matter what that something is.
- the project lead is probably not the best at anything

+++

### How can we improve the democracy of our collaborations?

Note:
- No more those who git and those who do not - dividing lines in the teams we work in. Clients included - it's their product, share your code with your clients. The appreciate knowing a little.
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
- We all feel dumb and vulnerable sometimes. The important thing is not to box others in or judge them.
- Ignorance is a universal condition - no one knows everything.
- Within this community, at least - I am pretty certain that we all mean well - so let's listen to anyone that finds themselves next to us in this space, no matter what their journey here.
