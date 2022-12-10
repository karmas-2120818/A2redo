# Assignment 2: Protests
In recent years the United States has experienced a surge of protests, in support of Black Lives Matter, gender equity, and many other social or political issues.

In this assignment, you will work with data from [Count Love](https://countlove.org/), data that is ocassionally [cited](https://www.nytimes.com/2020/08/28/us/black-lives-matter-protest.html) by the _New York Times_ when reporting on US demonstrations.

Through this assignment, you will be able to answer questions about protests, including:

* What were the most attended and least attended protests in the US in the last 5 years?
* How many protests occurred in Washington state?
* How did the number of protests in 2019 compare to 2020, and why?
* Why are people protesting in the US? What are the biggest motivators?

## Learning objectives
By completing the assignment, you will develop or skills for:

- **Version control** tools for managing code (git and GitHub)
- Writing documents with **markdown** syntax
- Coding in R
- Thinking critcally about data.

# 1. Critical Analysis & Reflection: Before You Code

Before diving into this (or any) dataset, it's important to know where the data came from, and it's important to have or to seek out _domain familiarity_ — that is, knowledge about the topic of the dataset. Sometimes the topic is very narrow; more often it is expansive, as in the case of CountLove. We don't want to be "strangers in the dataset," as Catherine D'Ignazio and Lauren Klein describe it. To get more familiar, we are going to begin by doing some background reading.

**Note:** Please write your answers below under the heading "Your Responses and Reflections."

- First, please read [this FAQ](https://countlove.org/faq.html) from the CountLove website and the opening of [this blog post](https://www.tommyleung.com/countLove/index.htm).  

**(R1a)** Based on the information in these pieces, why did the creators start collecting the Count Love data? 

The creators started collecting the Count Love data because they wanted to document information about protests in 2016. 


- Next, we would like you to read this [New York Times piece that uses CountLove data](https://www.nytimes.com/interactive/2020/06/13/us/george-floyd-protests-cities-photos.html) and that describes the Black Lives Matter protests that occurred in the summer of 2020. 

**(R1b)** Please summarize the main point or argument of this article.

Count Love is trying to show protests around the United States in an interactive way so that
it is easier for people to see. They hope to bring more people to the site so that people
are interested in looking at protests can view them all at once. There are two people working on the project. 


Next, we're going to reflect about who collected this data, and what's actually inside it. 

**(R1c)** Who collected and shared the CountLove data, and what do they do for a living?

Their names are Tommy Leung and Nathan Perkins who are both engineers and scientists. 

**(R1d)** As Klein and D'Ignazio remind us, when it comes to data, "what gets counted counts." What types of demonstrations does CountLove include in their data, and what types do they exclude? 

They count public displays of protests that are not part of the regular buisiness type. They exclude awareness events, commmeoritve celebrations, historic reenactments, fundraising events, and polotical campaign rallies. 


**(R1e)** How and where does CountLove get their data about the protests? 

The data comes from news acticles for example like the New York Times. The information is credible. The developers count protests that were public and not part of private organizations. The data comes from events in the United States from 01-20-2017 all the way to 12/31/21. 


**(R1f)** How does CountLove make their estimates about the number of people who attended a protest? What potential problems might arise from this method of estimation? 

Count Love record the most conservative number from news articles that they have found. They interpret from as small as 10 to as large as 100. The problems that arise are that people aren't getting the exact number of people that attended. 


**(R1g)** What are two central values of Count Love? Name and briefly describe them. (See the Envisioning Cards for a defintion of "value".)

They are making important political data publicly available and accessible for everyone who is interested in protest data Two of their vales is that that data should both available and accessible to the gerneral public. 

**(R1h)** Name and briefly describe one direct stakeholder and one indirect stakeholder (See the Envisioning Cards)? 

One direct stakeholder is people who study protests or do research related to their topics. In order to use these skills people need to have great researching skills as well as having
knowledge in computers. Journalists and people who write newspapers could use this information as well. One Indirect stakeholder is a student. 

# 2. Coding in R: Parts 1-6
**Instructions**. Assignment instructions and prompts are in this file: [analysis.R](analysis.R).

**Coding and reflection prompts**. You will find two kinds of prompts in [analysis.R](analysis.R):

* *Coding prompts*, which prompt you to write R code in [analysis.R](analysis.R).
* *Reflection prompts*, which prompt you to think and write in English below, in this file (README.md).

**Formatting Your Responses and Reflections**.

* When formatting your written responses and reflections below, please *retain* all
reflection prompt IDs (e.g., R1a, R2a, etc.).
* Fill in the elipses (...) with your own words. 
* Remove expected word counts.
* To write clearly, use markdown code appropriately (e.g., **bold**, _italics_, and `code`). As appropriate, include images, links, and so forth.

**Questions?** As always, please post on Teams or ask your Instructor or Teaching Assistant.

:computer: Good coding!
   :writing_hand: Good critical thinking!
      :smile: Good-luck!

(_Updated: October 2022, Your Teaching Team_)

# 3. Critical Analysis & Reflection: After You Code

In the second chapter of *Data Feminism*, Klein and D'Ignazio describe 4 ways that data scientists can challenge power and take action:
> Taking action can itself take many forms, and in this chapter we offer four starting points:  
> (1) Collect: Compiling counterdata—in the face of missing data or institutional neglect—offers a powerful starting point as we see in the example of the DGEI, or in María Salguero’s femicide maps discussed in chapter 1.  
> (2) Analyze: Challenging power often requires demonstrating inequitable outcomes across groups, and new computational methods are being developed to audit opaque algorithms and hold institutions accountable.  
> (3) Imagine: We cannot only focus on inequitable outcomes, because then we will never get to the root cause of injustice. In order to truly dismantle power, we have to imagine our end point not as “fairness,” but as co-liberation.  
> (4) Teach: The identities of data scientists matter, so how might we engage and empower newcomers to the field in order to shift the demographics and cultivate the next generation of data feminists?  

**(R1h)** How does the CountLove project embody one or more of these 4 forms of challenging power? 

The Countlove project embodies Collect because they are collecting data from different sources. It is important because they are collecting data that most institutions wouldn't collect. 

**(R1i)** What is the most interesting or surprising thing you learned from this analysis? Please answer in at least 2-3 sentences (2 points)

Something that was interesting about this analysis is that Count Love took different data from places that instituions wouldn't take from because it could contain missing data. 

**(R1j)** What is a kind of analysis that you would like to do or that would be interesting to do with the CountLove data that you don't have the time or skills to accomplish at this moment? Please answer in at least 2-3 sentences (2 points)

A kind of analysis that would be intersting to do with Count Love that I don't have the time or skills for is that how protests have changed by region. It would be intersting to see how protests by region because there isn't a lot of information about it. 


## Your Responses and Reflections
### Critical Analysis & Reflection: Before You Code (questions above)

See above answers

### Part 3: Locations (`analysis.R`)

* **(R3a)** Something that surprised me about about the protests in Washington is that there are 1375 protests in WA. I'mm not surpised with how many protests there are. 

* **(R3b)**  When I applied the Sapply() function it made it quite simple and was easier to do all at once. I was shocked how simple it was to use.

* **(R3c)** Looking at at the State Table, I saw some errors with the States. Some of the names were all, lowercase and it was really weird to look at. There were also weird duplicates of them which made it even stranger.  

### Critical Analysis & Reflection: After You Code (questions above)

see above answers
