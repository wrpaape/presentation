# OpenCyc-Jumble Saga
<sup>*Tears of a Spoon-fed Baby Dev*</sup>

## Getting Started
- OpenCyc server and KB browser
  - painless download, installation, and setup
  - very clear guidance linking beginners to the dev center and relevant tutorials/resources
- OpenCyc CycL tutorials and exercises
  - infinite resources that demonstrate the "basic assertion(s) + query on those assertion(s)" pattern
  - much like childhood piano lessons (maybe worthwhile to stick it out, but seems painful and irrelevant in the meantime)
  - **developer-minded questions remain unanswered/untouched upon completion**
- Java API
  - after completing the beginner's tutorials experience few hiccups getting the Java environment up and running
  - review the single provided "Basic Cyc Core API Use Cases" example code
  - apparent from unfamiliar references I had more reading to do
  - stuck attempting to execute the code anyway, appears OpenCyc is not compatible with the latest API suites
  - after receiving access to ResearchCyc run example code without a hitch
  - uninspired by the process (same old assert + query formula, this time in Java), begin scouring the web for use cases of OpenCyc

## Community
- no (active) centralized place for discussion
- mostly academic and/or well versed in "Ontological Development"
- most (constructive) help threads flavored:

  1. "highly"-technical (of things not immediately mentioned in the tutorials) discussion
  2. issues with setup/installation
- for better or for worse, lacking a (vocal) newblood presence

## Drawn Conclusions
1. OpenCyc is **_NOT_** Cyc
2. OpenCyc is **_NOT_** an out-of-the-box "plugin" solution
3. Prerequisites to developing a **_BASIC_** OpenCyc application:
  1. Understanding of:
	    1. ontological development
      		- knowledge representation in first-order logic
    	2. graph (RDF) data models
    	3. relational data models
    	4. object-oriented paradigms
  2. Technical know-how in:
    	1. Java Programming Language
      		- syntax and conventions
      		- IDE (NetBeans) or latest JDK + misc dependencies
      		- build tools (Apache Maven, Apache Ant)
      		- JavaFX/Swing/SwiXML GUI libraries
    	2. XML (XSL, XSD, CSS)
      		- Cyc and Java implementations
    	3. core API interface
      		- Java packages
      		- classes and their constructors/methods
    	4. Git
4. Prerequisites to developing a **_USEFUL_** OpenCyc application:
  1. Understanding of:
  		1. all of the above Piled Higher and Deeper
  		2. natural language processing
  		3. inductive and deductive reasoning, higher-order logic
  2. Technical know-how in:
  		1. misc NLP tools
  		2. other differently-structured/specialized ontologies (and the APIs/DSLs that accompany them)
  3. competent construction of the rules and assertions necessary for reasoning and inference across the OpenCyc KB
  4. secret handshake
  5. ???


## Wish I had found sooner:
1. [OpenCyc as a Database ~2009](https://web.archive.org/web/20090618141755/http://www.dapissarenko.com/resources/2005_09_30_ordus/#12)
  - easy-reading and unfortunately one-of-a-kind complete walk-through for constructing a simple app using OpenCyc with the Java API
  - developer-minded considerations and asides
2. [Guyren Howe SDRuby Podcast ~2010](http://video.sdruby.org/video/076_opencyc.m4v)
  - one-of-a-kind video demo of OpenCyc functionality beyond simple assertion/query
    	- retrieves PrettyStrings "(HotDog Dog)" from "dog"
  - "Cyc for ordinary mortals"
    	- smarter searching and classification
    	- framework for developing ontologies
  		- demo of ruby wrapper for Java API
3. [HD Video Demo of Basic KB Browser Assertion and Query](http://www.cs.indiana.edu/~vjalalib/OpenCyc.swf)
4. [OpenCyc Forums](http://sourceforge.net/p/opencyc/discussion/)
5. Misc Lectures:
  1. [Free Semantic Content: Using OpenCyc in Semantic Web Applications (~2008)](http://videolectures.net/iswc08_witbrock_fsc/)
  2. [Teaching Cyc to Fish (~2011)](https://www.youtube.com/watch?v=84B_AgyUDIU)
  3. OpenCyc Commonsense AI Tutorial (~2009)
    	1. [Part 1](https://vimeo.com/6579522)
    	2. [Part 2](https://vimeo.com/6595854)

## Would like to see:
1. application-development-oriented tutorials
2. application-development-oriented walk-throughs
3. POC demo of functionality exclusive to or best implemented by OpenCyc
4. comprehensive lists of:
	1. prerequisite tools and knowledge for:
    	1. effective employment of the KB browser
    	2. basic communication with API
    	3. effective employment of the API
    	4. development of a full-stack, knowledge-based app
   2. links to open-source OpenCyc apps
