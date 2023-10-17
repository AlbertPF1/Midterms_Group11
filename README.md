# Midterms_Group11_MEXE-4101
![group-11](https://github.com/AlbertPF1/Midterms_Group11/assets/143917422/0b901445-abe7-41e7-aa9e-54a07c15c608)

**Authors**: _Arellano, Justin Joe M., Dela Peña, Ralph Nathanael A. and Fajardo, Lenard Albert P._

# TEXT FUNCTION


# Math Functions
The **CEILING** function is used to round a number *"up"* to the nearest multiple of a specified significance or increment. It's a mathematical function that can be particularly useful when you want to ensure that a value is always rounded up to the nearest desired level or step.

- *Syntax:* =CEILING(number, significance)

    - *"number"*: This is the numeric value that you want to round up. 

    - *"significance"*: This is the multiple to which you want to round the number. The function rounds the "number" up to the nearest value that is a multiple of the "significance." 

Here's how the CEILING function works:

1. It takes the "number" and divides it by the "significance."
2. It then rounds up to the nearest integer.
3. Finally, it multiplies the rounded-up integer by the "significance" to give you the rounded-up result.

![CEILING](https://github.com/AlbertPF1/Midterms_Group11/assets/143917422/c8a89dba-3bb8-422b-a785-f5cdd20713d7)

The **FLOOR** function is used to round a number *"down"* to the nearest multiple of a specified significance or increment. It's a mathematical function that can be particularly useful when you want to ensure that a value is always rounded up to the nearest desired level or step.

- *Syntax:* =FLOOR(number, significance)

    - *"number"*: This is the numeric value that you want to round up. 

    - *"significance"*: This is the multiple to which you want to round the number. The function rounds the "number" down to the nearest value that is a multiple of the "significance." 

Here's how the FLOOR function works:

1. It takes the "number" and divides it by the "significance."
2. It then rounds down to the nearest integer.
3. Finally, it multiplies the rounded-down integer by the "significance" to give you the rounded-down result.

![floor](https://github.com/AlbertPF1/Midterms_Group11/assets/143917422/6b453df3-4c1c-47c3-901f-de7ec3c36f48)

The **EVEN** function is used to round a number up to the nearest even integer. 
- *Syntax:* =EVEN(number)

    - *"number"*: This is the numeric value you want to round up to the nearest even integer.

The EVEN function takes a single argument, which is the number you want to round up to the nearest even integer. When you use the EVEN function, it rounds the number up to the next even integer. If the number is already an even integer, it remains unchanged.

![EVEN](https://github.com/AlbertPF1/Midterms_Group11/assets/143917422/05ac8c27-bbae-4bda-badd-933592e2ac3f)

The **ODD** function is used to round a number up to the nearest odd integer. 
- *Syntax:* =ODD(number)

    - *"number"*: This is the numeric value you want to round up to the nearest even integer.

The ODD function takes a single argument, which is the number you want to round up to the nearest odd integer. When you use the ODD function, it rounds the number up to the next odd integer. If the number is already an odd integer, it remains unchanged.

![ODD](https://github.com/AlbertPF1/Midterms_Group11/assets/143917422/10dc07fc-570c-4ac0-a6de-795e3657b71c)


# Logical Functions

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
## WEEKNUM Function

## WEEKDAY Function

## EDATE Function

## EOMONTH Function

## DAY_MONTH_YEAR Function

# Lookup Functions
