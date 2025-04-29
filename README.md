# cis3530-lab3-solved
**TO GET THIS SOLUTION VISIT:** [CIS3530 Lab3 Solved](https://www.ankitcodinghub.com/product/lab3-cis-3530-worth-4-solved/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;115188&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;1&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;5&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;5\/5 - (1 vote)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;CIS3530 Lab3 Solved&quot;,&quot;width&quot;:&quot;138&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

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
            5/5 - (1 vote)    </div>
    </div>
Submit all queries in a file called lastnameFirstnameL3.sql (e.g. chaturvediRituL3.sql)

Step 1. Connect to linux.socs.uoguelph.ca and Postgres (see tutorial1 for details).

Step 2. Download the following 2 scripts from Moodle and run them on

Postgres:

(1) movies_schema.sql to create and populate the movie database

(2) movies_schema_alter.sql to add primary and foreign keys to the created tables.

Remember, to run the scripts on Postgres, use i (e.g. i movies_schema.sql). &gt;select * from movie;

mid | title | year | director —–+————————-+——+——————

101 | Gone with the Wind | 1939 | Victor Fleming

102 | Star Wars | 1977 | George Lucas

103 | The Sound of Music | 1965 | Robert Wise

104 | E.T. | 1982 | Steven Spielberg

105 | Titanic | 1997 | James Cameron

106 | Snow White | 1937 |

107 | Avatar | 2009 | James Cameron

108 | Raiders of the Lost Ark | 1981 | Steven Spielberg

(8 rows)

&gt;select * from reviewer;

rid | name —–+——————

201 | Sarah Martinez

202 | Daniel Lewis

203 | Michael Walsh

204 | Mike Anderson

205 | Chris Jackson

206 | Elizabeth Thomas

207 | John Moore

208 | Ashley White

(8 rows)

&gt;select * from rating;

rid | mid | stars | ratingdate —–+—–+——-+————

201 | 101 | 2 | 2011-01-22

201 | 101 | 4 | 2011-01-27

202 | 106 | 4 |

202 | 107 | 3 | 2011-10-02

203 | 103 | 2 | 2011-01-20

203 | 108 | 4 | 2011-01-12

203 | 108 | 2 | 2011-01-30

204 | 101 | 3 | 2011-01-09

205 | 101 | 3 | 2011-01-27

205 | 102 | 2 | 2011-01-27

205 | 105 | 4 | 2011-01-27

205 | 106 | 2 | 2011-01-27

205 | 107 | 3 | 2011-01-27

205 | 103 | 3 | 2011-01-27

205 | 104 | 2 | 2011-01-22

205 | 108 | 4 |

206 | 107 | 3 | 2011-01-15

206 | 106 | 5 | 2011-01-19

207 | 107 | 5 | 2011-01-20

208 | 104 | 3 | 2011-01-02

(20 rows)

rating(rid) is a foreign key that references table reviewer rating(mid) is a foreign key that references table movie

Step 3: Write SQL queries to do the following:

1. List names of reviewers who reviewed all movies reviewed by ‘Elizabeth Thomas’. Expected Result:

name ——————

Daniel Lewis

Chris Jackson

Elizabeth Thomas

(3 rows)

2. List all reviewers and the total number of movies reviewed by them

SELECT count (*) AS total FROM Movie;

Expected Result:

name | total ——————+—— Chris Jackson | 8

Michael Walsh | 3

Daniel Lewis | 2

Elizabeth Thomas | 2

Sarah Martinez | 2

Ashley White | 1

Mike Anderson | 1

John Moore | 1

(8 rows)

3. List all movies that have been reviewed by 2 or more reviewers.

Expected Result:

title | Reviewed by ————————-+————-

Gone with the Wind | 4

Avatar | 4

Raiders of the Lost Ark | 3

Snow White | 3

E.T. | 2 The Sound of Music | 2

(6 rows)

4. Which movies have the highest rating?

Expected Result: title ————

Snow White

Avatar

(2 rows)

5. List the oldest movie (in this database) that has been reviewed.

Expected Result: title ————

Snow White

(1 row)
