# Midterms_Group11_MEXE-4101

<p align="center">
  <img src="https://github.com/AlbertPF1/Midterms_Group11/assets/143917422/0b901445-abe7-41e7-aa9e-54a07c15c608">
</p>

**Authors**: _Arellano, Justin Joe M., Dela Peña, Ralph Nathanael A. and Fajardo, Lenard Albert P._

# Text Function
The **LENGTH** function is used to determine the length of a text string.

- *Syntax:* =LEN(text)


The **TRIM** function is used to remove extra spaces from a text string, leaving only a single space between words. 

- *Syntax:* =TRIM(text)

The **UPPER** function is used to convert all the letters in a text string to uppercase. 

- *Syntax:* =UPPER(text)

The **LOWER** function is used to convert all the letters in a text string to lowercase. 

- *Syntax:* =LOWER(text)

The **PROPER** function is used to convert the first letter of each word in a text string to uppercase and all other letters to lowercase.

- *Syntax:* =PROPER(text)
  
# Information Functions

The **ISTEXT** function is used to check if a given value is a text data type.

- *Syntax:* =ISTEXT(value)
<p align="center">
  <img src="https://github.com/Diyastin/Midterms_Group11/assets/144225180/1abb2d86-d8cd-4d3c-a242-1ac1c41eb1d2">
</p>


The **ISNONTEXT** function helps to check if a cell contains text or not.

- *Syntax:* =ISNONTEXT(value)

The **ISNUMBER** function is used to check whether a given value is a number.

- *Syntax:* =ISNUMBER(value)

The **ISBLANK** function is used to check whether a specified cell is empty.

- *Syntax:* =ISBLANK(value)

The **ISLOGICAL** function is used to checks whether a given value is a logical value or not.

- *Syntax:* =ISLOGICAL(value)

# Math Functions
## CEILING Function
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

## FLOOR Function
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


## EVEN Function
The **EVEN** function is used to round a number up to the nearest even integer. 
- *Syntax:* =EVEN(number)

    - *"number"*: This is the numeric value you want to round up to the nearest even integer.

The EVEN function takes a single argument, which is the number you want to round up to the nearest even integer. When you use the EVEN function, it rounds the number up to the next even integer. If the number is already an even integer, it remains unchanged.

<p align="center">
  <img src="https://github.com/AlbertPF1/Midterms_Group11/assets/143917422/05ac8c27-bbae-4bda-badd-933592e2ac3f">
</p>


## ODD Function
The **ODD** function is used to round a number up to the nearest odd integer. 
- *Syntax:* =ODD(number)

    - *"number"*: This is the numeric value you want to round up to the nearest even integer.

The ODD function takes a single argument, which is the number you want to round up to the nearest odd integer. When you use the ODD function, it rounds the number up to the next odd integer. If the number is already an odd integer, it remains unchanged.

<p align="center">
  <img src="https://github.com/AlbertPF1/Midterms_Group11/assets/143917422/10dc07fc-570c-4ac0-a6de-795e3657b71c">
</p>


## ROUND Function
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

# Logical Functions
## IF Function
The **IF** function in Excel is one of the most popular and useful functions in the program. It allows you to make a logical comparison between a value and what you expect and return a different result depending on whether the comparison is true or false.
- *Syntax:* =IF(logical_test, value_if_true, value_if_false)

    - *"Logical_test"*: This is the comparison that you want to perform. It can be any expression that can be evaluated to TRUE or FALSE. For example, you could compare two numbers, two text strings, or a cell value to a constant.

    - *"Value_if_true"*: This is the value that you want to return if the logical test evaluates to TRUE.
 
    - *"Value_if_false"*: This is the value that you want to return if the logical test evaluates to FALSE.

<p align="center">
  <img src="https://github.com/AlbertPF1/Midterms_Group11/assets/144073436/d243231c-22c0-440e-a696-500e01cc6cf1">
</p>

  
## ISBLANK Function
The **ISBLANK** function is a logical function that checks whether a specified cell is empty or not. It returns TRUE if the cell is empty and FALSE if the cell contains any value. This includes spaces, formulas, or empty text ("").
- *Syntax:* =ISBLANK(reference)

    - *"reference"*: The cell or range of cells you want to check. If the reference is empty, the function returns TRUE; otherwise, it returns FALSE.

