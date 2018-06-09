
# About

Leaderboard is a simple combination of HTML+Javascript (HT: [Sheetrock](https://github.com/chriszarate/sheetrock)) to embed a student evaluation of teaching (SET) response leaderboard in any web page.  It's orgins as are a personal kludge, which has evolved to be used by others.

The following image is a representation of how it works.

![SET leaderboard in action](https://i0.wp.com/c1.staticflickr.com/5/4207/35314111366_4a463eabd7_z.jpg?resize=640%2C251&ssl=1)

# Why?

The purpose of the leaderboard is to increase response rates from students evaluating your teaching. [This page](http://djon.es/blog/2017/06/17/nudging-up-myopinion-response-rates-using-a-gamified-leaderboard/) provides more detail on why and the results in a number of courses.

# Requirements

1. A publicly available Google spreadsheet ([for example](https://docs.google.com/spreadsheets/d/1o7Dqv8XK54yVrvAmbJvsf88ot2QssSxUMJM4wP8q204/edit#gid=0)) with rows capturing multiple SET response rates
> Typically this is over multiple offerings. But some have used it to compare between different student cohorts. You will enter data about student response rates into this Google spreadsheet.
1. A web page (e.g. a part of a Moodle site) in which you can insert some HTML+Javascript (below)
> This HTML+Javascript will retrieve the content from the Google spreadsheet and display it to students

# How to use it

1. Copy [this example Google spreadsheet](https://docs.google.com/spreadsheets/d/1o7Dqv8XK54yVrvAmbJvsf88ot2QssSxUMJM4wP8q204/edit#gid=0)) and modify it with your data.
> See [this page](http://djon.es/blog/creating-a-set-leaderboard/#spreadsheet) for some more detail
1. Copy the contents of [the COPY_ME.html file](https://github.com/djplaner/leaderboard/blob/master/COPY_ME.html), paste it into your HTML file, and replace `**COPY AND PASTE GOOGLE SHEET URL BETWEEN QUOTES` with the URL for your Google spreadsheet
> See [this page](http://djon.es/blog/creating-a-set-leaderboard/#html) for some more detail


