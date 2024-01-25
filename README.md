# Fly Safely to Your Destination Vacation: Ranking private airplanes based on safety and risk
### Lotus Baumgarner, Norman Jen, and Bekah McLaughlin

<p align="center">
  <img src = "https://github.com/Bekahlmc/Ranking-Safest-Private-Planes/blob/Bekah/Images/private_jet.jpeg">
</p> 

## The Business Need

The luxury travel resort, White Lotus, is opening a new location in Martha's Vineyard and intends to purchase private planes for guest transportation from mainland locations to the island resort property. White Lotus takes great pride in its renowned commitment to delivering a luxurious and exclusive experience, with private air travel being an integral component at this location. The primary goal is to prioritize the safety of guests and mitigate risks during transportation. Furthermore, among the safest options, White Lotus aims to pinpoint the most cost-effective, high-end, and highest passenger capacity choice.

### Safety First:
Data analysis will focus on evaluating a database of historical incident and accident rates of different aircrafts. From these records we will extract a list the safest potential private jet options.
  - *How do we measure safety when looking at historical records of aircraft accidents and incidents?*
  - *Based on statistical analysis and chosen safety measuring method, what can we determine are the safest private jets to recommend to White Lotus?*

### Other Incidental Considerations:
After compiling a list of the safest private jets, we'll also compare cost and passenger capacity.
  - *Which option is the most cost effective?*
  - *Which option can transport the largest group of guests?*
  - *Which option could White Lotus splurge on for the guest experience?*

**Stakeholders: White Lotus Resorts owners and investors, guests, and White Lotus employees**

## The Dataset

This project uses the dataset Aviation Accident Database & Synopses, up to 2023, which can be found in the `Data` folder in this repository. This dataset was provided by National Transportation Safety Board, and each entry in this dataset represents either an incident or an accident of an aircraft. The columns of the data are explained in the columns_information.md file also found in the `Data` folder.

After thorough data cleaning and analysis that will be explained step by step below, we narrowed down our options to three different planes. Of these planes, we researched and compiled a small dataset to compare cost, range, and capacity of the planes. This dataset can additionally be found in the `Data` folder. 

## Data Analysis and Visualization 
