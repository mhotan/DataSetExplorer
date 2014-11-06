# README #

# Data Set Explorer (For lack of a better name) #
* Version: 0.0.1

### What is this Project in three sentences? ###

This is web application that is intended to shorten the time it takes for people to find different Data Sets.
We want to empower end users by allowing them to find data sets that pertain to them faster then ever before.
The application will serve as a search base tool to search and index data sets across different web host and domains.

Follow up Note:
The initial intentions of this project was to easily find Socrata data sets to throw into a Tableau visualization.
The scope was deemed to specific and was then generalized into an alternate tool to make discovering data simpler and
more enjoyable.

## Background ##

### What is Open Data?

In simple terms, "Open Data" is data that has been made openly available to the public.  While the diversity and adoption
 of open data has been increasing, there is a lot of debate around which data should be made public.  That and the lack
 of a clear, cookie cutter Return on Investment strategy has resulted in less adoption in some organizations.

See the [wiki](http://en.wikipedia.org/wiki/Open_data) for a more detailed and articulate explanation.

### Who would use this so called Data Set Explorer?

Researchers, Students, Civic activists, Data curious people, and Data Visualization enthusiast.

### User Stories
Hypothetical User Stories that help build the scope and vision of this project.

#### Jane the Social Scientist
Suppose Jane is a social science researcher.  Her current project is to compare and contrast the crime activity
statistics between different States within the USA.  She uses the Data Set Explorer to search for criminal data
for different cities within the United States.  Instead of panning around Google diving into different different
government websites, Jane is able to utilize Data Set Explorer search functionality.  She is able to find crime
data sets for different cities in the fraction of the time using a common search engine.

#### Curious Joe

Curious Joe is looking to understand more about his local community's upcoming budget plan.  He find that the local
media and the people he speaks usually lack empirical evidence in support of their claims.  Curious Joe is able to use
Data Set Explorer to find the data set he needs.  Subsequently Data Set Explorer is able to suggest and show related
data sets related to that and nearby communit communities.

#### Amy, Andy, and Alex (A Cubed) the business analytics team

A Cubed is looking to do research about investment in a particular target area for their business.
A Cubed uses Data Explorer to link, share, and save specific notes about particular data sets within
their group.  This allows them to share notes within themselves without revealing company internal
information to the public.

### Potential Data Set Sources

#### Socrata

Socrata has been an integral company in the progression of open data.  They are currently hosting open data for public sector
organizations all over the world (but currently mostly in the United States).  For more information about who they are
please visit their site [here](http://www.socrata.com/).

### Import.io

Import.io is a fast and effective tool to turn web pages into data sets.  See [import.io](https://import.io/).

### Target Features

* Responsive UI - P1
* Search and Filter data sets across different web services and domains - P1
* Create groups of users - P1
* Share data sets publicly, between individuals, or within a group - P1

### Advanced Features
* Tableau Web Connection functionality. - P1
* Recommendation Engine for Data Sets. - P2

### Tools

* [Gradle](http://www.gradle.org/) Build and execution tool.
* [Spring Boot](http://spring.io/guides/gs/spring-boot/) Spring powered application and service.
* [AngularJS](https://angularjs.org/) Front End Web Client Framework.
* [Learn Markdown](https://bitbucket.org/tutorials/markdowndemo) Used to write this README

### How do I get set up? ###

The intent with using Java to write our backend and HTML, CSS, AngularJS to write our frontend
 was to utilize current standards within industry.  Thus providing the lightest ramp up cost for
  interested contributors.  We also wanted to be able to have the source code be easily extended.

#### Configuration ####

##### Clone Git Repository #####
For the sake of maintainability Github contributors will be kept at a minimum.  However, anyone
can [Fork](https://help.github.com/articles/fork-a-repo/) the [Github repository](https://github.com/mhotan/DataSetExplorer)
 and submit pull request for making contributions.

Command line git clone

```
git clone https://github.com/mhotan/DataSetExplorer.git
```

If you are new to git or don't like the command line try [SourceTree](http://www.sourcetreeapp.com/)

##### Clone Git Repository #####

##### Requirements #####

* [git](http://git-scm.com/)
* [Java SE JDK 8](http://www.oracle.com/technetwork/java/javase/downloads/jdk8-downloads-2133151.html)

Note: You do not need to download [Gradle](http://www.gradle.org/) to work on this project.
All gradle commands can be done through the gradle wrapper (gradlew or gradlew.bat)

##### Database Configuration #####
TODO How to configure database.

##### Running Tests #####

For Java, from the root directory run
For unix based systems
```
./gradlew test
```

For windows systems
```
gradlew.bat test
```

##### Deployment instructions #####
TODO Decide which deployment platform to go to.
Currently building Alpha

### Contribution guidelines ###

##### Branching #####
Make git branches are descriptive in what they are trying to achieve.

##### Writing tests #####
Follow Gradle Java Plugin format.  Make sure most classes has there own individual test.
IE. src/main/java/ClassA.java has a test class  src/test/java/ClassA.java for hypothetical ClassA.

##### Code review #####
Will be done through Github for each pull request

##### Writing tests #####

* TODO Other guidelines

## Other Information

### What the heck is a Tableau?

Technically its the french word for table.  However, in this context we are refering to [Tableau Software](http://www.tableausoftware.com/).
Tableau Software is a data visualization company that seeks to help people see and understand their data.
Their desktop product allows users to explore their data and gain understand in fast and delightful ways.
They recently announced a new web based "Data Connection" at their last Tableau Conference Key Note see
[here](https://tc14.tableausoftware.com/keynote) 1:17:00.

Caveat: At the time of starting this project the owner worked for Tableau Software.
This is project was taken on completely independently of either companies.

### Contact ###

* Owner: Michael Hotan, michael.hotan@gmail.com
* [Code for Seattle](http://codeforseattle.org/)

