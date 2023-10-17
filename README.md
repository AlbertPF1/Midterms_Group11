# Midterms_Group11_MEXE-4101

<p align="center">
  <img src="https://github.com/AlbertPF1/Midterms_Group11/assets/143917422/0b901445-abe7-41e7-aa9e-54a07c15c608">
</p>

**Authors**: _Arellano, Justin Joe M., Dela Peña, Ralph Nathanael A. and Fajardo, Lenard Albert P._

# TEXT FUNCTION


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

![floor](https://github.com/AlbertPF1/Midterms_Group11/assets/143917422/6b453df3-4c1c-47c3-901f-de7ec3c36f48)

## EVEN Function
The **EVEN** function is used to round a number up to the nearest even integer. 
- *Syntax:* =EVEN(number)

    - *"number"*: This is the numeric value you want to round up to the nearest even integer.

The EVEN function takes a single argument, which is the number you want to round up to the nearest even integer. When you use the EVEN function, it rounds the number up to the next even integer. If the number is already an even integer, it remains unchanged.

![EVEN](https://github.com/AlbertPF1/Midterms_Group11/assets/143917422/05ac8c27-bbae-4bda-badd-933592e2ac3f)


## ODD Function
The **ODD** function is used to round a number up to the nearest odd integer. 
- *Syntax:* =ODD(number)

    - *"number"*: This is the numeric value you want to round up to the nearest even integer.

The ODD function takes a single argument, which is the number you want to round up to the nearest odd integer. When you use the ODD function, it rounds the number up to the next odd integer. If the number is already an odd integer, it remains unchanged.

![ODD](https://github.com/AlbertPF1/Midterms_Group11/assets/143917422/10dc07fc-570c-4ac0-a6de-795e3657b71c)


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
   
![ROUND](https://github.com/AlbertPF1/Midterms_Group11/assets/143917422/d5f08788-f3d6-4afa-abfa-41f27fa937f8)

# Logical Functions
## IF Function

## ISBLANK Function

## NOT Function

## SUMIF Function

## COUNTIF Function

# Information Functions
## ISTEXT Function
- *Description:* The ISTEXT function in Excel is used to check if a given value is text (including numbers entered as text). It returns TRUE if the value is text and FALSE if it's not.

- *Usage:*
  - Basic syntax: =ISTEXT(value)
  - Example: =ISTEXT(A1) will return TRUE if the content of cell A1 is text, and FALSE if it's not.
  
## ISNUMBER Function
- *Description:* The ISNUMBER function is used to check if a given value is a numeric value (including numbers, dates, and times). It returns TRUE if the value is a number and FALSE if it's not.

- *Usage:*
  - Basic syntax: =ISNUMBER(value)
  - Example: =ISNUMBER(B2) will return TRUE if the content of cell B2 is a number, and FALSE if it's not.

## TYPE Function
- *Description:* The TYPE function is used to determine the type of data in a cell. It returns an integer that corresponds to the type of data (e.g., 1 for numbers, 2 for text, 4 for logical values, etc.).

- *Usage:*
  - Basic syntax: =TYPE(value)
  - Example: =TYPE(C3) will return 2 if the content of cell C3 is text.

## ISODD Function
- *Description:* The ISODD function checks if a given number is an odd integer. It returns TRUE if the number is odd and FALSE if it's not.

- *Usage:*
  - Basic syntax: =ISODD(value)
  - Example: =ISODD(D4) will return TRUE if the content of cell D4 is an odd number, and FALSE if it's not.

## ISEVEN Function
- *Description:* The ISEVEN function checks if a given number is an even integer. It returns TRUE if the number is even and FALSE if it's not.

- *Usage:*
  - Basic syntax: =ISEVEN(value)
  - Example: =ISEVEN(E5) will return TRUE if the content of cell E5 is an even number, and FALSE if it's not.
 
# Date and Time Functions
The **"NOW" and "TODAY"** function are used to display the current date and time or just the current date, respectively. These functions are useful when you need to insert the current date and time into a cell or use them in calculations.

- *Syntax:* =NOW() , =TODAY()

The "NOW" function returns the current date and time. The "TODAY" function, on the other hand, returns only the current date (without the time). 

Like the NOW function, the TODAY function doesn't require any arguments. It retrieves the current date from your computer's system clock and displays it in the cell.

The TODAY function is often used to track dates or for date-related calculations where you don't need the time component.

Both the NOW and TODAY functions can be particularly useful in various scenarios, including record-keeping, project management, and data analysis, where tracking or referencing the current date and time is essential.

![NOW   TODAY](https://github.com/AlbertPF1/Midterms_Group11/assets/143917422/2497ce68-e4cb-4596-b64a-13ebadf57bb2)

The **"DAY," "MONTH," and "YEAR"** function are used to extract the day, month, and year components, respectively, from a date value. These functions are helpful when you have a date in a cell and you want to extract specific parts of that date. 

- *Syntax:* =DAY(date) , =MONTH(date), =YEAR(date)
    - *"date"*: This  is the cell reference or a date value from which you want to extract the day, month or year.

The "DAY" function is used to extract the day component from a date. The "MONTH" function is used to extract the month component from a date. The "YEAR" function is used to extract the year component from a date. 

These functions are particularly useful for various data analysis and reporting tasks where you have a date field, and you want to perform calculations or create reports based on the individual components of the date, such as day, month, or year.

![1D](https://github.com/AlbertPF1/Midterms_Group11/assets/143917422/06314533-0288-49c1-9edb-2cb6c08b99d9)![2D](https://github.com/AlbertPF1/Midterms_Group11/assets/143917422/fabd8aea-6e7b-421c-8ab2-bd68ea57ae2f)

The **WEEKNUM** function is used to determine the week number for a specified date. The WEEKNUM function returns the week number within the year for a given date.

- *Syntax:* =WEEKNUM(date, [return_type])

    - *"date"*: This is the date for which you want to determine the week number. You can enter the date as a cell reference, a date value, or a formula that results in a date.

    - *"[return_type]"*(optional): This argument specifies the method for determining the week number, and it is an optional argument. If you omit it, Excel assumes a default value of 1.

      - If you omit [return_type] or set it to 1, the WEEKNUM function will return week numbers according to the system's default. The week containing January 1 is considered week 1.
         
      - If you set [return_type] to 2, the WEEKNUM function will return week numbers according to ISO standards. In this system, the first week of the year is the one that contains the first Thursday.

The WEEKNUM function is useful in various business and project management scenarios where you need to track tasks, deadlines, or events by week number. It allows you to quickly categorize and organize data based on the week in the year.

![1A](https://github.com/AlbertPF1/Midterms_Group11/assets/143917422/1dd000af-3730-4c80-b285-b7a8bbba220e)![2A](https://github.com/AlbertPF1/Midterms_Group11/assets/143917422/2f7eca8a-8904-421d-af20-417e8ccb5d09)

The **EDATE** function  is used to calculate the date that is a specified number of months before or after a given date. The function is particularly useful when you need to work with dates in financial or project management calculations.
- *Syntax:* =EDATE(start_date, months)

    - *"start_date"*: This is the initial date from which you want to calculate a new date. You can enter the date as a cell reference, a date value, or a formula that results in a date.

    - *"months"*: This is the number of months by which you want to adjust the start_date. You can use a positive value to calculate a future date or a negative value to calculate a past date.

The EDATE function is versatile and is commonly used in various financial calculations, project planning, and scheduling tasks. It allows you to project or calculate future or past dates based on a starting date and the desired number of months.

![1B](https://github.com/AlbertPF1/Midterms_Group11/assets/143917422/48c351b4-419b-45ab-872e-0e4f50d51b24)![2B](https://github.com/AlbertPF1/Midterms_Group11/assets/143917422/0f67d394-bc93-43df-8dc0-3dc4263ca1df)

The **EOMONTH** function  is used to calculate the last day of the month for a specified number of months before or after a given date. The EOMONTH function is helpful when you need to find the end of a specific month, which can be particularly useful in financial or project management calculations.
- *Syntax:* =EOMONTH(start_date, months)

    - *"start_date"*: This is the initial date from which you want to calculate the last day of a month. You can enter the date as a cell reference, a date value, or a formula that results in a date.

    - *"months"*: This is the number of months by which you want to adjust the start_date. You can use a positive value to calculate the last day of a future month or a negative value to calculate the last day of a past month.

The EOMONTH function is a valuable tool for various date-related calculations, especially when you need to determine due dates, report periods, or financial closing dates based on a starting date and the desired number of months.

![1B](https://github.com/AlbertPF1/Midterms_Group11/assets/143917422/8a2862fc-e63d-4427-8b80-bd4f2fb8c3b1)![1E](https://github.com/AlbertPF1/Midterms_Group11/assets/143917422/1dde9168-3093-407c-a468-8e6a86afe289)



# Lookup Functions
