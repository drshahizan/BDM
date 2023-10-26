<a name="br1"></a> 

**MCSD1123-01 BIG D** **ATA MANAGEMENT**

**ASSIGNMENT REPORT 1B**

**LECTURER’S NAME:**

PM DR. MOHD SHAHIZAN OTHMAN

**MEMBERS’ NAMES**

NABILA HUSNA BINTI ROSLI

NUR AZIMAH BINTI MOHD SALLEH

MOHD NOR BIN MOHIDIN

**MATRIC NO.**

MCS231009

MCS231011

MCS231008

MCS231002

ZUHAYR ARIF BIN ZAKARIA



<a name="br2"></a> 

**1.0**

**INTRODUCTION**

The purpose of the case study is to display the statistics of the overall result after

analyzing the examination results from the dataset named "dataset.txt.". This dataset has 5

columns and 111520 rows that contain information about student ID, academic and sports

performance, co-curriculum activities and test scores. The objective of this case study is to use

Google Sheets to process and analyze the data and create a visualization dashboard that

summarizes the data's results.

**2.0**

**DATA TRANSFORMATION**

The data received was in txt format and needed to be imported into Google Sheets so that

data processing could be done. To import the data, the steps should be done as follow:-

a) Create a new blank spreadsheet in Google Sheet.

b) Select File > Import.

c) Select the file to import.

d) Select an Import Location.

e) Select Convert text to numbers, dates, and formulas; and

f) Click Import.

**3.0**

**DATA PROCESSING**

After the data was imported into the Google Sheets, data values of the Academic, Sports,

Co-Curriculum, Test\_1 and Test\_2 need to be converted to two decimal places. In order to do

that, the steps are as follow:-

a) Highlight the cells containing the Data Values;



<a name="br3"></a> 

b) Use the function

to reduce the values to two decimal places

For the next data processing, five columns which are columns B (Academic) until

columns F (Test 2) have to change to the new maximum value of 3.33 for each column. The new

value needs to be displayed with two decimal places in the new column next after the column F

with column name P1 until P5.

To update the value of new column (Column G to Column K) with a maximum value of

3\.33, based on full marks given, below is the formula that should be followed: -

Table 3.1: The Column and Its Calculation Formula for Maximum Value of 3.33

**New Column**

**Column Name**

**Calculation Formula**

= (‘Academic Value’)/61\*3.33

G

H

I

P1

P2

P3

P4

P5

= (B2/61)\*3.33

= (‘Sports Value’)/10\*3.33

= (C2/10)\*3.33

= (‘Co-Curriculum Value’)/15\*3.33

= (D2/15)\*3.33

= (‘Test-1 Value’)/10\*3.33

= (E2/10)\*3.33

J

= (‘Test-2 Value’)/10\*3.33

= (F2/10)\*3.33

K

To update the above formula into the entire column itself, copy the formula, highlight the

first row in respective column until the last row using ‘Ctrl, Shift and down’ key and ‘Paste’. The

values then were converted to two decimal places using the same method as mentioned before

The result after applying the formula in column G to K is shown below: **-**



<a name="br4"></a> 

Figure 3.1: The New Value of Column P1 to P5 Out Of 3.33

The next data processing is to determine the top three values from the values in columns

G to K that have been updated with new maximum value and put it into new column next after

the column K. To find the top three values, the formulas are as follow:-

Table 3.2: The Column and Its Calculation Formula for Top Three Values

**New Column**

**Column Name**

**Calculation Formula**

= MAX(G2:K2)

L

B1

M

N

B2

B3

= LARGE(G2:K2,2)

= LARGE(G2:K2,3)



<a name="br5"></a> 

To update the above formula into the entire column itself, copy the formula, highlight the

first row in respective column until the last row using ‘Ctrl, Shift and down’ key and ‘Paste’. The

result will show the highest three values in each row in the column. Below is the result: -

Figure 3.2: The Top Three Values From Column P1 to P5

With the top three values that have been updated, the total values for the all top three

values from columns L to N need to be computed and entered in Column O with column name

TM. Also, the percentage values of the total values need to be calculated and entered in Column

P within two decimal places where the column name is Percent. The formulas are as follows:



<a name="br6"></a> 

Table 3.3: The Column and Its Calculation Formula for Total Marks (TM) and Percent

**New Column**

**Column Name**

**Calculation Formula**

= SUM(L2:N2)

O

TM

(Copy down the formula)

= Q2/(3.33\*3)\*100

P

PERCENT

(Copy down the formula)

The result shown as follow: -

Figure 3.3: The Total Marks and Percentage Values

Based on the grading system given, the grade and status will be assigned for each mark

value in column Percent and entered in column Q and R respectively. The formula to assign the

grade and status is listed in the table below:-



<a name="br7"></a> 

Table 3.4: The Column and Its Calculation Formula for Grade and Status

**New Column**

**Column Name**

**Calculation Formula**

=IF(P2>=90,"A+",IF(P2>=80,"A",IF(P2>=75,"

A-",IF(P2>=70,"B+",IF(P2>=65,"B",IF(P2>=6

0,"B-",IF(P2>=55,"C+",IF(P2>=50,"C",IF(P2>

=45,"C-",IF(P2>=40,"D+",IF(P2>=35,"D",IF(P

2>=30,"D-",IF(P2>=0,"E")))))))))))))

GRADE

Q

(Copy down the formula)

=IF(P2>=65,"PASS","FAIL")

