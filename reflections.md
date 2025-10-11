**[home](https://badebasligil.github.io/badebasligil/)** | **[projects](project.md)** | **[big ideas](big_ideas.md)** | **[resources](resources.md)** | **[reflections](reflections.md)**

# **CSP Quiz #3 Reflection**

### **Score:** 17/21

<img src="" width="">

### ***Success Rate Per Unit*** : 

| Unit  | # of Questions | Success Rate |
| ------------- | ------------- | ------------- |
| 2.1 Binary Numbers  | 6 | 83 % |
| 2.2: Data Compression | 3 | 100% |
| 2.3: Extracting Information from Data | 6 | 83% |
| 2.4: Using Programs with Data | 6 | 67% |

### ***Questions I Got Wrong*** : 

## **Q8**

The owner of a clothing store records the following information for each transaction made at the store during a 7-day period.

The date of the transaction
The method of payment used in the transaction
The number of items purchased in the transaction
The total amount of the transaction, in dollars
Customers can pay for purchases using cash, check, a debit card, or a credit card.

Using only the data collected during the 7-day period, which of the following statements is true?


- **A)** The average amount spent per day during the 7-day period can be determined by sorting the data by the total transaction amount, then adding the 7 greatest amounts, and then dividing the sum by 7.

- **B)** The method of payment that was used in the greatest number of transactions during the 7-day period can be determined by sorting the data by the method of payment, then adding the number of items purchased for each type of payment method, and then finding the maximum sum.

- **C)** The most expensive item purchased on a given date can be determined by searching the data for all items purchased on the given date and then sorting the matching items by item price.

- **D)** The total number of items purchased on a given date can be determined by searching the data for all transactions that occurred on the given date and then adding the number of items purchased for each matching transaction.

<code style="color : red">**What I Chose:** B, **Why It's Wrong:** You can find the most used payment method by counting how many times each payment type appears in the data, not by adding the number of items bought. After counting, sort these totals to see which payment method was used the most. </code>

<code style="color : green">**Correct Answer:** D </code>

## **Q13**

A database of information about shows at a concert venue contains the following information.

Name of artist performing at the show
Date of show
Total dollar amount of all tickets sold
Which of the following additional pieces of information would be most useful in determining the artist with the greatest attendance during a particular month?

-**A)** Average ticket price

-**B)** Length of the show in minutes

-**C)** Start time of the show

-**D)** Total dollar amount of food and drinks sold during the show

<code style="color : red">**What I Chose:** D, **Why It's Wrong:** The total money made from food and drinks may relate to how many people attended, but it doesn’t show the exact number of attendees. </code>

<code style="color : green">**Correct Answer:** A </code>

## **Q17**
A large spreadsheet contains information about the photographs in a museum’s collection. A sample portion of the spreadsheet is shown below.

 	
A Photographer

B Subject

C Year

D Publicly Available

1	Steven Greene	Geyser Eruption	2004	true
2	Linda James	Giant Sloth Fossil	-1	true
3	Yajaira Lopez	Diplodocus Skull	1997	false
4	Masahiro Higashi	Sea Turtle	1989	true
5	(unknown)	Solar Eclipse	2011	false
6	(unknown)	Giant Sequoia	-1	true
In column A, each unknown photographer is set to "(unknown)".
In column C, each unknown year is set to -1.
A student is developing an algorithm to determine the name of the photographer who took the oldest photograph in the collection. Photographs whose photographer or year are unknown are to be ignored.

Once the algorithm is complete, the desired entry will appear in the first row of the spreadsheet. If there are multiple entries that meet the desired criteria, then any of them can appear in the first row.

The student has the following actions available.

Action	Explanation
Filter by photographer	Removes entries whose photographer is "(unknown)"
Filter by year	Removes entries whose year is -1
Sort by subject	Sorts the rows in the spreadsheet on column B alphabetically from A to Z
Sort by year	Sorts the rows in the spreadsheet on column C from least to greatest
Assume that applying either of the filters will not change the relative order of the rows remaining in the spreadsheet.

Which of the following sequences of steps can be used to identify the desired entry?

-**A)** Filter by photographer, then filter by year, then sort by subject

-**B)** Filter by photographer, then filter by year, then sort by year

-**C)** Sort by subject, then sort by year, then filter by photographer

-**D)** Sort by year, then filter by year, then filter by photographer

<code style="color : red">**What I Chose:** C-D, **Why It's Wrong:** These steps don’t remove entries with an unknown year, so the first row will still have a year value of -1 </code>

<code style="color : green">**Correct Answer:** B-D </code>

## **Q18**

Consider the following numeric values.

Binary 1011
Binary 1101
Decimal 5
Decimal 12
Which of the following lists the values in order from least to greatest?

-**A)** Decimal 5, binary 1011, decimal 12, binary 1101

-**B)** Decimal 5, decimal 12, binary 1011, binary 1101

-**C)** Decimal 5, binary 1011, binary 1101, decimal 12

-**D)** Binary 1011, binary 1101, decimal 5, decimal 12

<code style="color : red">**What I Chose:** C, **Why It's Wrong:** I read the 'decimal 12' part as 'decimal **15**' :( </code>

<code style="color : green">**Correct Answer:** A </code>
