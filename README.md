# Midterms_Group11_MEXE-4101

<p align="center">
  <img src="https://github.com/AlbertPF1/Midterms_Group11/assets/143917422/0b901445-abe7-41e7-aa9e-54a07c15c608">
</p>

**Authors**: _Arellano, Justin Joe M., Dela Peña, Ralph Nathanael A. and Fajardo, Lenard Albert P._

<p align="center">
  <img src="https://github.com/RalphNathanDP/Midterms_Group11/assets/144073436/798832d9-c372-4fe0-9701-61ff0538f8df">
</p>

# LENGTH Function
The **LENGTH** function is used to determine the length of a text string.

- *Syntax:* =LEN(text)

<p align="center">
  <img src="https://github.com/AlbertPF1/Midterms_Group11/assets/143917422/40fe013e-5d29-4a5e-993b-28cb6de5a190">
</p>

# TRIM Function
The **TRIM** function is used to remove extra spaces from a text string, leaving only a single space between words. 

- *Syntax:* =TRIM(text)

<p align="center">
  <img src="https://github.com/AlbertPF1/Midterms_Group11/assets/143917422/92311741-e1ad-45b4-b214-f807ae72c4d4">
</p>

# UPPER Function
The **UPPER** function is used to convert all the letters in a text string to uppercase. 

- *Syntax:* =UPPER(text)

<p align="center">
  <img src="https://github.com/AlbertPF1/Midterms_Group11/assets/143917422/c4367cbb-9730-4115-9634-4f5d869d364a">
</p>

# LOWER Function
The **LOWER** function is used to convert all the letters in a text string to lowercase. 

- *Syntax:* =LOWER(text)

<p align="center">
  <img src="https://github.com/AlbertPF1/Midterms_Group11/assets/143917422/a98ea8a6-f2ca-4ad3-9f7c-b159b0ac73f1">
</p>

# PROPER Function
The **PROPER** function is used to convert the first letter of each word in a text string to uppercase and all other letters to lowercase.

- *Syntax:* =PROPER(text)

<p align="center">
  <img src="https://github.com/AlbertPF1/Midterms_Group11/assets/143917422/a57cefd2-301d-4af9-b469-ab2529119014">
</p>

<p align="center">
  <img src="https://github.com/RalphNathanDP/Midterms_Group11/assets/144073436/7ac17886-6d55-4aa9-a12e-3872093316be">
</p>

# CEILING Function
The **CEILING** function is used to round a number *"up"* to the nearest multiple of a specified significance or increment. It's a mathematical function that can be particularly useful when you want to ensure that a value is always rounded up to the nearest desired level or step.

- *Syntax:* =CEILING(number, significance)

    - *"number"*: This is the numeric value that you want to round up. 

    - *"significance"*: This is the multiple to which you want to round the number. The function rounds the "number" up to the nearest value that is a multiple of the "significance." 

Here's how the CEILING function works:

1. It takes the "number" and divides it by the "significance."
2. It then rounds up to the nearest integer.
3. Finally, it multiplies the rounded-up integer by the "significance" to give you the rounded-up result.


<p align="center">
  <img src="https://github.com/AlbertPF1/Midterms_Group11/assets/143917422/c8a89dba-3bb8-422b-a785-f5cdd20713d7">
</p>

# FLOOR Function
The **FLOOR** function is used to round a number *"down"* to the nearest multiple of a specified significance or increment. It's a mathematical function that can be particularly useful when you want to ensure that a value is always rounded up to the nearest desired level or step.

- *Syntax:* =FLOOR(number, significance)

    - *"number"*: This is the numeric value that you want to round up. 

    - *"significance"*: This is the multiple to which you want to round the number. The function rounds the "number" down to the nearest value that is a multiple of the "significance." 

Here's how the FLOOR function works:

1. It takes the "number" and divides it by the "significance."
2. It then rounds down to the nearest integer.
3. Finally, it multiplies the rounded-down integer by the "significance" to give you the rounded-down result.

