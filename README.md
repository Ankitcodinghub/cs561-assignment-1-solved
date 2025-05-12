# cs561-assignment-1-solved
**TO GET THIS SOLUTION VISIT:** [CS561 Assignment 1 Solved](https://www.ankitcodinghub.com/product/cs561-assignment-1-solved/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;91579&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;2&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;5&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;5\/5 - (2 votes)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;CS561 Assignment 1&nbsp;Solved&quot;,&quot;width&quot;:&quot;138&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

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

<div class="kksr-stars-active" style="width: 138px;">
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
            5/5 - (2 votes)    </div>
    </div>
<div class="page" title="Page 1">
<div class="layoutArea">
<div class="column">
&nbsp;

In this assignment, you will express “complex” OLAP queries in SQL. The key point of the exercise is to observe the complexity of expressing the type of such queries despite relatively simple ideas of the queries themselves. Your mission (in addition to writing the SQL queries) is to consider the reasons for the complexity of the expression of these queries.

Generate separate reports/output based on the following queries (one report for each of the queries):

<ol>
<li>For each customer, compute the minimum and maximum sales quantities along with the corresponding products, dates (i.e., dates of those maximum and minimum sales quantities) and the states in which the sale transactions took place. For the same customer, also compute the average sales quantity.</li>
<li>For each combination of customer and product, output the maximum sales quantities for October (regardless of the year, that is, both 10/11/2016 and 10/23/2019 are considered sales transactions for October) and minimum sales quantities for November and December (again, regardless of the year) in 3 separate columns. Like the first report, display the corresponding dates (i.e., dates of those maximum and minimum sales quantities). Furthermore, for October (MAX), include only the sales that occurred after 2017 (that is, not to include sales that occurred in 2017 or earlier); for November (MIN) and December (MIN), include all sales.</li>
<li>For each of the 12 months (regardless of the year), find the most “popular” and least “popular” products (those products with most and least total sales quantities) and the corresponding total sales quantities (i.e., SUMs).</li>
<li>For each product, find the “most favorable” month (when most amount of the product was sold) and the “least favorable” month (when the least amount of the product was sold).</li>
<li>For the years 2016, 2017, 2018, 2019 and 2020, show, for each product and customer combination, the average sales quantities for the 4 states, ‘CT’, ‘NY’, ‘NJ’ and ‘PA’ (in four separate columns). Also compute the average for the “whole” year (again ignoring the YEAR component, meaning simply compute AVG) along with the total quantities (SUM) and the counts (COUNT).</li>
</ol>
The following are sample output reports – quantities displayed are for illustration only (not the actual values).

</div>
</div>
<div class="layoutArea">
<div class="column">
Fall 2021

</div>
</div>
<div class="layoutArea">
<div class="column">
Report #1:

CUSTOMER ======== Bloom Sam Emily ….

Report #2:

<pre>   CUSTOMER
   ========
   Sam
   Helen
   Bloom
</pre>
….

</div>
<div class="column">
MIN_Q MIN_PROD MIN_DATE ST MAX_Q MAX_PROD ===== ======== ========== == ===== ========

</div>
<div class="column">
<pre>MAX_DATE    ST  AVG_Q
==========  ==  =====
09/25/2019  NY   1435
03/23/2018  CT     56
02/02/2016  NJ   1512
</pre>
</div>
</div>
<div class="layoutArea">
<div class="column">
<pre>12  Pepsi
 1  Milk
 1  Bread
</pre>
</div>
<div class="column">
<pre>01/01/2016  NJ   2893  Apple
02/15/2017  NJ    259  Banana
07/01/2018  NY   3087  Milk
</pre>
</div>
</div>
<div class="layoutArea">
<div class="column">
PRODUCT OCT_MAX OCT_DATE NOV_MIN NOV_DATE DEC_MIN DEC_DATE

</div>
</div>
<div class="layoutArea">
<div class="column">
======= ======= ========== ======= ==========

</div>
<div class="column">
<pre>=======  ==========
   2432  12/03/2018
   9483  12/23/2017
   2596  12/11/2016
</pre>
Page 1 of 2

</div>
</div>
<div class="layoutArea">
<div class="column">
<pre>Egg
Cookies
Butter
</pre>
</div>
<div class="column">
<pre> 8  10/11/2019
92  10/22/2018
45  10/31/2020
</pre>
</div>
<div class="column">
<pre>3234  11/24/2016
4342  11/14/2020
1923  11/10/2017
</pre>
</div>
</div>
</div>
<div class="page" title="Page 2">
<div class="layoutArea">
<div class="column">
Report #3:

MONTH MOST_POPULAR_PROD MOST_POP_TOTAL_Q LEAST_POPULAR_PROD LEAST_POP_TOTAL_Q ===== ================= ================ ================== =================

</div>
</div>
<div class="layoutArea">
<div class="column">
<pre>       1  Eggs
       2  Milk
       3  Pepsi
</pre>
….

Report #4:

<pre>   PRODUCT  MOST_FAV_MO
   =======  ===========
   Egg                4            12
</pre>
</div>
<div class="column">
<pre> 497214  Pepsi
1874794  Banana
</pre>
974531 Milk

</div>
<div class="column">
<pre>55526
23126
19958
</pre>
</div>
</div>
<div class="layoutArea">
<div class="column">
Apple Banana ….

Report #5:

</div>
<div class="column">
1 11 3 2

</div>
</div>
<div class="layoutArea">
<div class="column">
<pre>LEAST_FAV_MO
============
</pre>
</div>
</div>
<div class="layoutArea">
<div class="column">
Grading

Submission

</div>
<div class="column">
NOTE: A query with syntax errors will lose 50% of the points for the query.

</div>
</div>
<div class="layoutArea">
<div class="column">
PRODUCT

=======

Pepsi Sam 1923 4241 2383 1325 2988 38848 13

</div>
</div>
<div class="layoutArea">
<div class="column">
Milk Bread

….

</div>
<div class="column">
Emily 239 9872 142 2435 2663 21307 8 Helen 2534 981 4239 1987 2781 25032 9

</div>
</div>
</div>
