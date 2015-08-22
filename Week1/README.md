
##Week 1:

Lots of getting set up and review exercises.

## What This Class Covers, the General Plan...

Review repo [README](../README.md).

**Homework Reading**: The client brief.  Look for any open questions you may have after looking at their report and website.  Take a few notes, we'll discuss next week.


## Data Formatting in Excel

* Recommended read for general good advice: http://kbroman.org/dataorg/

We'll go through a download and csv formatting example in class.  You'll need to do the same, so take notes!

**Homework**: Download a data set and format in Excel for use in visualization. Try to mimic the simple style in my csv examples. See below for how to send me the result in a gist.


## Your Local Server

Set up your servers. Depending on time, we'll do it in class. Use this to help: https://github.com/arnicas/d3-faq#running-a-server


## Intro to Chrome Tools, the Console

* View Source. Let's do it. First at childmortality.org...
* Look at a newspaper site too, and view the styling on an article. You'll need this for a homework project.
* Read a bit here about the console and trying stuff in it: http://jsforcats.com/#basics


### Github and Gists:

#### Github

Github is how you should get and keep the course files up to date.
Make an account, if you haven't.

* Make sure you have git installed: https://git-scm.com/book/en/v2/Getting-Started-Installing-Git
* Read: Gists how-to:  https://help.github.com/articles/creating-gists/
* Command line tool info (optional): https://github.com/mbostock/gistup

I recommend you clone my repo, so you can repull it as I add stuff. You will do `git clone [copied path]`.  I'll show you in class.

#### Gists

You'll be doing homework in gists.  This makes it easier for me to review and check it and find issues. Also, the bl.ocks.org site makes things easy for visual display of gists.  See: http://bl.ocks.org/

Make a directory for your files for a gist and upload those by hand from the web page, or using the command line tool gistup. If you use the command line, make a directory for each gist, NOT INSIDE THE CLASS REPO YOU CLONED. (It can't be inside another repo.)

* If you want your d3 visual code to show up in bl.ocks.org, you need to name your html file index.html.
* And you need to make sure you use a CDN path to D3, not refer to it locally on your own machine. That means, in the `<script>` tag, you want to reference: `<script type="text/javascript" src="//cdnjs.cloudflare.com/ajax/libs/d3/3.5.6/d3.min.js"></script>` instead of a local path.

You can see all your gists by looking here - where you fill in your own user name where mine is: `https://gist.github.com/arnicas`. If you want to edit or delete it, click on the header for one from the list.


### Intro to HTML/CSS:

Have a look at this fun project, Tufte CSS: http://www.daveliepmann.com/tufte-css/.

A refresher on HTML and CSS is necessary -- you can't afford to NOT be good at CSS with interactive graphics.  It's as important as Javascript. There's a refresher in Ch 3 of IDVW.

**Homework**: Style [this page](files/wapo_debates_article.html) to look like the news website of your choice or like Tufte.  Make a gist (index.html for the file name!) and send it to me.  You can keep the styles in the page or in a file you load.


### Javascript Review

I sent you some stuff over the summer, and here is a list of teaching references again: https://www.javascript.com/resources. And http://learnxinyminutes.com/docs/javascript/.

A super simple intro with gif demos is JS For Cats: http://jsforcats.com/
You should review everything in it except for the last part on callbacks now.

We'll play with [files/console_javascript.html](files/console_javascript.html) now.

**Homework:** Fix js_errors.html so it displays correctly.  Send me a screen cap of your console with the results of all the stages correctly showing. Subject line: "Week 1, js errors".  If you can't do it all, send me as far as you got.


### Loading Data with JS/D3:

You will use the data you downloaded and formatted in D3 next week.

**Recommended Reading**: Loading data with D3, at http://learnjsdata.com/read_data.html.


### Homeworks Collected Up

Readings:

* Read Chapter 3 of IDVW: http://chimera.labs.oreilly.com/books/1230000000345/ch02.html. You can stop at the SVG part at the end of chapter 3, for now. (Chapter 2 may be nice background but is optional.)

* [The client brief](../APromiseRenewed_Brief_March2015.pdf): Look for any open questions you may have after looking at their report and website.  Take a few notes, we'll discuss next week.

* Loading data with D3, at http://learnjsdata.com/read_data.html.

**Homework:** fix js_errors.html so it displays correctly.  Send me a screen cap of your console with the results of all the stages correctly showing. Subject line: "Week 1, js errors".  If you can't do it all, send me as far as you got.

**Homework**:  Style [this page](files/wapo_debates_article.html) to look like the news website of your choice or like Tufte.  Don't get out of control - just headlines, byline, paragraph/body text, and images.  Make a gist and send me the link: "Week 1: style."

**Homework**: Download a UNICEF data set and format in Excel for use in visualization.  Keep a copy of the Excel file(s) for yourself, but save out a CSV file that can be loaded into javascript. Make a gist with the csv file and send me the link: 'Week 1: CSV data.'