<p align="center">
  <img src="https://github.com/AlbertPF1/Midterms_Group11/assets/143917422/6b453df3-4c1c-47c3-901f-de7ec3c36f48">
</p>


# EVEN Function
The **EVEN** function is used to round a number up to the nearest even integer. 
- *Syntax:* =EVEN(number)

    - *"number"*: This is the numeric value you want to round up to the nearest even integer.

The EVEN function takes a single argument, which is the number you want to round up to the nearest even integer. When you use the EVEN function, it rounds the number up to the next even integer. If the number is already an even integer, it remains unchanged.

<p align="center">
  <img src="https://github.com/AlbertPF1/Midterms_Group11/assets/143917422/05ac8c27-bbae-4bda-badd-933592e2ac3f">
</p>


# ODD Function
The **ODD** function is used to round a number up to the nearest odd integer. 
- *Syntax:* =ODD(number)

    - *"number"*: This is the numeric value you want to round up to the nearest even integer.

The ODD function takes a single argument, which is the number you want to round up to the nearest odd integer. When you use the ODD function, it rounds the number up to the next odd integer. If the number is already an odd integer, it remains unchanged.

<p align="center">
  <img src="https://github.com/AlbertPF1/Midterms_Group11/assets/143917422/10dc07fc-570c-4ac0-a6de-795e3657b71c">
</p>


# ROUND Function
The **ROUND** function is used to round a number to a specified number of decimal places. The ROUND function helps you control the precision of numerical values in your spreadsheets.
- *Syntax:* =ROUND(number, num_digits)

    - *"number"*: This is the numeric value you want to round.

    - *"num_digits    "*: This is the number of decimal places to which you want to round the number.

Here's a breakdown of how the ROUND function works:

1. "number": This is the value you want to round. It can be a cell reference, a constant, or a formula that results in a numeric value.
2. "num_digits": This argument specifies the number of decimal places to which you want to round the number. It can be a positive or negative integer.
    - If num_digits is a positive integer, the function rounds the number to that many decimal places. For example, if num_digits is 2, the function will round to two decimal places.

    - If num_digits is zero, the function rounds to the nearest whole number.

    - If num_digits is a negative integer, the function rounds to the left of the decimal point. For example, if num_digits is -1, the function rounds to the nearest ten, making the number end in zero.

<p align="center">
  <img src="https://github.com/AlbertPF1/Midterms_Group11/assets/143917422/d5f08788-f3d6-4afa-abfa-41f27fa937f8">
</p>


<p align="center">
  <img src="https://github.com/RalphNathanDP/Midterms_Group11/assets/144073436/3ce0bf94-5ee9-4d9e-99a2-893e22d3d7fb">
</p>

# IF Function
The **IF** function in Excel is one of the most popular and useful functions in the program. It allows you to make a logical comparison between a value and what you expect and return a different result depending on whether the comparison is true or false.
- *Syntax:* =IF(logical_test, value_if_true, value_if_false)

    - *"Logical_test"*: This is the comparison that you want to perform. It can be any expression that can be evaluated to TRUE or FALSE. For example, you could compare two numbers, two text strings, or a cell value to a constant.

    - *"Value_if_true"*: This is the value that you want to return if the logical test evaluates to TRUE.
 
    - *"Value_if_false"*: This is the value that you want to return if the logical test evaluates to FALSE.

<p align="center">
  <img src="https://github.com/AlbertPF1/Midterms_Group11/assets/144073436/d243231c-22c0-440e-a696-500e01cc6cf1">
</p>

  
# ISBLANK Function
The **ISBLANK** function is a logical function that checks whether a specified cell is empty or not. It returns TRUE if the cell is empty and FALSE if the cell contains any value. This includes spaces, formulas, or empty text ("").
- *Syntax:* =ISBLANK(reference)

    - *"reference"*: The cell or range of cells you want to check. If the reference is empty, the function returns TRUE; otherwise, it returns FALSE.

