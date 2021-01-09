<img src='images/covid19.jpg'/>

### Title: Exploring COVID-19 Data in Mecklenburg County 
---

<br>
<br>

### Date Created: 
January 8, 2021
<br>
<br>

### Description
In this repo, I focused on exploring 2020 data related to COVID-19 Deaths and new cases in Mecklenburg County, North Carolina. 
<br>
#### Content:<br>
0. Reading Data
1. Death Percentage by Age Bracket
   - 1.1 Monthly Death Percentage By Age Bracket Chart
2. Death Count - All Ages 
   - 2.1 Monthly Deaths - All Ages
3. Death Percentage - All Ages
4. New Cases
5. Deaths vs. New Cases
6. Deaths by Age Bracket
    - 6.1 Total Deaths by Age Bracket
    - 6.2 Deaths by Age Bracket Throughout 2020
    - 6.3 Monthly Deaths by Age Bracket
7. Other Underlying Illness Conditions
    - 7.1 Monthly Deaths With Underlying Illness Conditions vs Deaths Without
    - 7.2 Total Death Percentage and Count With and Without Other Underlying Conditions

<br>
<br>

### Libraries used

* os <br>
* shutil <br>
* datetime <br>
* dateutil<br>
* pandas<br>
* pathlib<br>
* numpy<br>
* matplotlib<br>
<br>
<br>

### Data Used

To perform exploration of COVID-19 data in Mecklenburg county, I created my own dataset, "weekly_covid19_report_mecknc.csv"
The Data in this dataset was based on the Mecknc.gov COVID-19 reports from [Mecklenburg County COVID-19 Data Releases](https://www.mecknc.gov/news/Pages/COVID-19-Data-Dashboard.aspx)<br>
The reports in this site are in PDF format, so I had to pull the data manually. <br> 
This dataset does not update automatically.<br> Dataset was last updated on 2020-12-27. 
<br>
<br>
