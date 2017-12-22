# 6018_Term_Project
Programming Term Project
This program is designed to analyze and calculate some of the data I use for a Christmas Tree farm that I help run with my wife and her family.  Specifically it creates an Employee class to keep track of the employees (our kids and their friends) that we utilized during the season.  It then allows the user to enter in the employee's name, hours worked, and hourly rate to return how much that employee should be paid for the season.  Next, there is a function to help calculate the cost to add flocking to a tree, as both tree heights and cost for various flocking varies the function utilizes slider widgets to choose the appropriate height and flocking rate and then returns the total.  I then wanted to look at the sales data, because I had been noticing over the past several years since we have been in operation that our opening weekend sales seem to have a different theme/tone than sales do after opening weekend.  To look at this data, I uploaded some csv files that were created from our point of sale software.  I specifically wanted to compare category sales for the opening weekend compared to the whole season.  I wanted to visually display this data and thought that a pie chart would be the best visual representation.  The knowledge gained from comparing this data will help us in future years to know how best to stock the lot for opening weekend compared to the rest of the season.  

Before running this program the following packages must be installed or imported:
!conda install ipywidgets -y
import matplotlib.pyplot as plt
import pandas as pd
from ipywidgets import interact, interactive, fixed
from IPython.display import clear_output, display, HTML