<p align="center">
  <img src="https://github.com/AlbertPF1/Midterms_Group11/assets/144073436/45eed2b1-cea7-4a79-8897-8a8541c897a7">
</p>


# NOT Function
The **NOT** function is a logical function that reverses the logical value of its argument. It is used to negate a logical value, meaning it converts TRUE to FALSE and FALSE to TRUE
- *Syntax:* =NOT(logical)

    - *"logical"*: The value or expression that you want to negate. It can be a logical value, a comparison, or any other expression that results in a logical value (TRUE or FALSE)

<p align="center">
  <img src="https://github.com/AlbertPF1/Midterms_Group11/assets/144073436/f8d821db-2e49-4400-86a0-47cedc42b30f">
</p>


# SUMIF Function
The **SUMIF** function in Excel adds all of the values in a range that meet a single criterion. The criterion can be a number, a text string, a date, or a logical expression.
- *Syntax:* =SUMIF(range, criteria, sum_range)

    - *"sum_range"*: The range of cells that you want to sum.
      
    - *"criteria"*: The criterion that you want to use to filter the sum_range.
      
    - *"sum_range_if_true"*: The range of cells that you want to sum if the criterion is met.
<p align="center">
  <img src="https://github.com/AlbertPF1/Midterms_Group11/assets/144073436/36bd2780-0cc1-4b06-90d5-8bdc3cd998ce">
</p>

      
# COUNTIF Function
The **COUNTIF** function is used to count the number of cells within a specified range that meet a given condition or criteria. It allows you to count cells based on a single condition.
- *Syntax:* =COUNTIF(range, criteria)

    - *"range"*: This is the range of cells that you want to apply the criteria against. 
      
    - *"criteria"*: This is the condition that defines which cells in the range should be counted.
<p align="center">
  <img src="https://github.com/AlbertPF1/Midterms_Group11/assets/144073436/708920f4-405a-4d59-a256-1643ad3f1dda">
</p>

<p align="center">
  <img src="https://github.com/RalphNathanDP/Midterms_Group11/assets/144073436/6a97ddf6-5a72-433d-91e0-a6342c15ae9f">
</p>
      
# ISTEXT Function
The **ISTEXT** function is used to check if a given value is a text data type.

- *Syntax:* =ISTEXT(value)
<p align="center">
  <img src="https://github.com/Diyastin/Midterms_Group11/assets/144225180/1abb2d86-d8cd-4d3c-a242-1ac1c41eb1d2">
</p>

# ISNONTEXT Function
The **ISNONTEXT** function helps to check if a cell contains text or not.

- *Syntax:* =ISNONTEXT(value)

<p align="center">
  <img src="https://github.com/AlbertPF1/Midterms_Group11/assets/143917422/c22002c8-d5f1-41f6-ad01-7b725fa061cd">
</p>

# ISNUMBER Function
The **ISNUMBER** function is used to check whether a given value is a number.

- *Syntax:* =ISNUMBER(value)

<p align="center">
  <img src="https://github.com/AlbertPF1/Midterms_Group11/assets/143917422/a6107dfb-3896-4498-bf97-ad895e808b15">
</p>

# ISBLANK Function
The **ISBLANK** function is used to check whether a specified cell is empty.

- *Syntax:* =ISBLANK(value)

<p align="center">
  <img src="https://github.com/AlbertPF1/Midterms_Group11/assets/143917422/b1d8b3b5-db8b-4375-89c4-6fb49c41d93e">
</p>

# ISLOGICAL Function
The **ISLOGICAL** function is used to checks whether a given value is a logical value or not.

- *Syntax:* =ISLOGICAL(value)

<p align="center">
  <img src="https://github.com/AlbertPF1/Midterms_Group11/assets/143917422/32929dba-29a6-4dd6-9d9c-0de911f311e6">
</p>


<p align="center">
  <img src="https://github.com/RalphNathanDP/Midterms_Group11/assets/144073436/fdabb857-f693-42c3-a52b-eaa341397aae">
</p>

