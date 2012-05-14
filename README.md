# BIG DATA

### Brief Bio
* name, current position, past experience
* thrown into data analytics, data science
* seeing a lot of overlap with statisticians learning Python

### Quick Definition of Big Data
* It's big. 
* But that's not all.
* It's volume, yes.
* Velocity - incoming speed. Sometimes streaming.
* Variety - unstructured.
	* Could be how fast it's coming in
	* Or how fast it needs to be processed.

### Big data is not magic.
* Data alone means nothing. 
* The value is in the extraction of meaning.
* To extract meaning, you have to ask the right questions.
* Still means you have to apply some level of scientific rigor.
	* Very helpful to read up on statistics.
	* I'm still doing that.	
* Build your hypothesis. Find ways to challenge it.

### Our Challenges

* Variety of data.
* Time to format (numbers, characters, lengths) was onerous
	* Especially with the amount of data we get.
		* State data releases quarterly.
		* National data sets being released year-around.
* Needed to QA data to ask "What's interesting here?"
* We have backgrounds more in SQL.
	* Great, how do I GROUP BY?
* Less often, sheer size was an issue.

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
* Ask! Especially in the "enterprise" where data is siloed. Need to communicate across departments.

#### "Clean Data?"
* It's like a unicorn. We would love to see one, but it hasn't happened yet.
* The good news is that you're not alone. Open source tools exist to inspect wild data in it's natural habitat.
* Case study: Enron
* 1.2m emails, .5 m attachments, 210GB total.
* You can fire up an Amazon instance w/ all the data.


#### Inspecting data
* head
* tail
* grep/ack
* Documentation, if available!

#### Tools (Medium-sized Data)
* SPSS, PSPP
* awk
* R
* pandas (demo)

#### Tools (Larger Data)
* Python & Hadoop Streaming
	* mrjob (demo)
* Hive & Hadoop (demo)