(Copy down the formula)

R

STATUS



<a name="br8"></a> 

The result shown as follow: -

Figure 3.4: The Grade and Status Values

The next data processing is to colour Column P with green colour if the status is Pass and to

colour the Pass row with a light red colour. To do that, follow the steps below: -

To colour Column P with green colour:-

a) Select the range of cells that want to apply formatting to. (Highlight all of the cell

in column P)

b) In the file menu, click "Format" followed by "Conditional formatting"

c) The Conditional format rules menu will now appear on the right hand side of the

screen.



<a name="br9"></a> 

d) In the Format rules section, will see the “Format cells if” drop down menu, click

on “Greater than or equal to”.

e) Enter the value of 65 because the passing mark is 65..

f) Choose green colour in Formating Style; and

g) Click Done to see the result.

Figure 3.5: Conditional Formating for Colouring Column P

To colour the Pass row with a light red colour;-

a) Select the range of cells that want to apply formatting to. (Highlight all of the cell)

b) In the file menu, click "Format" followed by "Conditional formatting"

c) The Conditional format rules menu will now appear on the right hand side of the

screen.



<a name="br10"></a> 

d) In the Format rules section, see the “Format cells if” drop down menu, expand

this and scroll to the bottom. Click on “Custom formula is”.

e) Enter the formula =$R2:$R="PASS"

f) Choose light red colour in Formating Style; and

g) Click Done to see the result.

Figure 3.6: Conditional Formating for Colouring ‘Pass’ row

After performing all of the above data processing, the result will be shown as Figure 3.7 below:-



<a name="br11"></a> 

Figure 3.7: The Table of Dataset that has been processed.

**4.0**

**DATA VISUALIZATION**

For data visualization, there are some calculations and charts that need to be performed in order

to show the statistics of the overall result. From the data processing that has been done before,

we can determine the value of the following elements: -

a) Minimum, maximum and average values of the result.

b) The table and charts of grades obtained by students according to the number of

students.

c) The total records of students with the Pass and Fail status in the form of

percentages and numbers.

d) The views of Pass and Fail status in the form of pie charts.

Below is the formula to determine the minimum, maximum and average values:-



<a name="br12"></a> 

Table 3.5: The Column and Its Calculation Formula for Minimum, Maximum and Average

Values.

**Values**

**Calculation Formula**

= MIN(Dataset!$P:$P)

Minimum Value

Maximum Value

Average Value

= MAX(Dataset!$P:$P)

= AVERAGE(Dataset!$P:$P)

To create tables of grades obtained by students according to the number of students, we

can use the pivot table for the summarization of data in dataset or using the formula as follows:-



<a name="br13"></a> 

Table 3.6: The Column and Its Calculation Formula To Get The Number of Student According

To Their Grades

**NUMBER OF**

**STUDENT**

**CALCULATION FORMULA TO GET THE NUMBER**

**OF STUDENT**

**GRADE**

=COUNTIF(Dataset!$Q$2:$Q$111520,L4)

A+

A

8588

24264

12464

13956

13392

10677

7803

L4 is the cell of ‘A+’. To make changes in the cell of

‘A’ to ‘E’, copy down the formula.

A-

B+

B

Or

B-

C+

C

Using the Pivot table to summarize the data from the

dataset.

7566

C-

D+

D

5982

3436

1664

D-

1019

E

708

TOTAL

111,519



<a name="br14"></a> 

From the above table, we can create the Column Chart by following the step below:-

a) Select data by highlighting the appropriate cells and click Insert in the toolbar and

then select Chart.

b) In the Chart Editor, select Column Chart under the Chart Type dropdown..

c) The graph will appear in a box

Figure 3.8: Chart Editor For Column Chart

To show the total records of students with the Pass and Fail status in the form of percentages and

numbers, below is the formulas:-



<a name="br15"></a> 

Table 3.7: The Column and Its Calculation Formula To Get Total Records of Students with the

Pass and Fail Status In The Form of Percentages and Numbers.

**Values**

**Calculation Formula**

= COUNTA(Dataset!A2:A)

Total record for Number

of Students

= COUNTIF(Dataset!$R$2:$R$111520,O11)/M17

Percentage value for Pass

and Fail

where the M17 is the cell of number of students and O11 is

the cell of Pass or Fail. Then, format the cell into percentage

format.

= COUNTIF(Dataset!$R$2:$R$111520,O11) & " records"

where the O11 is the cell of Pass or Fail.

Total Records for Pass

and Fail

To views of Pass and Fail status in the form of pie chart, below is the steps to follow: -

a) Select data by highlighting the appropriate cells and click Insert in the toolbar and

then select Chart.

b) In the Chart Editor, select Pie Chart under the Chart Type dropdown..

c) The graph will appear in a box.



<a name="br16"></a> 

Figure 3.9: Chart Editor For Pie Chart

After performing the above calculation, table, graph and chart, the result of the visualization

dashboard will be shown as below:-

Figure 3.10: The Visualization Dashboard for Statistic of the Overall Result



<a name="br17"></a> 

**5.0**

**CONCLUSION**

In conclusion, after performing the data transformation, data processing, and data

visualization on the dataset given, the analysis of students examination results can be

summarized in the form of easy-to-understand and meaningful insight. The statistics of the

overall result that come from the dataset will be shown on the visualization dashboard, which

will help the responsible party to get some valuable information in improving the student

performance.

