# Marvel Cinematic Universe Dataset - GROUP8_MOVIES

<div align="center">
  <strong>This repository contains dashboards for Marvel Cinematic Universe Box Office Dataset starting from the year 2008 to year 2021.</strong>
</div>  

<br>

![MCU](https://github.com/aprilrhose/Movie_MCU-Dataset_GROUP8/assets/143881769/bbda7c5f-ed47-44d9-9caf-b40631f4c335)
<br>
<br>
<div align="center">
  Here are the set of data that will be used throughout the discussion. If you want to see it clearly or if you want to have access on the original file, you can go to this link: https://www.kaggle.com/datasets/davidgdong/marvel-cinematic-universe-box-office-dataset/data 
</div>

![DATA SET (1)](https://github.com/aprilrhose/Movie_MCU-Dataset_GROUP8/assets/143881769/742c9cf8-9773-40a5-9d22-84fb8da208d4)

<br>

# Text Function

In Microsoft Excel, the **TEXT function** is a function that allows you to format a numeric value as text based on a specified format code. You can use this function to display texts, numbers, dates, and times in a way that makes them more readable, user-friendly or adheres to a specific format. This function is valuable for creating custom-formatted labels, data exports, reports, and more. For this part, LEN function, UPPER function, LOWER function, Proper Function, and LEFT function will be shown.
<br>
<br>


**LEN Function**
<br>
>The **LEN function** is used to count the number of characters in a given text string, including letters, numbers, symbols, and spaces. The basic syntax for this function  is **=LEN(text)**. 

>For example, if cell A1 contains the text "Iron Man", then you can use **=LEN(A1).** The result will be 8 as there are 8 characters in the text including letters, comma, and spaces.

<p align="center">
  <img src="https://github.com/aprilrhose/Movie_MCU-Dataset_GROUP8/assets/143881769/cc708df8-ec60-4c8b-9e78-260b0e57e828">
</p>
<br>

**UPPER Function**

>The **UPPER function** is a text function that is used to convert all the letters in a given text string to uppercase. It is a simple yet valuable tool for text manipulation and data processing. The basic syntax for this function is **=UPPER(text)**.

>For example, if cell A1 contains the text "Iron Man", then you can use **=UPPER(A1).** The result will be "IRON MAN" as all the letters are converted to uppercase.

<p align="center">
  <img src="https://github.com/aprilrhose/Movie_MCU-Dataset_GROUP8/assets/143881769/02d64771-65e4-4cb7-93e3-65df5b0d575c">
</p>
<br>

**LOWER Function**

>The **LOWER function** is a text function used to convert all the letters in a given text string to lowercase. Same with UPPER function, it is also a fundamental tool for text manipulation and data processing. The basic syntax for this function is **=LOWER(text)**.

>For example, if cell A1 contains the text "Thor" or "THOR", then you can use **=LOWER(A1).** The result will be "thor" as all the letters are converted to lowercase.

<p align="center">
  <img src="https://github.com/aprilrhose/Movie_MCU-Dataset_GROUP8/assets/143881769/c802a37e-66a7-4be0-b0e3-7d2947f0c44a">
</p>

**PROPER Function**
>The **PROPER function** is a text function used to capitalize the first letter of each word in a text string while converting the rest of the letters to lowercase. It is a valuable tool for text manipulation, especially when dealing with data where you want to ensure consistent and well-formatted capitalization. The basic syntax for this function is **=PROPER(text)**.

>For example, if cell A1 contains the text "Guardians of the Galaxy," then you can use **=PROPER(A1).** The result will be "Guardians Of The Galaxy" as the first letter of each word is capitalized.
<p align="center">
  <img src="https://github.com/aprilrhose/Movie_MCU-Dataset_GROUP8/assets/143881769/61ea976d-d8da-4eef-aec2-bc53821b25dc">
</p>

**LEFT Function**
>The **LEFT function** is a text function that is used to extract a specified number of characters from the beginning or on the left side of a text string. It is a simple yet highly important tool for text manipulation and data extraction tasks. The basic syntax for this function is **=LEFT(text, num_chars)**.

>For example, if cell B4 contains the text "Iron Man" and you want to extract the first 4 characters, then you can use **=LEFT(B4, 4).** The result will be "Iron".

<p align="center">
  <img src="https://github.com/aprilrhose/Movie_MCU-Dataset_GROUP8/assets/143881769/a4ef7a44-61c1-4759-b732-be4d49c40cc5">
</p>

<br>
<br>

<div align="center">
  <strong>Overall, the TEXT function is a versatile tool in Excel that plays a significant role in data formatting and presentation, making data more understandable and visually appealing. It's widely used in financial, accounting, and data analysis tasks, among others.</strong>
</div>

<br>
<br>

# Math Functions

Math Function generally refers to a category of mathematical functions and operations that can be performed in mathematical calculations within Excel and similar programs. For this part, SUM function, AVERAGE function, MIN & MAC function, ROUND Function, and TRUNC function will be shown.
<br>
<br>

**SUM Function**

>The **SUM function** is one of the most fundamental and widely used mathematical functions. It is essential for adding a range of numbers together. The basic syntax for this function is **=SUM(number1, number2, ...)**.

>For example, if you have a range of numbers in cells A1 to A5, you can use **=SUM(A1:A5)**

>The SUM function will add up all the values in cells A1 to A5 and return the total.
<br>
<div align="center">
  <strong>For this table of values, SUM function was used to get the total sales of the movies from its opening weekend,</strong>
</div>
<div align="center">
  <strong>its domestic box office and from its worldwide box office.</strong>
</div>

<p align="center">
  <img src="https://github.com/aprilrhose/Movie_MCU-Dataset_GROUP8/assets/143881769/99a131b7-7208-409a-aa04-8de18144db21">
</p>
<br>

**AVERAGE Function**

>The **AVERAGE function** is a mathematical function used to calculate the average or arithmetic mean of a set of numbers. It is an essential tool for analyzing data and deriving a central tendency or average value. The basic syntax for this function is **=AVERAGE(number1, number2, ...)**

>For example, if you have a range of test scores in cells A1 to A10, you can use **=AVERAGE(A1:A10)**

>The AVERAGE function will calculate the average of the test scores in cells A1 to A10 and return the result.

<br>
<div align="center">
  <strong>For this table of values, AVERAGE function was used to get the average sales of the movies from its opening weekend,</strong>
</div>
<div align="center">
  <strong>its domestic box office and from its worldwide box office.</strong>
</div>

<p align="center">
  <img src="https://github.com/aprilrhose/Movie_MCU-Dataset_GROUP8/assets/143881769/c593455b-bece-4f40-98d9-f26762325e33">
</p>
<br>


**MIN & MAX Function**

>The **MIN and MAX Functions** are mathematical functions used to find the minimum (lowest) and maximum (highest) values within a range of numbers or cells, respectively. These functions are essential for various tasks, particularly when you need to identify the extremes or boundaries of a dataset.

>The **MIN Function** is used to find the smallest value in a set of numbers. The basic syntax for this function is **=MIN(number1, number2, ...)** where **number1, number2, ...** represents the individual numbers or cell references you want to compare to find the minimum value.

>For example, if you have a range of test scores in cells A1 to A10, you can use **=MIN(A1:A10).** It will return the lowest test score in that range.

>**MAX Function**, on the other hand, is used to find the largest value in a set of numbers. The basic syntax for this function is **=MAX(number1, number2, ...)**

>If you have a range of sales figures in cells B1 to B10, you can use **=MAX(B1:B10).** It will return the highest sales figure in that range.
<br>

<div align="center">
  <strong>For this table of values, MIN and MAX functions were used to get the minimum and maximum sales of the movies</strong>
</div>
<div align="center">
  <strong>from its opening weekend, its domestic box office and from its worldwide box office.</strong>
</div>
<p align="center">
  <img src="https://github.com/aprilrhose/Movie_MCU-Dataset_GROUP8/assets/143881769/e41c389c-db14-4e32-abec-c4098ea4b2e3">
</p>
<br>
<br>

**ROUND Function**

>The **ROUND function** is a mathematical function used to round a number to a specified number of decimal places. It is important for several reasons and plays a critical role in various applications. The basic syntax for this function **is =ROUND(number, num_digits)**

>The **number** is the number you want to round while the **num_digits** is the number of decimal places to which you want to round the number.

>For this table of values, since data are all whole numbers, we rounded it up to the nearest millions thus, the formula used was **=ROUND(A3,-6)**

<p align="center">
  <img src="https://github.com/aprilrhose/Movie_MCU-Dataset_GROUP8/assets/143881769/4bcd7e49-2ca6-4e30-bdc0-e09b76220b8b">
</p>
<br>
<br>

**TRUNC Function**

>The **TRUNC function** is used to truncate a number to a specified number of decimal places. It essentially removes the decimal portion of a number, leaving only the integer part. The basic syntax for this function is **=TRUNC(number, [num_digits])**.

>The **number** represents the number you want to truncate while **[num digits]** is the number of decimal places you want to truncate the number. If omitted, it defaults to 0 which means the number is truncated to a whole number. 

>For this table of values, since data are all whole numbers, we truncated the numbers with -8, the formula used was **=TRUNC(A3,-8)** thus the values defaults to 0.

<p align="center">
  <img src="https://github.com/aprilrhose/Movie_MCU-Dataset_GROUP8/assets/143881769/f2f84976-7103-4bd7-9f4d-82cf420a59f5">
</p>
<br>
<br>

<div align="center">
  <strong>The importance of mathematical functions in Excel and similar tools cannot be overstated. These functions are used in various fields, including finance, engineering, science, statistics, and data analysis. They enable users to perform complex calculations, analyze data, and make informed decisions. Mathematical functions are critical for creating models, generating reports, and solving a wide range of problems in different industries and disciplines.</strong>
</div>
<br>

# LOOKUP Functions


**LOOKUP Function**

<p align="center">
  <img src="https://github.com/aprilrhose/Movie_MCU-Dataset_GROUP8/assets/143881769/5a2fc70f-da6f-4c2d-9540-2d08562591fa">
</p>


**VLOOKUP Function**
<p align="center">
  <img src="https://github.com/aprilrhose/Movie_MCU-Dataset_GROUP8/assets/143881769/a7719536-98a9-481e-a1a4-ac719ae8da17">
</p>

**MATCHUP Function**
<p align="center">
  <img src="https://github.com/aprilrhose/Movie_MCU-Dataset_GROUP8/assets/143881769/16337bcc-ac17-427c-8848-081eed6ad4c1">
</p>


**CHOOSE Function**

<p align="center">
  <img src="https://github.com/aprilrhose/Movie_MCU-Dataset_GROUP8/assets/143881769/3e9b48ba-8faa-460e-83a0-f266ebefadd0">
</p>

**AREAS Function**

<p align="center">
  <img src="https://github.com/aprilrhose/Movie_MCU-Dataset_GROUP8/assets/143881769/3e1c6129-97ce-4e17-a7d4-3576e2252474">
</p>

![red velvet chibi](https://github.com/aprilrhose/Movie_MCU-Dataset_GROUP8/assets/143881769/f7c3aa0b-26f8-4ab3-955e-29c6e91f25f5)










# **References**
<br>
- Ong, D. (2022, April, 22). Marvel Cinematic Universe Box Office Dataset. Kaggle . https://www.kaggle.com/datasets/davidgdong/marvel-cinematic-universe-box-office-dataset/data

- [Image of a Marvel Cinematic Universe Poster](https://images-wixmp-ed30a86b8c4ca887773594c2.wixmp.com/f/5298bac0-b8bf-4c80-af67-725c1272dbb0/defibp5-8019b091-dae8-426d-8276-7b6d15afcce8.jpg?token=eyJ0eXAiOiJKV1QiLCJhbGciOiJIUzI1NiJ9.eyJzdWIiOiJ1cm46YXBwOjdlMGQxODg5ODIyNjQzNzNhNWYwZDQxNWVhMGQyNmUwIiwiaXNzIjoidXJuOmFwcDo3ZTBkMTg8). (n.d.)
