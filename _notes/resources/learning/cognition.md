[[--- title: cognition ---]]

## Optimal Learning Closure

### Principle

Define the ideal state to learn.

### Solution

1.  extract key features
    1.  goal
        1.  remember that the goal of the current task
        2.  fixed by a parent closure
    2.  feedback loop
        1.  results of relevant measurements
    3.  history
        1.  track changes over time
    4.  focus
        1.  restrict attention on a specific object and a limited network of concepts
        2.  know your needs [Goal, focus, attention](https://fabien.benetou.fr/Cookbook/Cognition#GoalFocusAttention) to remove them from the current task
2.  emulate those feature to build a dedicated environment
3.  note the results and improve

### Examples

-   learn Erlang directly in a code-repository
    -   goal: display the goal as the window title
    -   feedback loop: measure the distance between the distribution of the vocabulary used and the distribution from high quality Erlang programmers
    -   history: Mercurial tracks changes to code and comments
    -   focus: use `/startprogramming` in irssi to remove notifications (social aspect) yet lot messages and switch to a dedicated screen window
-   learn XXth century epistemology in a book
-   learn reading in school
-   learn a research domain in a laboratory

### Remarks

-   closure is preferred to environment in the sense that
    -   a closure can be created
    -   a closure can embed another closure
    -   relations are viewed in a hierarchical perspective, not as a network
        -   this could be an over-simplification yet provide a useful model

### See also

-   [Learning New Domain](https://fabien.benetou.fr/Cookbook/Cognition#LearningNewDomain)
-   [Seedea:Research/PhylogeneticFlowProgramming![](https://fabien.benetou.fr/innovativ.it/www/HistoricalArchives/Seedea/favicon.ico)](https://fabien.benetou.fr/innovativ.it/www/HistoricalArchives/Seedea/Research/PhylogeneticFlowProgramming)
-   [TurtlesTermitesAndTrafficJams](https://fabien.benetou.fr/ReadingNotes/TurtlesTermitesAndTrafficJams) and [Wikipedia:Constructionism (learning theory)![](https://en.wikipedia.org/favicon.ico)](https://en.wikipedia.org/wiki/Constructionism%20(learning%20theory))
-   discussion on "pocket world" with Paola at the 16/09/2010
===========================================================
## Learning New Language

### Principle

Every morning get a list of the new functions in your code repository to briefly review them to actively refresh your memory.

### Solution

1.  define a pattern for keywords
    1.  e.g W+( like "sort("
2.  parse the initial revision of the repository for all keywords
    1.  filter out very basic functions
3.  periodically extract keywords since the previously parsed revision
4.  display the list of new keywords
    1.  code snippet
    2.  link to internal notes
    3.  link to the official documentation
        1.  with examples

See [Repository:?p=.git;a=blob;f=shell_scripts/)logs_own_vocabulary![](https://fabien.benetou.fr/pub/images/repositoryshares/git-favicon.png)](http://fabien.benetou.fr/repository/?p=.git;a=blob;f=shell_scripts/logs_own_vocabulary) and [Repository:?p=.git;a=blob;f=shell_scripts/)most_used_commands![](https://fabien.benetou.fr/pub/images/repositoryshares/git-favicon.png)](http://fabien.benetou.fr/repository/?p=.git;a=blob;f=shell_scripts/most_used_commands).

### Remarks

-   basically any language based on the mastery of a large vocabulary
    -   Bash or shell history
-   if one just cram them up on a daily basis, he might recall 20% of those functions
    -   if he can review them and in a context in which he was involved
        -   he should remember not simply names but also how they relate to each other chronologically and contextually
-   the [The Language of Thought Hypothesis](http://plato.stanford.edu/entries/language-thought/) could also suggest that designing your own language (cf [Languages#MakingYourOwn](https://fabien.benetou.fr/Languages/Languages#MakingYourOwn) and [Seedea:Reseach:PhylogeneticFlowProgramming![](https://fabien.benetou.fr/innovativ.it/www/HistoricalArchives/Seedea/favicon.ico)](https://fabien.benetou.fr/innovativ.it/www/HistoricalArchives/Seedea/Reseach:PhylogeneticFlowProgramming)) could still be worth the investment

### See also

-   discussions with teacher friends
-   [Languages](https://fabien.benetou.fr/Languages/Languages)
-   [The preservation of favoured traces](http://benfry.com/traces/) by Ben Fry 2009
-   [ReadingNotes.TheCodeBook](https://fabien.benetou.fr/ReadingNotes/TheCodeBook) and cryptanalysis techniques
    -   [Wikipedia:Frequency analysis![](https://en.wikipedia.org/favicon.ico)](https://en.wikipedia.org/wiki/Frequency%20analysis)

### Inspiration

-   discovering [Mercurial](https://fabien.benetou.fr/Tools/Mercurial) and accumulating more and more command names
==========================================================

### Optimizable model per page

#### Principle

hopefully getting an entirely formalized wiki with the ability to optimize each page

#### Process

-   find for each page of the wiki a formal model of what it represents
    -   equation or an algorithm that will allow to simulate the principle in the page
        -   able to run simulations relative to the content of the page
        -   lot of models/simulations in academia about everything
    -   an optimization algorithm
        -   if none specific is found, generic one like those used in operational research
-   running optimization per page would be done according to
    -   the underlying principle of [Priority by economical system](https://fabien.benetou.fr/Cookbook/Cognition#PriorityByEconomicalSystem) meaning expected ROI

Data would be on that page or in another page of the wiki, the thing is that hopefuly it should always have the potential to improve.

#### Examples

page about my plants

-   algorithm = general plant metabolism model
-   optimization = Liebig's law
-   data = plants and resources (water+soil) quantitative description

#### Remarks

-   I already wanted to force myself to have a model/schema/formalization for each page but I didn't really got to it so far but if I can find optimization fo each, it could be a strong motivation.
-   making it an AmazonTurk task but then I would need to first do it for few pages and make clear example for turkers
-   proposed Pre-reading model and Post-reading model in [Template](https://fabien.benetou.fr/ReadingNotes/Template) but nearly never applied it
    -   months after added "consider a set of rules" too, same problem
-   consider iPython
===========================================================

### Thinking Is Technical

Thinking is idealized while, like computing, it is a very physical process. Not a simple one but still physical and thus that can be improve through processes technical too.

Example of the pen and paper, calculator, agenda, etc.

Even through social means (cf [egyptian scribs](http://www.canalacademie.com/ida5808-Les-transmissions-des-savoirs-et.html), ...).

#### See also

-   [Edsger Dijkstra - Denken Als Discipline (Discipline in Thought)](http://www.cs.utexas.edu/users/EWD/video-audio/NoorderlichtVideo.html), VPRO Television 2001
    -   "For myself, the most important thing has been **the daily discipline of neatly writing down your thoughts and what you do.**" ~6min50
    -   streaming on [Google Video mirror](http://video.google.com/videoplay?docid=-6873628658308030363)
-   [An evolution of problems and their solutions](http://www.ourp.im/PIM/Review-Utopiah), OurP.IM
    -   mostly the outline
-   [Evolution of my noteboosk](https://fabien.benetou.fr/Wiki/Wiki)
-   [Wiki#EvolutionOfMyWorkSpaces](https://fabien.benetou.fr/Wiki/Wiki#EvolutionOfMyWorkSpaces)
-   [Seedea:Xye/WhyWikis![](https://fabien.benetou.fr/innovativ.it/www/HistoricalArchives/Seedea/favicon.ico)](https://fabien.benetou.fr/innovativ.it/www/HistoricalArchives/Seedea/Xye/WhyWikis)
-   [BnF - Le labo](http://labo.bnf.fr/) lieu expérimental dédié aux nouvelles technologies de lecture et d'écriture
-   CNRS [Recherche Fondamentale](http://www.lutin-userlab.fr/recherche/) at Laboratoire des Usages en Technologies d'Information Numérique (Lutin) Userlab

#### To do

1.  add notes from my notebooks
===========================================================

### Goal, focus, attention

the absence of goal increases flexibility yes but it also increases uncertainty (which is very stressful) and provide no focus point (hard to leverage)

In the quote "Give me a lever long enough and a fulcrum on which to place it, and I shall move the world" attributed to Archimedes, in our cognitive world with knowledge worker and such, focus is your more powerful lever.

#### Goal

-   implementation at [PBES](https://fabien.benetou.fr/Fabien/PBES)
-   using [Irssi#ActivitiesAliases](https://fabien.benetou.fr/Tools/Irssi#ActivitiesAliases)

#### Remarks

-   [Greasemonkey#VirtualBlinders](https://fabien.benetou.fr/Tools/Greasemonkey#VirtualBlinders) with its multiple modes, "introspection" being the strictest, and [I:Site/UbiquitousNet![](https://fabien.benetou.fr/pub/ico_lock.png)](https://cloud.benetou.fr/wiki/Site/UbiquitousNet) are two sides of the same coin
-   probably proportional to the expected impact of CoS
    -   thus consider (evolutionary) bias that would wrongly shift the focus on a task that is not crucial

#### Metaphor

-   available CPU cycles including those hijacked by worms
    -   cf [Seedea:Utopiahanalysis/Botnets![](https://fabien.benetou.fr/innovativ.it/www/HistoricalArchives/Seedea/favicon.ico)](https://fabien.benetou.fr/innovativ.it/www/HistoricalArchives/Seedea/Utopiahanalysis/Botnets)
-   available neuron cycles including those hijacked by non-personal goals
    -   cf
-   wasted APM in

#### Key structures

-   [Wikipedia:Default network![](https://en.wikipedia.org/favicon.ico)](https://en.wikipedia.org/wiki/Default%20network) network of brain regions that are active when the individual is not focused on the outside world and the brain is at wakeful rest.
-   [Wikipedia:Dorsal attention network![](https://en.wikipedia.org/favicon.ico)](https://en.wikipedia.org/wiki/Dorsal%20attention%20network) (DAN) involved in voluntary (top-down) orienting and shows activity increases after presentation of cues indicating where, when, or to what subjects should direct their attention.
-   [Wikipedia:Ventral attention network![](https://en.wikipedia.org/favicon.ico)](https://en.wikipedia.org/wiki/Ventral%20attention%20network) (VAN) involved mostly, if not entirely, in involuntary actions.

#### See also

-   [Scholarpedia:Attention![](https://fabien.benetou.fr/pub/images/scholarpedia.ico)](http://www.scholarpedia.org/article/Attention) curated by Lawrence M. Ward
-   [Marlene Behrmann on Spatial vs. Object Based Attention](http://www.gocognitive.net/video/marlene-behrmann-spatial-vs-object-based-attention), Go Cognitive 2010
-   [Michael Posner on the Anatomy of attentional networks](http://www.gocognitive.net/video/michael-posner-anatomy-attentional-networks), Go Cognitive 2010
-   goal setting
-   filters
    -   rational ignorance
-   attention economy
-   motivation
    -   intrinsic, extrinsic
-   [Strategy Markup Language (StratML)](http://xml.gov/stratml/) XML vocabulary and schema for strategic plans.

#### References

-   [Attention Economy](http://www.goldhaber.org/) as I first discovered it by Michael Goldhaber
-   [Paying Attention to Interruption: A Human-Centered Approach](http://www.youtube.com/watch?v=_jHzbmYx-aY) by Brian Bailey, Stanford University Human-Computer Interaction Seminar (CS 547) 2007
-   [The Design of Future Things](http://www.youtube.com/watch#!v=wQmwEjL6K1U) by Don Norman, the Stanford University Human Computer Interaction Seminar (CS 547) 2007
-   “We have not yet found something that [multitaskers] are definitely better at than people who don't multitask.”
    -   [Clifford Nass interview](http://www.pbs.org/wgbh/pages/frontline/digitalnation/interviews/nass.html), FRONTLINE: Digital Nation, PBS 2009
-   [Multitasking at M.I.T.](http://www.pbs.org/wgbh/pages/frontline/digitalnation/blog/2009/12/multitasking-at-mit.html), FRONTLINE: Digital Nation, PBS 2009
===========================================================

### Reading Techniques

Import and structure

-   speed reading presentation done at [MBE01](https://fabien.benetou.fr/Events/MBE01)
-   [Yearly Overview](https://fabien.benetou.fr/Cookbook/Cognition#YearlyOverview)
-   [Private Library](https://fabien.benetou.fr/Cookbook/Cognition#PrivateLibrary)
-   [Causal Reading Tree](https://fabien.benetou.fr/Cookbook/Cognition#CausalReadingTree)
-   [my reading process visualized](http://picasaweb.google.com/utopiah/FinalizedVisualTools#5205938877525438418)
-   the tools Im using
    -   [Explore a book in 10 seconds](http://booksearch.blogspot.com/2009/06/explore-book-in-10-seconds.html) by Diego Puppin, Inside Google Books 2009
    -   for browsing
        -   [GreaseMonkey autoscroll](http://userscripts.org/scripts/show/25207)
        -   wiki note taking
        -   `Sidebar Downloads` to reduce width
    -   for PDFs
        -   auto-scroll shortcuts
        -   reflow
    -   ...

#### Remarks

-   Diminishing returns is probably why you do not want to finish that book sitting on your shelf for the last 2 months
    -   chances are that you already learn the basic concept even before reading the book, your decision to buy and start to read the book was a mere confirmation of your interest
    -   reading the first chapter refined your model
    -   the more you read the less you learn since you have already understood the basis
-   reading in 1 sitting is impossible for truly new concepts
    -   you need time to restructure your beliefs, if the concept you are currently learning through this book is reshaping them and their organization in a radical manner, you probably need time to spread this update
-   similar with fractal image compression technique
    -   MPEG/JPEG/...
    -   increasing precision

#### See also

-   [Wikipedia:Reading (process)![](https://en.wikipedia.org/favicon.ico)](https://en.wikipedia.org/wiki/Reading%20(process))
-   [Environnement numérique de lecture : instrumentation de l'activité de lecture savante sur support numérique](http://tel.archives-ouvertes.fr/tel-00347843/en/) by Erik Gebers, UTC 2008
===========================================================

### WikiBrain Mapping

Map this actively used [wiki instance](https://fabien.benetou.fr/) over a visual [brain imaging model](https://fabien.benetou.fr/Cookbook/Cognition#brainimaging_resources).

#### Objectives

1.  better understanding of the "state of the art" brain mechanisms (chronological lastly integrated brain areas, cf [Wikipedia:Developmental cognitive neuroscience![](https://en.wikipedia.org/favicon.ico)](https://en.wikipedia.org/wiki/Developmental%20cognitive%20neuroscience)) not through memorization but through usage (or simulated exploration)
2.  efficiently centralizing page to follow the [cognitive scalability principle](https://fabien.benetou.fr/Cookbook/Cognition#CognitiveScalability) and replace the automatically generated [Site.AllRecentChanges](https://fabien.benetou.fr/Site/AllRecentChanges) and the created [Fabien.LayeredModel](https://fabien.benetou.fr/Fabien/LayeredModel) (technical difficulty making it hardly usable)
3.  motivate an efficient and more systematic delegation of such mechanisms (as software)
4.  connect [Daily Exercises Feed](https://fabien.benetou.fr/Cookbook/Cognition#DailyExercisesFeed) and [Optimizable Model Per Page](https://fabien.benetou.fr/Cookbook/Cognition#OptimizableModelPerPage) whenever possible to improve the physical habits associated to the purely thereotical models associated to it or sub-part of the process
5.  directly connect healthy physical behavior and improved cognitive results
    1.  reticular activating system (RAS) and posture (cf [Health](https://fabien.benetou.fr/Content/Health) with PostureMinder)
    2.  nutrition in particular water, caffeine, fatty acids (cf [Health#Nutrition](https://fabien.benetou.fr/Content/Health#Nutrition))
6.  leverage [Concept Tree fMRI![](https://fabien.benetou.fr/innovativ.it/www/HistoricalArchives/Seedea/favicon.ico)](https://fabien.benetou.fr/innovativ.it/www/HistoricalArchives/Seedea/Content/Concepttreefmri) project to display content probabilisticaly relevant to the task at hand
    1.  display content associated with detected activated brain area

#### Process

1.  create a dedicated page
    1.  [WikiBrainMapping](https://fabien.benetou.fr/Content/WikiBrainMapping)
    2.  list the existing brain areas
        1.  [http://github.com/kanzure/brain/blob/master/human_brain.yaml](http://github.com/kanzure/brain/blob/master/human_brain.yaml)
        2.  binded to a visualization
    3.  list the existing wiki pages
    4.  create an associative table
        1.  association can be done through tag (PmWiki Categories)
        2.  use general "memory" as the default area
            1.  it is **crucial** to list all pages (as opposed to the [LayeredModel](https://fabien.benetou.fr/Fabien/LayeredModel))
        3.  the refine as much as possible
            1.  provide an incentive
        4.  [Roadmap](https://fabien.benetou.fr/Fabien/Roadmap) (in the "neo-cortex"?)
2.  integrate of external resources
    1.  previously organized through Seedea
        1.  [Services![](https://fabien.benetou.fr/innovativ.it/www/HistoricalArchives/Seedea/favicon.ico)](https://fabien.benetou.fr/innovativ.it/www/HistoricalArchives/Seedea/Seedea/Services)
        2.  [DATAmatrix![](https://fabien.benetou.fr/innovativ.it/www/HistoricalArchives/Seedea/favicon.ico)](https://fabien.benetou.fr/innovativ.it/www/HistoricalArchives/Seedea/Seedea/DATAmatrix)
        3.  [AImatrix![](https://fabien.benetou.fr/innovativ.it/www/HistoricalArchives/Seedea/favicon.ico)](https://fabien.benetou.fr/innovativ.it/www/HistoricalArchives/Seedea/Seedea/AImatrix)
        4.  [Onlineoutsourcing![](https://fabien.benetou.fr/innovativ.it/www/HistoricalArchives/Seedea/favicon.ico)](https://fabien.benetou.fr/innovativ.it/www/HistoricalArchives/Seedea/Seedea/Onlineoutsourcing)
            1.  should be already integrated thanks to [Person.Person](https://fabien.benetou.fr/Person/Person)
    2.  it can also be associated to areas related to tool usage
        1.  see [Content.KeyExperiments#MappingToolsToBody](https://fabien.benetou.fr/Content/KeyExperiments#MappingToolsToBody)
3.  visualize activity
    1.  edition (PmWiki and httpd logs) browsing (httpd logs)
    2.  see DTI visualization tools
    3.  [Website Traffic Map](http://designweenie.com/portfolio/index.php/page/140) Designweenie
4.  integrate non-content part of the wiki
    1.  modules
    2.  configuration files
5.  get reviewed by a neuroscience researcher
    1.  simple blind validation
6.  use [brain imaging techniques![](https://fabien.benetou.fr/innovativ.it/www/HistoricalArchives/Seedea/favicon.ico)](https://fabien.benetou.fr/innovativ.it/www/HistoricalArchives/Seedea/Content/Concepttreefmri#results)
    1.  to display (lens HUD or classical screen display) pages associated to the currently activated brain area(s)
    2.  [discussion with Paola](http://seedea.org/discussion_eeg_wikibrainmapping.txt) (2 Dec 09)
7.  assimilate visit paths (through trails or httpd logs) to [Wikipedia:Neural pathways![](https://en.wikipedia.org/favicon.ico)](https://en.wikipedia.org/wiki/Neural%20pathway)
    1.  example of [Wikipedia:Arcuate fasciculus![](https://en.wikipedia.org/favicon.ico)](https://en.wikipedia.org/wiki/Arcuate%20fasciculus) as described during [WatchingNotes#AGISummerSchool2009](https://fabien.benetou.fr/WatchingNotes/WatchingNotes#AGISummerSchool2009) lecture 12 by Allan Combs

#### Side note

This is entirely different from brain imaging on mind mapping :

-   Brain Imaging is the process of producing accurate picture of a physical brain, here those data are used in order to map over, not as a way to simulate.
-   Mind mapping is the process of taking notes in a structured fashion while being creative.
-   previous solutions
    -   chronology
        -   nothing
        -   entry page (add it's history)
        -   AllRecentChanges page
        -   LayeredModel
        -   WikiBrain Mapping
        -   next?
    -   review each step

Consider also non great apes brain model structures, in particular birds in particular crow and ravens, cephalopodes, dolphins and elephants.

-   distinguish patterns
    -   eventually propose an hybrid model

Study not the content but solely the organization of information and of processing components used in [ObjectsExoBrain#HardwareConfiguration](https://fabien.benetou.fr/Cookbook/ObjectsExoBrain#HardwareConfiguration) then compare to existing brain structures not through their expected usage but again, through their structural organization.

#### Remarks

-   the beauty of information stored on flexible system, it can have multidimensional categorization
    -   I can tag an information by physical context of the event, physical position of the information itself, chrnological position, relative positive to other events, etc... they don't have to be mutually exclusive.
        -   Consequently, based on the task at hand I can use any of those dimension of even combination of dimension to access that piece of information.
        -   even if I don't personally recall a piece of information by its physical position in my brain, I still think in the long run, with brain imaging progresses and because it's non-exclusive tagging, it will be useful.

Cf discussion with Klevre "Well I'd like something that organizes it the same way my brain does." and nicktick the 12/07/2010 at 09:39 on freenode/##pim

-   could corticogenesis by usage at the human and phylogeny provide a model to simplify learning brain areas and their position?
    -   see also morning [discussion with Raphael](https://cloud.benetou.fr/wiki/Person/Raphael#BanksOfTheMarneJuly2010) on the banks of the Marnes in Saint-Maur during mid-July 2010

#### See also

-   my notes on [The Wisdom Paradox](https://fabien.benetou.fr/ReadingNotes/TheWisdomParadox) by Elkhonon Golberg
-   [Organization for Human Brain Mapping](http://www.humanbrainmapping.org/) (OHBM)
-   neuroscience equivalent of KML for geography,
    -   a "NeuroML" using voxel coordinates?
        -   check [http://www.neuroml.org/](http://www.neuroml.org/)
-   datasets and visualization
    -   [Allen institute](http://www.brain-map.org/)
    -   [BrainMaps.org API](http://brainmaps.org/index.php?p=brain-maps-api)
-   the connectome initiative and the resulting connectomics field
    -   [Mapping the Structural Core of Human Cerebral Cortex](http://www.plosbiology.org/article/info:doi/10.1371/journal.pbio.0060159), PLoS Biology 2008
-   [MindModeling@Home (Beta)](http://www.mindmodeling.org/beta/) research project that uses volunteer computing for the advancement of cognitive science.
-   [ACT-R](http://act-r.psy.cmu.edu/) cognitive architecture (as Lisp functions modeled from fMRI data) from CMU
-   [Whole Brain Catalog](http://wholebraincatalog.org/) developed by a team of researchers from the UC San Diego
    -   [Whole Brain Project](http://www.wholebrainproject.org/)
-   [Wikipedia:Cognitive_architecture![](https://en.wikipedia.org/favicon.ico)](https://en.wikipedia.org/wiki/Cognitive_architecture)
    -   [Wikipedia:Category:Cognitive_architecture![](https://en.wikipedia.org/favicon.ico)](https://en.wikipedia.org/wiki/Category:Cognitive_architecture)
-   [Brain-Inspired Information Technology](http://www.springer.com/engineering/book/978-3-642-04024-5) edited by Akitoshi Hanazawa, Tsutom Miki, Keiichi Horio, Springer 2010
-   [ACT-R: ACT-R meets fMRI (2007)](http://act-r.psy.cmu.edu/publications/pubinfo.php?id=813) John R. Anderson, Yulin Qin, Dan Bothell
    -   in particular [John Robert Anderson](http://act-r.psy.cmu.edu/people/ja/ja-vita.php#pubs) at CMU knowing he is "using fMRI brain imaging to track different components of the cognitive architecture in the performance of complex tasks"
-   [Volume of Interest (VOI) Drawing with BrainMaker](http://brainimaging.waisman.wisc.edu/~oakes/spam/spam_BrainMaker.htm) by Terry Oakes
-   [BrainInfo](http://braininfo.rprc.washington.edu/) using NeuroNames Ontology, University of Washington
-   [NeuroImage - A Journal of Brain Function](http://www.elsevier.com/wps/find/journaldescription.cws_home/622925/description)
    -   vehicle for communicating important advances, using imaging and modelling techniques to study structure-function relationships in the brain.
-   [Building a Circuit-Diagram for the Brain](http://www.youtube.com/watch?v=4kRrarRR2kk) by Jennifer Raymond, Stanford University 2009
    -   [Jennifer Raymond Lab home page](http://raymondlab.stanford.edu/) mechanisms of motor learning in a simple cerebellar task.
-   [brainmap.org](http://brainmap.org/) online database of published functional neuroimaging (fMRI and PET) experiments with coordinate-based (x,y,z) activation locations in Talairach space.
-   [Wikipedia:Memory-prediction framework![](https://en.wikipedia.org/favicon.ico)](https://en.wikipedia.org/wiki/Memory-prediction%20framework) by Jeff Hawkins, 2004
    -   [Wikipedia:On Intelligence![](https://en.wikipedia.org/favicon.ico)](https://en.wikipedia.org/wiki/On%20Intelligence): How a New Understanding of the Brain will Lead to the Creation of Truly Intelligent Machines
-   [Human Brain Mapping](http://onlinelibrary.wiley.com/journal/10.1002/ISSN1097-0193/issues), Wiley
    -   first issued in 1993
===========================================================

### Causal Reading Tree

#### Problem

How can I step-back and understand what lead me to my current knowledge? A bibliography is a similar tool for the writer but for the reader, it's harder to backtrack what lead you to read a book or another.

#### Process

-   generate it using
    -   internal links in the Motivation section in every [ReadingNotes](https://fabien.benetou.fr/ReadingNotes/ReadingNotes)
    -   chronological list of my past read items in [PersonalInformationStream](https://fabien.benetou.fr/Content/PersonalInformationStream)
    -   add suggestions, cf [ToDo section in Seedea Bibliography![](https://fabien.benetou.fr/innovativ.it/www/HistoricalArchives/Seedea/favicon.ico)](https://fabien.benetou.fr/innovativ.it/www/HistoricalArchives/Seedea/Research/Bibliography#ToDo)
-   obtaining
    -   chronological animation of the generated causal tree
        -   so that one can see it unfold moment by moment
        -   visually distinguish the topic, associate a color by category (tags)
        -   output to GraphViz code, embed as PmGraphViz
        -   link each book to its [ReadingNotes](https://fabien.benetou.fr/ReadingNotes/ReadingNotes) page

#### Example

See progresses in [Processing#ProcessingJS](https://fabien.benetou.fr/Tools/Processing#ProcessingJS) resulting in a visualization of network of book in [ReadingNotes#Visualization](https://fabien.benetou.fr/ReadingNotes/ReadingNotes#Visualization).

-   bookA (lead to read) bookB (lead to read) bookC and bookD
-   bookA and bookC (lead to read) bookE

![PmGraphViz](https://fabien.benetou.fr/pub/pmgraphviz/pmgv-669e174b3fdc5a41b5c129efc8842341.png)

[Example of animation](https://fabien.benetou.fr/Cognition/CausalReadingTree#AnimationExample)

_Back to the [Menu](https://fabien.benetou.fr/Cookbook/Cognition#menu)_

### Private Library

#### Problem

[PersonalInformationStream](https://fabien.benetou.fr/Content/PersonalInformationStream) provides no link to my local files (or upload of them) as link to content implies giving an URL to the files thus uploading delay, copyrights issues, etc...

#### Process

1.  gives an URL to your collection
    1.  edit /etc/httpd
    2.  127.0.0.1
        1.  no upload and copyright problem
    3.  remote server
        1.  .htaccess required
2.  update [InterMap](https://fabien.benetou.fr/PmWiki/InterMap) of the wiki with the URL
3.  links page `[[MyLibrary:book_name.pdf#page=99]]`
    1.  [http://partners.adobe.com/public/developer/en/acrobat/PDFOpenParameters.pdf](http://partners.adobe.com/public/developer/en/acrobat/PDFOpenParameters.pdf)

#### Example

`[[MyLibrary:the Future of Ideas - Lawrence Lessig.pdf#page=10]]`[page10](https://cloud.benetou.fr/MyLibrary/the%20Future%20of%20Ideas%20-%20Lawrence%20Lessig.pdf#page=10) [search on "test"](https://cloud.benetou.fr/MyLibrary/the%20Future%20of%20Ideas%20-%20Lawrence%20Lessig.pdf#search=test)

#### To do

-   Shared libraries
    -   1 online server, each InterMap pointing to it
        -   check protection mechanism (cf [lighttpd directory password](http://www.cyberciti.biz/tips/lighttpd-setup-a-password-protected-directory-directories.html))
    -   distributed each InterMap pointing locally
        -   check simple mirroring mechanism, cvs-style
-   print
    -   "Locate nearby [Book Printer](http://www.engadget.com/2009/09/24/video-espresso-book-machine-now-serving-3-6-million-books-than/#continued)"
        -   use an international index of such printers and your location
        -   if nothing nearby, send to [Lulu](http://www.lulu.com/)
    -   "Print Book" and send your PDF to it

_Back to the [Menu](https://fabien.benetou.fr/Cookbook/Cognition#menu)_

### Education Self-Update

-   list the institutional books I have studied (from kindergarden to engineering school)
    -   find the notions that have since then been proven wrong
        -   highlight the new paradigms
            -   eventually generalize the result and make it a wiki to faciliate "getting up-to-date"
    -   mine the french Education National archive
        -   [Outils de documentation, d'information](http://www.education.gouv.fr/pid12/outils-de-documentation-d-information.html) from the Ministère de l'Education Nationale
        -   [Centre national de documentation pédagogique (CNDP)](http://www.sceren.fr/)
        -   get each year official program on content
            -   import user data from Copain d'Avant or similar websites
        -   generate the equivalent of a diff (or Wiki History page)
        -   compare each to the current situation here and abroad
        -   repeat for methodologies
    -   do this in collaboration with teacher friends, being teacher then or new teacher now
        -   Alain Burlot (physique-chimie)
        -   Mme Carre (allemand)
        -   Mme Buhard (francais)
        -   Claude Herviou (francais)
        -   Emilie Tanguy (general)
            -   cf paper notes
        -   Raphael Sonnier (general)
        -   Matthieu Herviou (mathematique)
        -   Frederic
            -   cf [11/09/09 discussion](https://fabien.benetou.fr//pub/conversations/discussion-with-Frederic.txt)
    -   schools should provide such a tool in them and when one leaves them
        -   it would also impair the rote learning paradigm
    -   [Institut National de Recherche Pédagogique (INRP)](http://www.inrp.fr/)
        -   [Musée national de l'Education](http://www.inrp.fr/musee/)
        -   [Programme Apprentissages, curriculum, didactiques (ACD)](http://www.inrp.fr/inrp/recherche/programmes/Apprentissages%20curriculum%20didactiques%20/programme-apprentissages-curriculum-didactiques-acd)
-   read a recent thesis a day each time from different domain
    -   locate RSS feeds for each key labs
        -   see also [SCImago Research Group](http://www.scimago.es/) esearch group dedicated to information analysis, representation and retrieval by means of visualisation techniques.
    -   pick daily a lab (cycling through them)
        -   choose the latest most acclaimed onebased on popularity

_Back to the [Menu](https://fabien.benetou.fr/Cookbook/Cognition#menu)_

### Daily Exercises Feed

Currently partly implemented as [ImprovingPIM#PIMBasedExercises](https://fabien.benetou.fr/MemoryRecalls/ImprovingPIM#PIMBasedExercises).

-   generate daily exercises feed
    -   based on the different wiki pages
        -   generated with [OurPIM:MembersProposals#TopicRevision](https://ourpim.benetou.fr/MembersProposals#TopicRevision)
    -   global repostory of exercises in a specific format by data type or domain
        -   periodically contributed by peer reviewed papers on education
        -   provide an API to pull the exercise form (as a template) and add content from other sources
    -   to finally provide
        -   generated exercises to be embedded (in a wiki, a feed reader, a link, ...)
        -   then every morning I would have an RSS feed with randomly picked exercises adapted to the content I want to learn (instead of always the same type, forcing me to be focused)
        -   feedback mechanism regarding exercises efficiency (eventually uniquely based on tests)
    -   a kind of WikiExercises to mashup content from Wikiversity/Wikibooks and other sources
        -   Dana Foundation [Cognitive Fitness at Work](http://www.dana.org/danaalliances/programs/cognitivefitness/)
        -   [Wikiversity list of quizzes](http://en.wikiversity.org/wiki/Category:Quizzes) ([with its help](http://en.wikiversity.org/wiki/Help:Quiz))
        -   extracting the exercises from FOSS e-Learning tools
        -   [Free Puzzle Collections](http://www.freepuzzles.com/)
        -   [Educational Games](http://nobelprize.org/educational_games/) on NobelPrize.org
        -   no existing dedicated semantic wiki according to [semanticweb.org listing](http://semanticweb.org/wiki/Semantic_wiki#Existing_Semantic_Wikis) and #semanticmediawiki on freenode
    -   including based on previously read books
-   [Topicmarks](http://topicmarks.com/info/features) upcoming feature "Answer quiz questions about the text"

[Seedea:Seedea.SandIdeabox#wikiasalearningtool![](https://fabien.benetou.fr/innovativ.it/www/HistoricalArchives/Seedea/favicon.ico)](https://fabien.benetou.fr/innovativ.it/www/HistoricalArchives/Seedea/Seedea.SandIdeabox#wikiasalearningtool)

#### Examples of wiki-based exercises

-   is word X from page A, B, C or D?
-   does page A contains word X, Y or Z?
-   is page A linked to page B?
-   what is the correct order for pages A, B and C on descending criteria i A>B>C? A>C>B? B>C>A? B>A>C? C>B>A? C>A>B?
    -   i e.g. size, frequency update, last edition, ...
-   which of those page corresponds the updates visualization V, A, B or C?

Score would the be based on accuracy, number of answers and time required. It would be kept over time and tracking which questions one does fail the most at. Batches of questions would initially be of the same number but gradually updated to reflect the most frequently failed question.

#### See also

-   [Lumosity](http://www.lumosity.com/) Brain Games & Brain Training by Lumos Labs
-   [http://quiz.thefullwiki.org](http://quiz.thefullwiki.org/)
-   [Discussion:freenode/randiter.log![](https://fabien.benetou.fr/pub/illustrations/chat_bubbles.jpg)](https://cloud.benetou.fr/discussions/freenode/randiter.log) the 25th of June 2011 at ~10AM

#### References

-   [No gain from brain training : Computerized mental workouts don't boost mental skills, study claims](http://www.nature.com/news/2010/100420/full/4641111a.html), Nature News April 2010
    -   Putting brain training to the test by Owen, A. M. et al. Nature advance online publication [doi:10.1038/nature09042](http://dx.doi.org/10.1038/nature09042) (20 April 2010)
    -   [Learning science : Actively recalling information from memory beats elaborate study methods](https://fabien.benetou.fr/PersonalInformationStream/WithoutNotesJanuary11#ActivelyRecalling), ScienceDaily January 2011
        -   hence the importance of "table exercise" with **no** access to studied material, forcing to retrieve rather than reread

_Back to the [Menu](https://fabien.benetou.fr/Cookbook/Cognition#menu)_

### Thinking about thinking

Thinking is the process that extract information by transforming a probabilty distribution to another distribution using energy.

More classicly, your brain is an engine executing a process that updates its own neural configuration (a topology of weights) based on newly perceived information (external to itself) using energy acquired by digestion.

#### Discussions

-   [discussion with Dira](https://fabien.benetou.fr//pub/conversations/thinkingdefinedwithdira1.log) with focus on matrices, 25th of September 2009
-   [discussion with Dira](https://fabien.benetou.fr//pub/conversations/thinkingdefinedwithdira2.log) focusing on language, 25th of September 2009
-   [discussion with Paola](https://fabien.benetou.fr//pub/conversations/thinkingredefinedwithpaola.log) clarifying "distribution of what" and source thought process, 25th of September 2009
-   [discussion with Koganei](https://fabien.benetou.fr//pub/conversations/distributedthinkingserialization.txt) regarding distributed vs serialized thinking process (based on language) 17th of December 2009
-   [discussion with X](https://fabien.benetou.fr//pub/conversations/decisiontheoryanddistributions.txt) regarding decision theory, its Street walker dilemma and expertise in IT, 18th of April 2010

#### Resulting questions

-   What are the implication of such a framework
    -   for software?
        -   self-updating ANN (or other ML techniques)? cf log1 with Dira
    -   for learning?
-   How can it be tested?
-   Is the brain a large chemical manifold self-updating?
    -   in the same way that the gecko can use quantum scale physical effect, is the brain leveraging quantum scaled dynamics in order to make thinking an efficient process?
    -   see [Towards a Mathematical Theory of Cortical Micro-circuits](http://www.ploscompbiol.org/article/info:doi/10.1371/journal.pcbi.1000532), Numenta, PLoS Computational Biology October 2009
-   can we expend to a "social manifold"?
    -   based on "joint attention is paradigmatically a distributed cognitive act. " (p153) Chapter [8 The Ontogeny and Phylogeny of Non-verbal Deixis](https://fabien.benetou.fr/ReadingNotes/ThePrehistoryOfLanguage#Chapter8) of The Prehistory Of Language
    -   and the encompassing "Social Brain Hypothesis" also used in Institute of Cognitive and Evolutionary Anthropology, Oxford University
    -   can we expend this "social manifold" to tools too?
        -   including thus not just a network of biological neural networks (NN) but also Artificial ones (ANN) and thus forming an even more encompassing manifold?
        -   see [discussion with Paola](https://fabien.benetou.fr//pub/conversations/thinkingredefinedwithpaola_social.log) clarifying "networked statistical distribution", 18th of October 2009

#### See also

-   [Seedea:CoEvolution/HistoryIdeaManagement#CognitiveArcheology![](https://fabien.benetou.fr/innovativ.it/www/HistoricalArchives/Seedea/favicon.ico)](https://fabien.benetou.fr/innovativ.it/www/HistoricalArchives/Seedea/CoEvolution/HistoryIdeaManagement#CognitiveArcheology)
    -   evolution from fixed systems (bones) to gears (Antikythera mechanism) then wiring (early computers) then FPGA then pure software on generic CPUs
-   Artificial Intelligence in which most techniques are based on statistics
-   the scientific method which rely heavily on coorelation to deduce potential causation, statistical tests, regression analysis, ...
-   Information Geometry in which the concept of manifolds is central
-   my page [Cognitive Drag](https://fabien.benetou.fr/Content/CognitiveDrag) which goal is to minimize inefficiency in the thinking process
-   [Ray Solomonoff](http://en.wikipedia.org/wiki/Solomonoff) and his Universal Distribution
    -   The Universal Distribution and Machine Learning in [Publications of Ray Solomonoff](http://world.std.com/~rjs/pubs.html) (2003)
-   [The Streetwalker's Dilemma: A Job Shop Modelby](http://www.jstor.org/pss/2099954) Steven A. Lippman and Sheldon M. Ross, SIAM Journal on Applied Mathematics, Vol. 20, No. 3 (May, 1971), pp. 336-342
-   [HplusSummitHarvard#NoahGoodman](https://fabien.benetou.fr/Events/HplusSummitHarvard#NoahGoodman) on Probabilistic Lambda-calculus
    -   [http://projects.csail.mit.edu/church/wiki/Probabilistic_Models_of_Cognition_Tutorial](http://projects.csail.mit.edu/church/wiki/Probabilistic_Models_of_Cognition_Tutorial)
-   [Information Geometry on Hierarchy of Probability Distributions](http://people.csail.mit.edu/jrennie/trg/papers/amari-ig-hierarchy-01.pdf) by Shun-ichi Amari, 2001
-   consider [Wikipedia:Kullback–Leibler divergence![](https://en.wikipedia.org/favicon.ico)](https://en.wikipedia.org/wiki/Kullback%96Leibler%20divergence) (aka information divergence, information gain, relative entropy or KLIC and notated `||`) discovered for definition of Φ in [WithoutNotesMay11#IITManifesto](https://fabien.benetou.fr/PersonalInformationStream/WithoutNotesMay11#IITManifesto)
    -   could it be consider as a Munz's mapping (a la [PhilosophicalDarwinism](https://fabien.benetou.fr/ReadingNotes/PhilosophicalDarwinism)) of the environment?
-   [Seedea:Content/Newconcepts#InformationGeometry![](https://fabien.benetou.fr/innovativ.it/www/HistoricalArchives/Seedea/favicon.ico)](https://fabien.benetou.fr/innovativ.it/www/HistoricalArchives/Seedea/Content/Newconcepts#InformationGeometry)