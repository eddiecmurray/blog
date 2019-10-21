---
layout: post
title: "How to Keep the Leading Zeros in Spreadsheet"
tags: excel google google_sheets
eye_catch: /blog/assets/img/spreadsheet-2127832_960_720.png
---

In my school district our student ID numbers begin with zeros.  This is a problem in spreadsheet software like Google Sheets or Microsoft Excel because by default you can’t include the leading zeros in a cell.  There are a few ways to change the cell formatting to include leading zeros in the cell so that your student ID numbers or other data looks correct in your spreadsheet.

<!--more-->

## Add a Single Quote

In both Sheets and Excel you can simply add a single quote before you type the number.  This tells the spreadsheet that the cell contains plain text, not a number which will show the leading zeros.  For example:

`’0012345`

## Format the Cell as Plain Text

You can also change the formatting of the cell so that it is plain text.  This will tell the spreadsheet software that the cell contents should be viewed as text instead of a number.  

[Alan Murray](https://twitter.com/Computergaga1) at [How-To Geek](https://www.howtogeek.com/) explains how to do this in Excel:

>Select the range of cells you want to format as text. Next, click the “Home” tab, select the list arrow in the Number group, and choose “Text.”

In Google Sheets, select the range of cells then in the toolbar select Format > Number > Plain text.

## Use Custom Number Formatting

If you need to keep the cell in the number format so you can sort the data there is also an option to apply a custom number format to the cell.

Again, [Alan Murray](https://twitter.com/Computergaga1) at [How-To Geek](https://www.howtogeek.com/) explains how to do this in Excel:

>Select the range of cells you want to format. Right-click the selected range and click “Format Cells.”
>
>From the “Number” tab, select “Custom” in the Category list and enter 00000 [or whatever length you need for the number] into the Type field.

In Google Sheets, select the range of cells then in the toolbar go to Format > Number > More Formats > Custom number format.  Enter the length of your number in zeros and click ‘Apply’.

Microsoft Excel and Google Sheets include several ways to include leading zeros in cells.  These formatting options make it easier to view and sort the data you need in your spreadsheet.

**Source:** [How-To Geek](https://www.howtogeek.com/434261/how-to-enter-zero-before-a-number-in-excel/)

**Photo:** [denvit / Pixabay](https://pixabay.com/images/id-2127832/)
