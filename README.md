Geographic Visualization with Python and R's ggmap()
----

Expected Outcomes
----

By the end of this presentation, I hope you be able to:     

1. Correctly import the related packages to your environment.
2. Make a deal with __Google Cloud__.
3. Write reasonable Python codes to manipulate the data.   
4. Rock with simple `ggmap()` in Jupyter Notebook.   
5. Visualize great geographic figures for your data set.

----

### 1. Import the Packages

After surviving the catastrophe on `rpy2`, I believe you have already got the environment and dependencies correct.

Then the prework is quite easy. Follow the guide and everything's gonna be fine.

Open the __R console__ on your laptop. Then run these commands.

>```
install.packages(c("ggplot2", "devtools", "dplyr", "stringr"))
install.packages(c("maps", "mapdata"))
devtools::install_github("dkahle/ggmap")```

Remember to check the libraries in Jupyter Notebook. 

>```
%%R
library(ggplot2)
library(ggmap)
library(maps)
library(mapdata)```

If this is your first time installing and importing these packages, some alerts will pop up. 

Don't panic. It's just Google shouting for your money. Go to the next step and grab some free trial.

----

### 2. Register for Google Cloud

