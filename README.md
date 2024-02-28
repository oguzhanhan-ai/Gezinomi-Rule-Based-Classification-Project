# Gezinomi-Rule-Based-Classification-Project

<img src = "images/gezinomi_rule_based_classification.png" style = "width:975px; height:400px"/> 

## Business Problem

Gezinomi wants to create new level-based sales definitions by using some features of the sales it makes, create segments according to these new sales definitions, and estimate how much new customers can bring to the company on average based on these segments.

For example: It is desired to determine how much a customer who wants to go to an All Inclusive hotel from Antalya during a busy period can earn on average.

## Dataset Story

**gezinomi_miuul.xlsx** data set contains the prices of sales made by Gezinomi company and information about these sales. The data set consists of records created in each sales transaction. This means the table is not deduplicated. In other words, the customer may have made more than one purchase.

## Features

**SaleId:** Sales ID

**SaleDate:** Date of Sales

**CheckInDate:** Customer's hotel check-in date

**Price:** Price paid for sale

**ConceptName:** Hotel concept information

**SaleCityName:** Information about the city where the hotel is located

**CInDay:** The day the customer checks in to the hotel

**SaleCheckInDayDiff:** Day difference between check-in and check-in date

**Seasons:** Season information on hotel check-in date
