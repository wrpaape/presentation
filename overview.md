Baby's First Knowledge-Based App

1. Opening Experience
  - opencyc projects
    1. CyN (2004 - present)
      - Natural language chat bot development system
      - example dialogue

		```
		Is a human a mammal ?
		
		Affarmitive. I agree.
		
		is a dog a vegetable ?
		
		Nope. I can't prove that.
		```
		
		```
		<kinoc2> explain why car is not plant
		<Cyn> "car" is a kind of "motor vehicle" . "motor vehicle"
		is a kind of "land vehicle" . "land vehicle" is a kind of
		"transportation device" . "transportation device" is disjoint
		with "naturally-occurring substance" . "plant material" is a
		kind of "naturally-occurring substance" . "plant" is a kind of
		"plant material" .
		```

		2. NorthWestern Qualitative Research Group
			- We think that these KB contents are a valuable resource for the AI research community.
			- ... **we use our own reasoning engine, running with knowledge extracted semi-automatically** from a Cyc KB
			- misc Academic Publications
		
		3. RoboHow

![overview](https://robohow.eu/_media/project/approach/overview-pancakes.png)

>Robohow is a four-year European research project that started in February 2012. It aims at enabling robots to competently perform everyday human-scale manipulation activities - both in human working and living environments. In order to achieve this goal, Robohow pursues a knowledge-enabled and plan-based approach to robot programming and control. The vision of the project is that of a cognitive robot that autonomously performs complex everyday manipulation tasks and extends its repertoire of such by acquiring new skills using web-enabled and experience-based learning as well as by observing humans.

			
	4.[Dutch Masters Report(2003)](http://wwwhome.portavita.nl/~yeb/d-opdracht/afstudverslag.pdf)

	5. Alchemy API

	6. [(choppy) Michael Witbrock lecture](http://videolectures.net/iswc08_witbrock_fsc/)
		- logistics reasoning
			- instead of spending ~1 year developing own logistics ontology in RDF, opencyc
			- "richly represented"
			- point of large, broad ontologies? Can build more focused ontologies much quicker
				- intelligent search app (semantic search results for heart valve repair/tricuspid valve surgery)
		- true question answering
		- all of opencyc is representable in OWL
		- wiki => people, OpenCyc => computers

	7. [teaching Cyc to Fish](https://www.youtube.com/watch?v=84B_AgyUDIU)

	8. [video demo of basic assertion and query](http://www.cs.indiana.edu/~vjalalib/OpenCyc.swf)

	9. [Guyren Howe sdruby podcast ~2010](http://video.sdruby.org/video/076_opencyc.m4v)
		- used for classifying things
		- processing natural language
		- 1967, 1984, the AI winter, the founding of Cyc
		- onotology: formal language/representation for stating facts about a domain
		- opencyc - all of the concepts, but none of the rules
			- the world's largest well-organized ontology
		- demo (computer freezing intermittently, 4GB RAM)
		- **jruby demo**
		- how to run on mac
		- NLP
			- **getDenotsOfString**
			- of "dog"? => HotDog and Dog
			- help users find things they don't enter explicitly
			- 1st live demonstration of practical use case
			- "Cyc for ordinary mortals" slide
				- search/classification
				- developing ontologies
				- disambiguation
				- knowledge store
				- prototyping
			- 2010, "at the point where there's enough stuff in it that I believe people will start to do stuff with it"
			- it's still hard, pushing the envelope with this stuff
			- although classification, smarter search more feasible
			- maybe in another 25 years we'll be getting close
			- it's interesting to play with, and it may be useful, already

	
	10. [cycfoundation.org (dead)](http://cycfoundation.org/)
		- links to interesting resources
		- presentations, demos
		- using cyc hierarchy to suggest conceptually related wiki articles to "dog" that aren't present in the article



	9. Watson (?)

	10. various 

------
  

2. Getting Started Experience

[web archive](https://web.archive.org/web/20090618141755/http://www.dapissarenko.com/resources/2005_09_30_ordus/)


3. Community

>creamyhorror 1250 days ago

>I looked at OpenCyc previously while investigating semantic networks, but not long enough to figure out how to do things with it. I'd be interested in hearing about what any of you have used it for. A map of English knowledge and relations between concepts ought to be pretty useful for some things.

	
>DavidPlumpton 1250 days ago

>Looking into Cyc I infer the following...
Q: So what is Cyc used for? A: You could use it for games Q: Has it been used for a game? A: No

>gojomo 1250 days ago

>Is there any public demo using OpenCyc that does something resembling anything?

>Chris Rose 2010-04-11

>After spending a few hours learning OpenCyc's unintuitive interface I find that it can't verify idiot level assertions like is-a Dog Animal.  I got the ugly syntax correct, the xface gave me links to each of the 3 elements.  Could the problem be the "low memory situation" error message - completely undocumented - that I get even though I have 4 GB RAM for Win32?   Regardless of my freeing memory, the RAM OpenCyc finds tops out at 1GB.  I am seriously unimpressed.

>Jeryl Cook

>I occasionally get emails on OpenCyc hoping that this tool would mature over time..i attempted to use this 2 year ago(Java) and it was unimpressive as well so i had to find another 'solution'(commercial) to handle my business case….
OpenCyc needs to be shut down(perhaps another team should take it over?) , and the wiki page(http://en.wikipedia.org/wiki/Cyc) updated to state that the system is USELESS  because TIME IS MONEY, developers spend hours trying to get the stupid thing up and running to find that it it works worst than a grad students project  that was built to just pass a course and the API is horrific.

[video tutorials](http://www.cs.indiana.edu/~vjalalib/OpenCyc.swf)



- OpenCyc Commonsense AI Tutorial (down until recently)
	- 2 part, 1 hour presentation by Stephen Reed
	- 2009
	- uses browser for basic assertions/queries

			(#$and 
				(#$genls ?X #$TransportationDevice) 
				(#$isa ?X #$MilitaryWeaponType))

	
	- mentions no rules in opencyc, can't backchain, with researchcyc, conclude something is a transportation device (prove it)
	
	>At some point in AGI development, it will be useful to incorporate OpenCyc content
	
	>OpenCyc’s inference engine and object store are not free software

	
- hidden sourceforge forums



-SHRDLU
>Person: Pick up a big red block.
>Computer: OK.
>Person: Grasp the pyramid.
>Computer: I DON'T UNDERSTAND WHICH PYRAMID YOU MEAN.
>Person (changing their mind): Find a block which is taller than the one you are holding and put it into the box.
>Computer: BY "IT", I ASSUME YOU MEAN THE BLOCK WHICH IS TALLER THAN THE ONE I AM HOLDING.
>Computer: OK.
>Person: What does the box contain?
>Computer: THE BLUE PYRAMID AND THE BLUE BLOCK.
>Person: What is the pyramid supported by?
>Computer: THE BOX.
>Person: How many blocks are not in the box?
>Computer: FOUR OF THEM.
>Person: Is at least one of them narrower than the one which i told you to pick up?
>Computer: YES, THE RED CUBE.
>Person: Is it supported?
>Computer: YES, BY THE TABLE.
>Person: Can the table pick up blocks?
>Computer: NO.
>Person: Can a pyramid be supported by a block?
>Computer: YES.
>Person: Can a pyramid support a pyramid?
>Computer: I DON'T KNOW.
>Person: Stack up two pyramids.
>Computer: I CAN'T.
>Person: Will you please stack up both of the red blocks and either a green cube or a pyramid?
>Computer: OK.
>Person: Which cube is sitting on the table?
>Computer: THE LARGE GREEN ONE WHICH SUPPORTS THE RED PYRAMID.
>Person: Is there a large block behind a pyramid?
>Computer: YES, THREE OF THEM: A LARGE RED ONE, A LARGE GREEN CUBE, AND THE BLUE ONE.
>Person: Put a small one onto the green cube which supports a pyramid.
>Computer: OK.
>Person: Put the littlest pyramid on top of it.
>Computer: OK.
>Person: Does the shortest thing the tallest pyramid's support supports support anything green?
>Computer: YES, THE GREEN PYRAMID.
>Person: What color is it?
>Computer: BY "IT", I ASSUME YOU MEAN THE SHORTEST THING THE TALLEST PYRAMID'S SUPPORT SUPPORTS.
>Computer: RED
>Person: How many things are on top of green cubes?
>Computer: I'M NOT SURE WHAT YOU MEAN BY "ON TOP OF "IN THE PHRASE "ON TOP OF GREEN CUBES " .
>DO YOU MEAN:
>1 - DIRECTLY ON THE SURFACE
>2 - ANWHERE ON TOP OF ?
>Person: 2
>Computer: THREE OF THEM.
>Person: Had you touched any pyramid before you put the green one on the little cube?
>Computer: YES, THE GREEN ONE.
>Person: When did you pick it up?
>Computer: WHILE I WAS STACKING UP THE RED CUBE, A LARGE RED BLOCK AND A LARGE GREEN CUBE.
>Person: Why?
>Computer: TO GET RID OF IT.
>Person: Why did you do that?
>Computer: TO CLEAN OFF THE RED CUBE.
>Person: Why did you clear off that cube?
>Computer: TO PUT IT ON A LARGE GREEN CUBE.
>Person: Why did you do that?
>Computer: TO STACK UP THE RED CUBE , A LARGE RED BLOCK AND A LARGE GREEN CUBE.
>Person: Why did you do that?
>Computer: BECAUSE YOU ASKED ME TO.
>Person: How did you do it?
>Computer: BY PUTTING A LARGE RED BLOCK ON THE TABLE ; THEN LETTING GO OF IT ; THEN PUTTING A LARGE GREEN CUBE ON IT ; THEN LETTING GO OF THAT CUBE ; THEN PUTTING THE RED CUBE ON THAT CUBE; THEN LETTING GO OF THAT CUBE.
>Person: How many objects did you touch while you were doing it?
>Computer: FOUR OF THEM.
>Person: What did the red cube support before you started to clean it off?
>Computer: THE GREEN PYRAMID.
>Person: There were five blocks to the left of the box then.
>Computer: NO, ONLY FOUR OF THEM: THE RED CUBE, TWO LARGE GREEN CUBES AND A LARGE RED BLOCK.
>Person: Put the blue pyramid on the block in the box.
>Computer: OK.
>Person: Is there anything which is bigger than every pyramid but is not as wide as the thing that supports it?
>Computer: YES, THE BLUE BLOCK.
>Person: Does a steeple
>Computer (interrupting): SORRY, I DON'T KNOW THE WORD "STEEPLE".
>Person: A "steeple" is a stack which contains two green cubes and a pyramid.
>Computer: I UNDERSTAND.
>Person: Are there any steeples now?
>Computer: NO.
>Person: Build one.
>Computer: OK.
>Person: Call the biggest block "superblock".
>Computer: OK.
>Person: Have you picked superblock up since we began?
>Computer: YES.
>Person: Why did you drop it?
>Computer: BY "IT", I ASSUME YOU MEAN THE SUPERBLOCK.
>I CAN'T EXPLAIN A NON-EXISTENT EVENT.
>Person: Is there anything to the right of the red pyramid?
>Computer: YES, FOUR THINGS: THE BOX , THE RED CUBE, THE BLUE PYRAMID AND THE BLOCK NAMED SUPERBLOCK
>Person: Thank you.
>Computer: YOU'RE WELCOME!

----
	
- unknowns
- java and friends (jdk, ide, builders, downloads, updates)
- natural language processing
- RDF, OWL, SPARQL
- http://sourceforge.net/p/opencyc/discussion/85727/
- live demonstration, walkthrough, I will demonstrate to you how to do something quicker/more efficiently/easier/better than something you know how to do

- [ruby on rails tech demo ~2005](https://www.youtube.com/watch?v=Gzj723LkRJY)
	- "Woops! It worked."
	- "Look at all the things I'm not doing, look at all the configuration I'm not writing!"
	- 0 to functioning blog app in 15 mins

- [easy translate gem](https://github.com/seejohnrun/easy_translate)
	
	request free trial (make new gmail account)

	generate api key (click button)
	> your API key is: 'xxxxx'
	
	enable google translate api (click button)

	gem install easy_translate (terminal command)

	can now translate 15 million characters of text (up to 2 million/day)

	irb

		EasyTranslate.api_key = 'xxxxx'

		EasyTranslate.translate('Hello', to: :es)
		=> "Hola"

		EasyTranslate.translate('Hola', to: :en)
		#=> "Hey there"

	- can run this line of code in my server
	- my program just learned Spanish for all I care, like Neo from the Matrix