# NOW AND TODAY FUNCTION
The **"NOW" and "TODAY"** function are used to display the current date and time or just the current date, respectively. These functions are useful when you need to insert the current date and time into a cell or use them in calculations.

- *Syntax:* =NOW() , =TODAY()

The "NOW" function returns the current date and time. The "TODAY" function, on the other hand, returns only the current date (without the time). 

Like the NOW function, the TODAY function doesn't require any arguments. It retrieves the current date from your computer's system clock and displays it in the cell.

The TODAY function is often used to track dates or for date-related calculations where you don't need the time component.

Both the NOW and TODAY functions can be particularly useful in various scenarios, including record-keeping, project management, and data analysis, where tracking or referencing the current date and time is essential.

<p align="center">
  <img src="https://github.com/AlbertPF1/Midterms_Group11/assets/143917422/2497ce68-e4cb-4596-b64a-13ebadf57bb2">
</p>

# DAY, MONTH, AND YEAR FUNCTION
The **"DAY," "MONTH," and "YEAR"** function are used to extract the day, month, and year components, respectively, from a date value. These functions are helpful when you have a date in a cell and you want to extract specific parts of that date. 

- *Syntax:* =DAY(date) , =MONTH(date), =YEAR(date)
    - *"date"*: This  is the cell reference or a date value from which you want to extract the day, month or year.

The "DAY" function is used to extract the day component from a date. The "MONTH" function is used to extract the month component from a date. The "YEAR" function is used to extract the year component from a date. 

These functions are particularly useful for various data analysis and reporting tasks where you have a date field, and you want to perform calculations or create reports based on the individual components of the date, such as day, month, or year.

<p align="center">
  <img src="https://github.com/AlbertPF1/Midterms_Group11/assets/143917422/432cecfd-7dd3-4fa5-bff9-e82c7e1fbfbe">
</p>

# WEEKNUM FUNCTION
The **WEEKNUM** function is used to determine the week number for a specified date. The WEEKNUM function returns the week number within the year for a given date.

- *Syntax:* =WEEKNUM(date, [return_type])

    - *"date"*: This is the date for which you want to determine the week number. You can enter the date as a cell reference, a date value, or a formula that results in a date.

    - *"[return_type]"*(optional): This argument specifies the method for determining the week number, and it is an optional argument. If you omit it, Excel assumes a default value of 1.

      - If you omit [return_type] or set it to 1, the WEEKNUM function will return week numbers according to the system's default. The week containing January 1 is considered week 1.
         
      - If you set [return_type] to 2, the WEEKNUM function will return week numbers according to ISO standards. In this system, the first week of the year is the one that contains the first Thursday.

The WEEKNUM function is useful in various business and project management scenarios where you need to track tasks, deadlines, or events by week number. It allows you to quickly categorize and organize data based on the week in the year.

<p align="center">
  <img src="https://github.com/AlbertPF1/Midterms_Group11/assets/143917422/da0065af-c72f-42db-a4dc-973aa1ab6688">
</p>

# EDATE FUNCTION
The **EDATE** function  is used to calculate the date that is a specified number of months before or after a given date. The function is particularly useful when you need to work with dates in financial or project management calculations.
- *Syntax:* =EDATE(start_date, months)

    - *"start_date"*: This is the initial date from which you want to calculate a new date. You can enter the date as a cell reference, a date value, or a formula that results in a date.

    - *"months"*: This is the number of months by which you want to adjust the start_date. You can use a positive value to calculate a future date or a negative value to calculate a past date.

The EDATE function is versatile and is commonly used in various financial calculations, project planning, and scheduling tasks. It allows you to project or calculate future or past dates based on a starting date and the desired number of months.

<p align="center">
  <img src="https://github.com/AlbertPF1/Midterms_Group11/assets/143917422/2c4597e0-5773-4050-a946-3d8943c7c2c3">
</p>

