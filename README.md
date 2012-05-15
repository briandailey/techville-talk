# BIG DATA

### Brief Bio
* name, current position, past experience
* thrown into data analytics, data science
* seeing a lot of overlap with statisticians learning Python

# Intro
* What is big data?
* How do we get it?
* How do we inspect it?
* How do we analyze it? (Asking the questions.)


### Quick Definition of Big Data
* It's big. 
* But that's not all.
* It's volume, yes.
* Velocity - incoming speed. Sometimes streaming.
* Variety - unstructured.
	* Could be how fast it's coming in
	* Or how fast it needs to be processed.
* Our Challenges
	* Variety of data.
	* Time to format (numbers, characters, lengths) was onerous
		* Especially with the amount of data we get.
			* State data releases quarterly.
			* National data sets being released year-around.
* Less often, sheer size was an issue.

### What's it's not: Big data is not magic.
* Data alone means nothing. 
* The value is in the extraction of meaning.
* To extract meaning, you have to ask the right questions.
* Still means you have to apply some level of scientific rigor.
	* Very helpful to read up on statistics.
	* I'm still doing that.	
* Build your hypothesis. Find ways to challenge it.


#### Getting Data
* Google it (filetype: csv, filetype: xls, filetype:dbf)
* Public data portals
	* data.gov
	* US Census, United Nations, World Bank
	* Published "private" data sets
* Amazon Public Data Sets (Enron data sets, etc)
* Google Public Data
* Wikipedia
* CMS, CDC
* Obviously varies based on what kind of data you're looking for.
* Ask! Especially in the "enterprise" where data is siloed. Need to communicate across departments. Researchers. FOIA.

#### "Clean Data?"
* It's like a unicorn. We would love to see one, but it hasn't happened yet.
* The good news is that you're not alone. Open source tools exist to inspect wild data in it's natural habitat.
* Case study: Enron
* 1.2m emails, .5 m attachments, 210GB total.
* You can fire up an Amazon instance w/ all the data.

# Transition - about to get technical.

#### Inspecting data
* head
* tail
* grep/ack
* Documentation, if available!
* Inspecting is for writing the code to ask the questions.
##### Tools (Medium-sized Data)
* SPSS, PSPP
* awk
* R
* pandas (demo)

##### Python - the language du jour
* Pycon 2012 had a huge data scientist contingent
* Check out talks online! pyvideos.org

# Break for Pandas Demo


#### Tools (Larger Data)
* Hadoop / Explain Map Reduce
	* Increasing level of abstraction.
	* Java
	* Pig
	* Hive
	* Pipes
	
#### mrjob
* Yelp, and how they use it to manage SEO, review spam.
* Let's use it to look @ AZ data.

# Warning - more demo.
* Arizona inpatient file, looking at facility and charges for normal newborn visits.
* Filter by year & DRG code
* Output tuple of charge & count
* In 20LOC, you can analyze a file of any size via cloud tools.

# Wrap-up
* We've talked about getting the data
* Inspecting the data
* Analyzing the data
* This used to be hard, but it's getting better.
* The sweet spot for deriving meaning from data is tech & domain expertise.
* It's a growing field.
* Start playing with tools!
	* The data is there.
	* The data is free.
	* The tools are there.
	* The tools are free.




