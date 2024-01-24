# 2024-01-17-tidycensus
Materials for EcoDataScience workshop on `tidycensus` package.

## Workshop Details

- **When:** Wednesday January 17, 11:30-1PM
- **Where:** In-person \@UCSB Library DREAM Lab (RM 2322, Mountain side of the building on the second floor)
- **What:** Intro to the `tidycensus` package.


## Pre-Workshop prep

### 1. Install and load `tidycensus` package

```
install.packages(tidycensus)
library(tidycensus)

```

### 2. Get U.S Census API

- Go to <https://api.census.gov/data/key_signup.html>
- Fill out the form
- Check your email for your key.


### 3. Set the Census API key in your local working environment

```
census_api_key("YOUR KEY GOES HERE", install = TRUE)
```

**Note:** install = TRUE forces R to write this key to a file in our R environment that will be read every time you use R. This means, by setting this argument to TRUE, you only have to do it once in any computer you are working. If you see this argument as FALSE, R will not remember this key next time you come back.


### 4. Restart R

### 5. Make sure you have the following packages installed
- `tidycensus`
- `dplyr`
- `tidyr`
- `ggplot2`
- `mapview`
- `sf`


## Workshop Material
- [Slides](https://docs.google.com/presentation/d/1uO1_g80zrt9D1JuaNdHHiOEj29kMIRcUvFxRpk4wefg/edit?usp=sharing)
- [Code](https://ecodatascience.github.io/2024-01-17-tidycensus/)