# EOMONTH FUNCTION
The **EOMONTH** function  is used to calculate the last day of the month for a specified number of months before or after a given date. The EOMONTH function is helpful when you need to find the end of a specific month, which can be particularly useful in financial or project management calculations.
- *Syntax:* =EOMONTH(start_date, months)

    - *"start_date"*: This is the initial date from which you want to calculate the last day of a month. You can enter the date as a cell reference, a date value, or a formula that results in a date.

    - *"months"*: This is the number of months by which you want to adjust the start_date. You can use a positive value to calculate the last day of a future month or a negative value to calculate the last day of a past month.

The EOMONTH function is a valuable tool for various date-related calculations, especially when you need to determine due dates, report periods, or financial closing dates based on a starting date and the desired number of months.

<p align="center">
  <img src="https://github.com/AlbertPF1/Midterms_Group11/assets/143917422/6f22e88d-d2a4-48f0-bd20-76da19e9a9eb">
</p>

<p align="center">
  <img src="https://github.com/RalphNathanDP/Midterms_Group11/assets/144073436/c662bd76-7c25-4dbe-9c83-911f0c2621c0">
</p>

# LOOKUP Function
The **LOOKUP** function is used to search for a value in a single row or column and return a corresponding value from the same position in another row or column.
 - *Syntax:* =LOOKUP(lookup_value, lookup_vector, [result_vector])

    - *"lookup_value"*: is a value that LOOKUP searches for in the first vector. Lookup_value can be a number, text, a logical value, or a name or reference that refers to a value.
  
    - *"lookup_vector"*: is a range that contains only one row or one column. The values in lookup_vector can be text, numbers, or logical values.
  
    - *"result_vector"*: is a range that contains only one row or column. The result_vector argument must be the same size as lookup_vector. It has to be the same size.

<p align="center">
  <img src="https://github.com/AlbertPF1/Midterms_Group11/assets/143917422/9db5fce1-196d-4c27-a062-5be94b2f78b5">
</p>

# MATCH Function
The **MATCH** function searches for a specified item in a range of cells, and then returns the relative position of that item in the range.
- *Syntax:* =MATCH(lookup_value, lookup_array, [match_type])

    - *"lookup_value"*: The value that you want to match in lookup_array. 
  
    - *"lookup_array"*: The range of cells being searched.
  
    - *"match_type"*: The number -1, 0, or 1. The match_type argument specifies how Excel matches lookup_value with values in lookup_array. The default value for this argument is 1. 1 MATCH finds the largest value that is less than or equal to lookup_value. 0 MATCH finds the first value that is exactly equal to lookup_value. -1 MATCH finds the smallest value that is greater than or equal tolookup_value.
  
<p align="center">
  <img src="https://github.com/AlbertPF1/Midterms_Group11/assets/143917422/e1cc1b76-daac-4a44-ac04-91bf5a7db72a">
</p>

# VLOOKUP Function
The **VLOOKUP** function is used to search for a value in the first column of a table or an array, and then return a value in the same row from a specified column. The "V" in VLOOKUP stands for "vertical," indicating that the function searches vertically (in columns) for the specified value. VLOOKUP is incredibly useful when you have a large dataset and you want to find specific information based on a known value.
- *Syntax:* =VLOOKUP(lookup_value, table_array, col_index_num, [range_lookup])

    - *"lookup_value"*: The value you want to search for in the first column of the table_array.
  
    - *"table_array"*: The range of cells that contains the data you want to search in. The lookup value should be in the first column of this range.
    - *"col_index_num*": The column number in the table_array from which to retrieve the value to return.
    - *"[range_lookup]*": This is an optional argument. If TRUE or omitted, an approximate match is returned. If FALSE, an exact match is required. In most cases, you'll want to use FALSE to ensure you get an exact match.

<p align="center">
  <img src="https://github.com/AlbertPF1/Midterms_Group11/assets/143917422/1bdb1a9c-393d-47dd-b9c8-cd7d1bf208c3">
</p>

