# Project Overview: Overview
In this project, you will make use of Python to explore data related to bike share systems for three major cities in the United States—Chicago, New York City, and Washington. You will write code to import the data and answer interesting questions about it by computing descriptive statistics. You will also write a script that takes in raw input to create an interactive experience in the terminal to present these statistics.
Divvy is a bicycle sharing system in the City of Chicago and two adjacent suburbs (image: [Wikipedia](https://en.wikipedia.org/wiki/Divvy))

## Project Overview: What Software Do I Need?
To complete this project, the following software requirements apply:
* You should have Python 3, NumPy, and pandas installed using Anaconda
* A text editor, like [Sublime](https://www.sublimetext.com/) or [Atom](https://atom.io/).
* A terminal application (Terminal on Mac and Linux or Cygwin on Windows).

# Project Details: Bike Share Data
Over the past decade, bicycle-sharing systems have been growing in number and popularity in cities across the world. Bicycle-sharing systems allow users to rent bicycles on a very short-term basis for a price. This allows people to borrow a bike from point A and return it at point B, though they can also return it to the same location if they'd like to just go for a ride. Regardless, each bike can serve several users per day.
Thanks to the rise in information technologies, it is easy for a user of the system to access a dock within the system to unlock or return bicycles. These technologies also provide a wealth of data that can be used to explore how these bike-sharing systems are used.
In this project, you will use data provided by [Motivate](https://www.motivateco.com/), a bike share system provider for many major cities in the United States, to uncover bike share usage patterns. You will compare the system usage between three large cities: Chicago, New York City, and Washington, DC.

# Project Details: The Datasets
* Randomly selected data for the first six months of 2017 are provided for all three cities. All three of the data files contain the same core six (6) columns:
** Start Time (e.g., 2017-01-01 00:07:57)
** End Time (e.g., 2017-01-01 00:20:53)
** Trip Duration (in seconds - e.g., 776)
** Start Station (e.g., Broadway & Barry Ave)
** End Station (e.g., Sedgwick St & North Ave)
** User Type (Subscriber or Customer)
* The Chicago and New York City files also have the following two columns:
** Gender
** Birth Year
* The original files are much larger and messier, and you don't need to download them, but they can be accessed here if you'd like to see them ([Chicago](https://www.divvybikes.com/system-data), [New York City](https://www.citibikenyc.com/system-data), [Washington](https://www.capitalbikeshare.com/system-data)). These files had more columns and they differed in format in many cases. Some [data wrangling](https://en.wikipedia.org/wiki/Data_wrangling) has been performed to condense these files to the above core six columns to make your analysis and the evaluation of your Python skills more straightforward.

# Project Details: The Datasets
https://www.python-course.eu/python3_input.php
https://stackoverflow.com/questions/23294658/asking-the-user-for-input-until-they-give-a-valid-response
https://stackoverflow.com/questions/2847386/python-string-and-integer-concatenation
https://stackoverflow.com/questions/19377969/combine-two-columns-of-text-in-dataframe-in-pandas-python