<p align="center">
  <img src="https://github.com/AlbertPF1/Midterms_Group11/assets/144073436/45eed2b1-cea7-4a79-8897-8a8541c897a7">
</p>


## NOT Function
The **NOT** function is a logical function that reverses the logical value of its argument. It is used to negate a logical value, meaning it converts TRUE to FALSE and FALSE to TRUE
- *Syntax:* =NOT(logical)

    - *"logical"*: The value or expression that you want to negate. It can be a logical value, a comparison, or any other expression that results in a logical value (TRUE or FALSE)

<p align="center">
  <img src="https://github.com/AlbertPF1/Midterms_Group11/assets/144073436/f8d821db-2e49-4400-86a0-47cedc42b30f">
</p>


## SUMIF Function
The **SUMIF** function in Excel adds all of the values in a range that meet a single criterion. The criterion can be a number, a text string, a date, or a logical expression.
- *Syntax:* =SUMIF(range, criteria, sum_range)

    - *"sum_range"*: The range of cells that you want to sum.
      
    - *"criteria"*: The criterion that you want to use to filter the sum_range.
      
    - *"sum_range_if_true"*: The range of cells that you want to sum if the criterion is met.
<p align="center">
  <img src="https://github.com/AlbertPF1/Midterms_Group11/assets/144073436/36bd2780-0cc1-4b06-90d5-8bdc3cd998ce">
</p>

      
## COUNTIF Function
The **COUNTIF** function is used to count the number of cells within a specified range that meet a given condition or criteria. It allows you to count cells based on a single condition.
- *Syntax:* =COUNTIF(range, criteria)

    - *"range"*: This is the range of cells that you want to apply the criteria against. 
      
    - *"criteria"*: This is the condition that defines which cells in the range should be counted.
<p align="center">
  <img src="https://github.com/AlbertPF1/Midterms_Group11/assets/144073436/708920f4-405a-4d59-a256-1643ad3f1dda">
</p>

      
# Information Functions
## ISTEXT FUNCTION
The **ISTEXT** function is used to check if a given value is a text data type.

- *Syntax:* =ISTEXT(value)

