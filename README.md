# stat240-assignment-4-solved
**TO GET THIS SOLUTION VISIT:** [STAT240 Assignment 4 Solved](https://www.ankitcodinghub.com/product/stat240-assignment-4-solved/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;97940&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;0&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;0&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;0\/5 - (0 votes)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;STAT240 Assignment 4 Solved&quot;,&quot;width&quot;:&quot;0&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

<div class="kksr-stars">

<div class="kksr-stars-inactive">
            <div class="kksr-star" data-star="1" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="2" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="3" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="4" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="5" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>

<div class="kksr-stars-active" style="width: 0px;">
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>
</div>


<div class="kksr-legend" style="font-size: 19.2px;">
            <span class="kksr-muted">Rate this product</span>
    </div>
    </div>
<div class="page" title="Page 1">
<div class="layoutArea">
<div class="column">
Writing a histogram function

We will write a version of the histogram function almost from scratch (some basic plotting functions will be assumed). If you struggle with this question, please read the O’Reilly text Learning R, or chapter 11 of the course textbook Automated Data Collection with R. Question 1a, (4 points): Create a function in R named counts. This function should take as parameters a numeric vector x and also a number indicating a number of bins n. The function will consider the range [min(x), max(x)], and then consider a partition of this interval into n equally sized non-overlapping intervals (the first interval will be closed, and the remaining intervals will be half open on the left): I1 = [min(x), b1], I2 = (b1, b2], . . ., In = (bn1, max(x)]. Note that since the intervals are equally sized, the value of bi is constrained. The function will then return a vector of length n such that the j-th element of this vector is the number of elements of x that lie in the interval Ij. Provide the code for this function: It should be of the following form:

<pre> counts = function( ... ) {
   ...
</pre>
<pre>   return(...)
 }
</pre>
Question 1b, (3 points): Create a function in R called histo and provide the R code. This function should take the same x and n parameters as the count function you wrote in the previous part of the question, and it should plot a histogram of the vector x with the n bins defined in the previous part of the question. The only plotting functions you may make use of are the plot function and the lines function (‘just add an egg’). You may not make use of the hist function. Provide your code for this function. Hint: there are several ways to do this, one way would be to create a new and empty plot with:

</div>
</div>
<div class="layoutArea">
<div class="column">
plot(1,

type = ‘n’, xlab = ‘x’, ylab = ‘counts’, xlim = …, ylim = …)

</div>
</div>
<div class="layoutArea">
<div class="column">
1

</div>
</div>
</div>
<div class="page" title="Page 2">
<div class="layoutArea">
<div class="column">
Then make a for loop through the bins and call lines in the body of the for loop so that three lines (delinating the left, top, and right of the rectangle for that bin) are drawn. As before, your code should be in the following form:

<pre> histo = function( ... ) {
   ...
</pre>
}

Question 1c, (2 points): We will now test the histo function. Create a vector of 200 random variables such that the first 100 random variables are independent draws from a normal distribution with mean -1 and variance 1 and the second 100 elements are independent draws from a normal distribution with mean 1 and variance 1. Call your histo function on this vector with 10 bins, and provide a graphic including the resulting plot.

Question 1d, (2 points): We will now test a corner case of the histo func- tion. Call histo on the vector x = (0, 0, 0, 1, 1, 2) with 3 bins, and provide a graphic including the resulting plot. Note that this is a corner case because the middle values lie at the boundary between two bins, and so their contribution to the histogram’s height requires that the half-open nature of the intervals be respected.

Moving Averages with SQL

In statistics, a moving average (rolling average or running average) is a calcu- lation to analyze data points by creating series of averages of di↵erent subsets of the full data set. Usually the mean is taken from an equal number of data on either side of a central value. Sometimes we use the average of the previous few years since we do not yet have information moving forward. Let’s look at how to obtain moving with SQL Queries. Lets try to obtain moving averages for total number of athletes who obtained medals regardless of which country they are from. We will make use of the sqlite table provided in the previous lab. Throughout this section, please refer to Chapter 7 of the textbook of this course or to http://www.dev.mysql.com/doc/refman/8.0/en for more detail about the functions used (not all of them were covered in the SQL lectures). First we need to create a Frequency table where we need a unique list of year with its corresponding total medal counts. To do this we will create a new virtual table as an interim step. We’ll split up the task into small pieces so that you can see what is happening.

• Obtain the medal count within each year for the Olymp meds table.

2

</div>
</div>
<div class="layoutArea">
<div class="column">
<pre>mov_avg1 = "SELECT Edition, Count(Edition) AS TotalNumber
  FROM Olymp_meds GROUP BY Edition"
</pre>
<pre>out = dbGetQuery(con, mov_avg1)
</pre>
</div>
</div>
</div>
<div class="page" title="Page 3">
<div class="layoutArea">
<div class="column">
Make a nice plot of the number of athletes who obtained medals per year. Use the option type=”p”. Make sure axes and the title are nice and clear.

• Create a virtual table (called a VIEW ) which we will call tot meds to house that output from the previous query without bringing the results into R. This will let us do other queries on that virtual table.

Check that the above worked by finding the new virtual table inside the database.

<pre>  dbListTables(con)
</pre>
<ul>
<li>Do this to delete the temporary table so that you don’t get stuck with errors when you rerun your code. If you run this you will need to re-run the previous step to re-build the virtual table.
<pre>  #dbSendQuery(con, "drop view tot_meds")
</pre>
</li>
<li>Query the virtual table to extract year and total medal.
Add a line plot of the total number of athletes who received medals per year from this table as an addition to the plot in part 1a. Make sure you chose a di↵erent colour for the line.
</li>
</ul>
</div>
</div>
<div class="layoutArea">
<div class="column">
<pre>plot(out$Edition, out$TotalNumber,
main="Total number of athletes who obtained Olympic medals",
</pre>
<pre>     xlab="year",ylab="Count",type="p",
     col="red",lwd=2,las=2)
</pre>
</div>
</div>
<div class="layoutArea">
<div class="column">
<pre>mov_avg2 = "CREATE VIEW tot_meds AS SELECT Edition,
Count(Edition) AS TotalNumber
FROM Olymp_meds GROUP BY Edition"
dbSendQuery(con, mov_avg2)
</pre>
</div>
</div>
<div class="layoutArea">
<div class="column">
<pre>mov_avg3 = "SELECT Edition, TotalNumber FROM tot_meds"
out = dbGetQuery(con, mov_avg3)
</pre>
</div>
</div>
<div class="section">
<div class="layoutArea">
<div class="column">
<pre>#remaking the plot from 1a (not necessary for students):
</pre>
<pre>plot(out$Edition, out$TotalNumber,
main="Total number of athletes who obtained Olympic medals",
</pre>
<pre>     xlab="year",ylab="Count",type="p",
     col="red",lwd=2,las=2)
</pre>
lines(out$Edition, out$TotalNumber,col=1,lwd=2)

# Note that the line must go through the points

# to show that it is from “lines” instead of type=”b”.

</div>
</div>
</div>
<div class="layoutArea">
<div class="column">
3

</div>
</div>
</div>
<div class="page" title="Page 4">
<div class="layoutArea">
<div class="column">
• Now we will compute a moving average by defining an index within the year and averaging everything within that window. This requires us to define two new tables t1 and t2. Remember that we can specify where a variable comes from by using ”.”. So t1.year means that we use the variable year from table t1.

We will use table t1 to define an index over year and use that index to average everything within the window:

WHERE t2.Year BETWEEN (t1.Year-4) AND (t1.Year+4) .

Note that the moving average will contain more or less Olympics within the window depending on the year. The reason is that the Olympics were occasionally cancelled due to world wars.

Put a line with the moving average on the figure and make a legend(total 4 points; 2 points for the line, 2 points for the legend).

</div>
</div>
<div class="section">
<div class="layoutArea">
<div class="column">
<pre>check = "SELECT * FROM tot_meds AS t,
        (SELECT t1.Edition, AVG(t2.TotalNumber) AS mavg
</pre>
<pre>            FROM tot_meds AS t1, tot_meds AS t2
  WHERE t2.Edition BETWEEN (t1.Edition-4) AND (t1.Edition+4)
  GROUP BY t1.Edition) sq  WHERE (t.Edition = sq.Edition)"
</pre>
<pre>movingAvg = dbGetQuery(con, check)
</pre>
</div>
</div>
</div>
<div class="section">
<div class="layoutArea">
<div class="column">
<pre>#remaking the plot from 1a (not necessary for students):
</pre>
<pre>plot(out$Edition, out$TotalNumber,
main="Total number of athletes who obtained Olympic medals",
</pre>
<pre>     xlab="year",ylab="Count",type="p",
     col="red",lwd=2,las=2)
</pre>
lines(out$Edition, out$TotalNumber,col=1,lwd=2)

### New part:

lines(movingAvg$Edition, movingAvg$mavg,type=”l”,col=3,lwd=2) legend(“topleft”,lwd=2,lty=c(NA,1,1),pch=c(1,NA,NA),

<pre>        col=c(2,1,3),
       c("medals per year points",
</pre>
<pre>               "medals per year line",
               "moving average"))
</pre>
</div>
</div>
</div>
<div class="layoutArea">
<div class="column">
Now, make sure that you delete the temporary table.

Two dimensional density plots

Question 2a, (4 points): Plot the locations of all of the pokemon in the Vanpoke table provided in the previous lab, overlayed on a map of Vancouver. Provide the resulting graphic. The following code segment may be useful:

4

</div>
</div>
</div>
<div class="page" title="Page 5"></div>
