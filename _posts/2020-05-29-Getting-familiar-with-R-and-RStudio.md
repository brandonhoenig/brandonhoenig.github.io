*Hello, everyone!*

My name is Brandon Hoenig, and I have been working in R for about 5
years. While I am far from an expert, I wanted to write up some posts
that go through how to use R. I plan to release this weekly, but work at
greater frequency if time allows. For this first post, we will be
introducing ourselves to the statistical software, R.

If you're here, you've probably heard time and time again how great R is
and why doing your analysis in a command line format is important.
Therefore, I won't bore you with those details. However, I will make a
short list of why I think analysis in any coding language is important.

-   *It allows you to keep track of how you analyzed your data and makes
    sharing with collaborators and readers easier.* In this day of fake
    news and alternative facts, scientists should make their analytic
    pipeline as accessible as possible to allow for proper scrutiny.

-   *You can do more!* Don't get me wrong, there are some things that
    Excel is just better at, like inputting data. However, if you want
    to do the kinds of advanced analyses that are demanded by current
    science, you'll have to turn to programs like R or Python to do
    them.

-   *It's free!* I'm sure that wherever you work, Microsoft Excel or
    other programs will be available to you. But what if they're not?
    What if you learned SPSS, but the company you work for uses JMP? If
    you know R, you'll be able to use *free* tools anywhere you go. And
    who doesn't love free?

There are probably a thousand of other reasons, but if you're here, you
probably don't need convincing. So let's jump into it and start to
familiarize ourselves with R.

Before we start make sure that you have
[R](http://lib.stat.cmu.edu/R/CRAN/) and
[RStudio](https://rstudio.com/products/rstudio/download/#download)
downloaded and installed.

Now, you're likely new to R if you're reading this, which is totally
okay! Even the most experienced data scientist started off as a novice.
The important thing is that you're here doing it now! So, if you'll open
RStudio, you should see something like this:

<img src="~/Desktop/GitHub/_posts/29_May_2020/RStudio.png" alt="Typical RStudio Window" width="100%" />
<p class="caption">
Typical RStudio Window
</p>

In the top left quadrant, we can see a blank notepad. This is where
you'd keep your notes for your analysis or write in the functions that
you'd like to use in your analysis. Don't worry if you don't know what a
function is right now, we'll go over those soon enough!

This is what a typical notepad of mine will have in it.

<img src="/_postmaterials/29_May_2020/TopLeftQuadrant.png" alt="My Notepad" width="100%" />
<p class="caption">
My Notepad
</p>

Don't worry too much about what is in the quadrant, just recognize that
this is the best place to store the pieces of your analysis. This is
basically just a text file and can be saved for later use down the road.
No need to write it down or try to remember what you did months down the
road.

The next area we'll look at the is bottom left quadrant, known as the
console. The console is where the magic happens. This is where your
functions will be evaluated and how your questions will be answered.
We'll get into functions more down the road, but just know that the
console is the heart of R.

Now there are three ways to use the console: the good way, the bad way,
and the ugly way. Each of these are fine to use, its just that some ways
are easier than others. Lets go over them.

*The Good Way*  
The method that I use is write whatever I want to do in the notepad
(i.e. the top left quadrant), click my cursor on the same line as the
function that I am running, and then press Command and Enter or Control
and Enter, depending on your computer. This way, our analysis is stored
in the notepad and our function runs with minimal steps.

<img src="/_postmaterials/29_May_2020/LeftQuadrants.png" alt="Good Way Example" width="100%" />
<p class="caption">
Good Way Example
</p>

In the above example, I did not have to copy and paste anything. Just
click next to whatever you want to run from your notepad and press
Command and Enter

*The Bad Way* This method is fine, but it just requires extra steps and
wastes time. Just as in the method above, you write what you want to do
in your notepad. However, this time, you copy the entire function or
combination of functions that you want to run, and then paste them into
the console below. This ensures that your code is correct and that you
selected the right lines, but I feel it is not necessary. But this is an
option, and if you prefer it, then go for it!

<img src="/_postmaterials/29_May_2020/LeftQuadrants2.png" alt="Bad Way Example" width="100%" />
<p class="caption">
Bad Way Example
</p>