![image](https://github.com/Diyastin/Midterms_Group11/assets/144225180/1abb2d86-d8cd-4d3c-a242-1ac1c41eb1d2)

## ISNONTEXT Function
The **ISNONTEXT** function helps to check if a cell contains text or not.

- *Syntax:* =ISNONTEXT(value)

## ISNUMBER Function
The **ISNUMBER** function is used to check whether a given value is a number.

- *Syntax:* =ISNUMBER(value)

## ISBLANK Function
The **ISBLANK** function is used to check whether a specified cell is empty.

- *Syntax:* =ISBLANK(value)

## ISLOGICAL Function
The **ISLOGICAL** function is used to checks whether a given value is a logical value or not.

- *Syntax:* =ISLOGICAL(value)


# Date and Time Functions

## NOW AND TODAY FUNCTION
The **"NOW" and "TODAY"** function are used to display the current date and time or just the current date, respectively. These functions are useful when you need to insert the current date and time into a cell or use them in calculations.

- *Syntax:* =NOW() , =TODAY()

The "NOW" function returns the current date and time. The "TODAY" function, on the other hand, returns only the current date (without the time). 

Like the NOW function, the TODAY function doesn't require any arguments. It retrieves the current date from your computer's system clock and displays it in the cell.

The TODAY function is often used to track dates or for date-related calculations where you don't need the time component.

Both the NOW and TODAY functions can be particularly useful in various scenarios, including record-keeping, project management, and data analysis, where tracking or referencing the current date and time is essential.

![NOW   TODAY](https://github.com/AlbertPF1/Midterms_Group11/assets/143917422/2497ce68-e4cb-4596-b64a-13ebadf57bb2)

## DAY, MONTH, AND YEAR FUNCTION
The **"DAY," "MONTH," and "YEAR"** function are used to extract the day, month, and year components, respectively, from a date value. These functions are helpful when you have a date in a cell and you want to extract specific parts of that date. 

- *Syntax:* =DAY(date) , =MONTH(date), =YEAR(date)
    - *"date"*: This  is the cell reference or a date value from which you want to extract the day, month or year.

The "DAY" function is used to extract the day component from a date. The "MONTH" function is used to extract the month component from a date. The "YEAR" function is used to extract the year component from a date. 

These functions are particularly useful for various data analysis and reporting tasks where you have a date field, and you want to perform calculations or create reports based on the individual components of the date, such as day, month, or year.

![1D](https://github.com/AlbertPF1/Midterms_Group11/assets/143917422/06314533-0288-49c1-9edb-2cb6c08b99d9)![2D](https://github.com/AlbertPF1/Midterms_Group11/assets/143917422/fabd8aea-6e7b-421c-8ab2-bd68ea57ae2f)

## WEEKNUM FUNCTION
The **WEEKNUM** function is used to determine the week number for a specified date. The WEEKNUM function returns the week number within the year for a given date.

- *Syntax:* =WEEKNUM(date, [return_type])

    - *"date"*: This is the date for which you want to determine the week number. You can enter the date as a cell reference, a date value, or a formula that results in a date.

    - *"[return_type]"*(optional): This argument specifies the method for determining the week number, and it is an optional argument. If you omit it, Excel assumes a default value of 1.

      - If you omit [return_type] or set it to 1, the WEEKNUM function will return week numbers according to the system's default. The week containing January 1 is considered week 1.
         
      - If you set [return_type] to 2, the WEEKNUM function will return week numbers according to ISO standards. In this system, the first week of the year is the one that contains the first Thursday.

The WEEKNUM function is useful in various business and project management scenarios where you need to track tasks, deadlines, or events by week number. It allows you to quickly categorize and organize data based on the week in the year.

![1A](https://github.com/AlbertPF1/Midterms_Group11/assets/143917422/1dd000af-3730-4c80-b285-b7a8bbba220e)![2A](https://github.com/AlbertPF1/Midterms_Group11/assets/143917422/2f7eca8a-8904-421d-af20-417e8ccb5d09)


## EDATE FUNCTION
The **EDATE** function  is used to calculate the date that is a specified number of months before or after a given date. The function is particularly useful when you need to work with dates in financial or project management calculations.
- *Syntax:* =EDATE(start_date, months)

    - *"start_date"*: This is the initial date from which you want to calculate a new date. You can enter the date as a cell reference, a date value, or a formula that results in a date.

    - *"months"*: This is the number of months by which you want to adjust the start_date. You can use a positive value to calculate a future date or a negative value to calculate a past date.

The EDATE function is versatile and is commonly used in various financial calculations, project planning, and scheduling tasks. It allows you to project or calculate future or past dates based on a starting date and the desired number of months.

![1B](https://github.com/AlbertPF1/Midterms_Group11/assets/143917422/48c351b4-419b-45ab-872e-0e4f50d51b24)![2B](https://github.com/AlbertPF1/Midterms_Group11/assets/143917422/0f67d394-bc93-43df-8dc0-3dc4263ca1df)


## EOMONTH FUNCTION
The **EOMONTH** function  is used to calculate the last day of the month for a specified number of months before or after a given date. The EOMONTH function is helpful when you need to find the end of a specific month, which can be particularly useful in financial or project management calculations.
- *Syntax:* =EOMONTH(start_date, months)

    - *"start_date"*: This is the initial date from which you want to calculate the last day of a month. You can enter the date as a cell reference, a date value, or a formula that results in a date.

    - *"months"*: This is the number of months by which you want to adjust the start_date. You can use a positive value to calculate the last day of a future month or a negative value to calculate the last day of a past month.

The EOMONTH function is a valuable tool for various date-related calculations, especially when you need to determine due dates, report periods, or financial closing dates based on a starting date and the desired number of months.

![1B](https://github.com/AlbertPF1/Midterms_Group11/assets/143917422/8a2862fc-e63d-4427-8b80-bd4f2fb8c3b1)![1E](https://github.com/AlbertPF1/Midterms_Group11/assets/143917422/1dde9168-3093-407c-a468-8e6a86afe289)


# Lookup Functions
## LOOKUP Function

## MATCH Function

## VLOOKUP Function

## COLUMNS Function

## ADDRESS Function