# COLUMNS Function
The **COLUMNS** function is used to count the number of columns in a specified array or range of cells. This function can be particularly useful when you want to know how many columns are there in a specific range or when you want to perform calculations based on the number of columns in a range.
- *Syntax:* =COLUMNS(array)

    - *"array"*: This is the range of cells or an array for which you want to count the number of columns.

<p align="center">
  <img src="https://github.com/AlbertPF1/Midterms_Group11/assets/143917422/c5fcaf78-dab3-4232-8a6e-27b1c4fd8369">
</p>

# INDIRECT Function
The **INDIRECT** function in Excel is used to convert a text string representing a cell reference or range name into an actual reference. In other words, it allows you to create a reference from text. This can be particularly useful in situations where you have a cell containing a reference as text, and you want to use that reference in a formula.
- *Syntax:* =INDIRECT(ref_text, [a1])

    - *"ref_text: This is the text string that contains the reference to a cell or a range of cells.
[a1]: This is an optional argument. If a1 is TRUE or omitted, ref_text is interpreted as an A1-style reference. If a1 is FALSE, ref_text is interpreted as an R1C1-style reference.

<p align="center">
  <img src="https://github.com/AlbertPF1/Midterms_Group11/assets/143917422/bfb90882-fe30-4bb8-8207-af11c55f9429">
</p>

# DASHBOARD

These dashboards below were based on the E-Commerce Sales Dataset Analyzing and Maximizing Online Business Performance. This Dataset is about the Amazon Sale report in India.
<p align="center">
  <img src="https://github.com/RalphNathanDP/Midterms_Group11/assets/144073436/e66a53fb-bf4b-4929-8324-b99847bbe236">
</p>

## Total Sales per State
<p align="center">
  <img src="https://github.com/AlbertPF1/Midterms_Group11/assets/143917422/b488348f-7654-4ac4-99f3-0ac814f3a550">
</p>

## Order Status per State  
<p align="center">
  <img src="https://github.com/AlbertPF1/Midterms_Group11/assets/143917422/57ba6f4c-f041-42c3-acb4-af31474a6d14">
</p>

## Total Orders per Category
<p align="center">
  <img src="https://github.com/AlbertPF1/Midterms_Group11/assets/143917422/bb172c2c-019f-49aa-a29a-f5a3a05041cb">
</p>

## Number of Orders per Date
<p align="center">
  <img src="https://github.com/AlbertPF1/Midterms_Group11/assets/143917422/a87d798d-e3a8-4747-8166-93d38acb2610">
</p>

## Fulfilment per Category
<p align="center">
  <img src="https://github.com/AlbertPF1/Midterms_Group11/assets/143917422/684b8db0-c0fb-47c4-add6-77644fd6a2c6">
</p>

# References:
E-Commerce Sales Dataset. (2022, December 3). Kaggle. https://www.kaggle.com/datasets/thedevastator/unlock-profits-with-e-commerce-sales-data?select=Amazon+Sale+Report.csv&fbclid=IwAR0GA7NXxkMfcMWKtxGh0I7Jt5DP9NMAQCT5QD6h8B1wTcgk1BD670148Wk

JumpFly, Inc. (2022, December 14). Amazon-com-portable-network-graphics-Transparency-logo-image-PNG-faVPng-8Q7I6DHJBRCNAYYTKHXLQVKDb | JumpFly, Inc. https://www.jumpfly.com/homepage-may-2021/amazon-com-portable-network-graphics-transparency-logo-image-png-favpng-8q7i6dhjbrcnayytkhxlqvkdb/?fbclid=IwAR0tkQSnmHwJ_MBzD8q8gNWMLBTdP-QzZ-d2tb4UgMN6HwiSg2MNmg06Xak

Amazon-Logo-Transparent-PNG | WOSU Public Media. (n.d.). https://wosu.org/television/broad-high-presents/attachment/amazon-logo-transparent-png/?fbclid=IwAR2AgR2TOZrqpK6RlgYblZMQOJZfJ_h-XJ0RLRKs0z7vBDzSxmsvOuaEQd0
