# itse-2309---database-programming-oracle-lab-4---table-constraints-solved



**<span style='color:red'>TO GET THIS SOLUTION VISIT:</span>** https://www.ankitcodinghub.com/product/itse-2309-database-programming-oracle-lab-4-table-constraints-solved/

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;53853&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;1&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;5&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;5\/5 - (1 vote)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;ITSE 2309 – Database Programming: Oracle Lab 4 – Table Constraints Solved&quot;,&quot;width&quot;:&quot;138&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">
            
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
JustLee Books has become the exclusive distributor for a number of books. The company now needs to assign sales representatives to retail bookstores to handle the new distribution duties. For these assignments, create new tables to support the following:

&nbsp;

<ol>
<li>Modify the following SQL command so that the Rep_ID column is the PRIMARY KEY for the table and the default value of ‘Y’ is assigned to the Comm column. (The Comm column indicates whether the sales representative earns commission.)</li>
</ol>
&nbsp;

CREATE TABLE store_reps (rep_ID NUMBER(5), last VARCHAR2(15), first VARCHAR2(10), comm CHAR(1));

&nbsp;

&nbsp;

<ol start="2">
<li>Change the STORE_REPS table so that NULL values can’t be entered in the name columns (First and Last).</li>
</ol>
&nbsp;

<ol start="3">
<li>Change the STORE_REPS table so that only a Y or N can be entered in the Comm column.</li>
</ol>
&nbsp;

<ol start="4">
<li>Add a column named Base_salary with a datatype of NUMBER(7,2) to the STORE_REPS table. Ensure that the amount entered is above zero.</li>
</ol>
&nbsp;

<ol start="5">
<li>Create a table named BOOK_STORES to include the columns listed in the following chart.</li>
</ol>
&nbsp;

&nbsp;

&nbsp;

&nbsp;

<ol start="6">
<li>Add a constraint to make sure the Rep_ID value entered in the BOOK_STORES table is a valid value contained in the STORE_REPS table. The Rep_ID columns of both tables were initially created as different datatypes. Does this cause an error when adding the constraint? Make table modifications as needed so that you can add the required constraint.</li>
</ol>
&nbsp;

<ol start="7">
<li>Change the constraint created in Assignment #6 so that associated rows of the BOOK_STORES table are deleted automatically if a row in the STORE_REPS table is deleted.</li>
</ol>
&nbsp;

<ol start="8">
<li>Create two tables based on the E-R model shown below and the business rules in the following list for a work order tracking database. Include all the constraints in the CREATE TABLE statements. You should have only two CREATE TABLE statements and no ALTER TABLE statements. Name all constraints except NOT NULLs.</li>
</ol>
&nbsp;

&nbsp;

&nbsp;

Business Rules

&nbsp;

<ul>
<li>Use your judgment for column datatypes and sizes.</li>
<li>Proj# and Wo# are used to uniquely identify rows in these tables.</li>
<li>Each project added must be assigned a name, and no duplicate project names are allowed.</li>
<li>Each work order must be assigned to a valid project when added and be assigned a description and number of hours.</li>
<li>Each work order added must have a different description.</li>
<li>The number of hours assigned to a work order should be greater than zero.</li>
<li>If data is provided for the Wo_complete column, only Y or N are acceptable values.</li>
</ul>
&nbsp;

Create and execute the SQL statements needed to enforce the data relationships among these tables.

&nbsp;

&nbsp;

Upload only the <strong>SQL Statements</strong> to Blackboard.

&nbsp;
