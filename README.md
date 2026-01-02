# Part I: The Proposal

## Other Requirements:
1.	Turn in this Word DOC containing your proposal for the project.   Fill out this form and answer the questions fully. Also, turn in a copy of the data file.  The data file can be a .txt file or an Excel file.
2.	You need to make an appointment with me to discuss your proposal.  I can meet with you online or in person.  Please email me to make an appointment or contact me during class.  If your proposal is well thought–out and your sample code looks like it will work, the meeting will be very short.  I will work with you to make sure you will be able to read your data and that your proposed program outline is acceptable.

__This program is yours to design.  The general requirements are:__
__Locate data on the web, copy it.  If necessary, convert it into a compatible format for reading.  Write a program that reads the data into arrays, performs analysis on that data using the data in the arrays, and writes a report into a text file.__

In this first part of the assignment, you are to locate the website from which you will obtain your data.

There is a huge amount of data available to you.   Some examples of topics from the past are sports team statistics, astronomy data, earthquake data, water usage data, population data, economic data, educational data, crime data, Pokémon data, and other game or movie data.  Find something that interests you. 

Some of the “cleanest” data you will find are from the government.  Some sites will have a download button where you can specify the format of the data to be downloaded.  Other sites will have data in a table that you can copy and paste into Excel.  Some sites will charge you for their data (I would look elsewhere).

The data will need to be in a text-based file. This file will be in your C++ Visual Studio project.  It will **not** be a link. You **will not** do a lot of editing "by hand" of the data. The only editing allowed is for changing the format of cells that seem to be numerical but are strings, and to remove the thousands separator.  That skill is in SLO2.

Make sure your data is current and interesting.  Do not come up with a list of teen pregnancies in Nebraska in 1987, broken down by county and age of the parent.

You will need to answer the following questions concerning your website, data, and intentions for the program.  **Fill out this WORD doc**.  You may write your answers in this spec.  Add any supplemental information as appropriate, for instance, a copy of the code snippet you will use to read in the data.

**Turn in requirements:  1) this completed document, 2) a copy of the data file.**

## **Questions:**
1. **What is the website you used to obtain your data? List the agency/organization as well as the specific URL. Your instructor should be able to go and find your data from this information.**
   
For this project proposal, the following is the URL of the data file the user is going to use in this program. The data file is about the bitcoin sales in the $ from 2014 to 2021. It is in .csv.
[Click Here](https://finance.yahoo.com/quote/BTC-USD/history?period1=1410825600&period2=1637539200&interval=1d&filter=history&frequency=1d&includeAdjustedClose=true)

2. **Often, the data files contain more data than you’ll need for P8. What data from the file are you going to use/analyze in your P8?**

It is oftentimes the data files contain more than one datum. In my Bitcoin sells in USD file in CSV, there is a date, high, low, open, close, Adj close, and volume. However, for the P8 project, the user is going to manipulate the maximum gain (high), the maximum loss (low), and the maximum volume (close) with their specific date. The reason for this analysis is to know which date the maxGain, maxLoss, and maxVolume in the data occurred on.  The sales date ranges from 2014 to 2021. 

3. **You will need to perform analysis on the data and generate at least three data facts. Describe the analysis you plan to do and the data facts you will generate.  High value and low value are one data fact together.**
   
The project determines the number of rows and columns in our CSV file. The project also uses this information to dynamically allocate “maximum loss”, “maximum gain”, and “maximum volume” arrays, as well as a "values" array for each row. The analysis of “maxLoss”, “maxGain”, and “maxVolume” are three data facts that this project performs and analyzes. In this project, the date and the amount in $ determine the “maxLoss”, “maxGain”, and “MaxVolume” of the bitcoin sold, except for the maxVolume, which is in high and low numbers in this CSV. file. 

4. **What is your plan for reading in the data? <ins>Include code to show your plan!</ins>**

The program not only explores three data facts but also has three functions, i.e., Functions.h, Functions.cpp, and Driver.cpp. Here’s the code to show the face of my project plan. 

## **Functions.h**

<img width="640" height="186" alt="image" src="https://github.com/user-attachments/assets/897b1adf-5dfe-4708-92a7-f2329aeb84ab" />

The .h function displays how .cpp files would look like. Therefore, this one is a replicate of cpp functions for this entire project plan. 

**Thanks**


# Sources:
# Usage:
# Contributions:
