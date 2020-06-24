# Analyzing Ford's GoBike Data 2019
## by Dishant Tanwar


## Dataset

> The dataset is provided by Ford's GoBike themselves. You can get the dataset from <a href='https://www.lyft.com/bikes/bay-wheels/system-data'>here</a>.

The dataset contains the below mentioned variables.  
- Trip Duration (seconds)
- Start Time and Date
- End Time and Date
- Start Station ID
- Start Station Name
- Start Station Latitude
- Start Station Longitude
- End Station ID
- End Station Name
- End Station Latitude
- End Station Longitude
- Bike ID
- User Type (Subscriber or Customer – “Subscriber” = Member or “Customer” = Casual)

## Summary of Findings  
  
> These are the key findings
- We've Subscribers and Customers as user types. Where the number of subcribers is about four times the number of customers. Subscribers are the membership holders whereas Customers are Casal Users.
- Most of the trips have a duration of 7-14 minutes.
- Less trips during Winter.
- Weekends means riding break too.
- Morning 8am and Evening 5pm are peak hours for bike usage.

## Tech Stack   
  
These are the following packages I used throughout this project.

```
import matplotlib.pyplot as plt

from zipfile import ZipFile
from io import BytesIO

import numpy as np
import pandas as pd
import seaborn as sns

import requests
import time
import os
```