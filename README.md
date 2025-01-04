# Travel Aggregator Documentation - Project #1

## History

In the earlier days, it was not easy to travel as booking journeys used to be a hassle, where people needed to contact travel agents, get prices and then do a lot of paperwork.<br>
But, with the advent of online apps, it has become easier to book tickets. <br> However, one challenge still persists; so many available apps offering bookings which requires rigorous comparisons (tedious and time-demanding) in order to find best prices/ offers.

## Travel Aggregator

Travelling has significantly changed thanks to technology.<br>
A new Indian start-up, **"MyNextBooking”** is an aggregator on top of the available top
platforms (Yatra, MMT, Goibibo). It helps users compare prices for their upcoming
journeys on its platform and the customer is redirected to the desired platform after
looking at the prices. <br>
However, they need to do a lot of analysis of the data which they have collected over time.

## What can you do with this App?

The Travel Aggregator has the following functionalities. It allows users to:

1. Find the number of distinct bookings, sessions, and searches from the given data
   sets.
2. Find the number of sessions that have more than one booking.
3. Determine which days of the week have the highest number of bookings; with a pie
   chart to show the distribution for all the days of the week.
4. Display for each of the service names, the total number of bookings and the total
   Gross Booking Value in INR.
5. Determine for customers who have more than 1 booking, which is the most booked route
   (from_city to to_city).
6. Find the top 3 departure cities from where customers book mostly in advance,
   provided that there have been at least 5 departures from that city.
7. Give a visual representation of the correlations among the numerical columns and report which pair of numerical columns in the bookings dataset, have the maximum correlation.
8. Determine for each service, which is the most used device type for making bookings on the platform.
9. Display the trends at a quarterly frequency for the number of bookings by each of the device types; i.e., dsiplay a time series for each year and quarter showing the number of bookings performed by each device type.
10. <br>   
    &emsp; a.  Determine  the average oBSR for each month of the year. <br> 
    &emsp; b.  Determine  the average oBSR for each day of the week. <br>
    &emsp; c.  Display a time series of oBSR on all the given dates.

# Getting Started

## Required Tasks

## Installing Dependencies

1.  **Python 3.13.1**

    Follow instructions to install the latest version of python for your platform in the [python docs](https://docs.python.org/3/using/unix.html#getting-and-installing-the-latest-version-of-python)

2.  **Virtual Enviornment**

    It is recommended to work within a virtual environment whenever using Python for projects. This keeps your dependencies for each project separate and organaized. Instructions for setting up a virtual environment for your platform can be found in the [python docs](https://packaging.python.org/guides/installing-using-pip-and-virtual-environments/)

3.  **PIP Dependencies**

    Once you have your virtual environment setup and running, install dependencies by navigating to the `/PROJECT_1` directory and running:

```bash
pip install -r requirements.txt
```

This will install all of the required packages necessary for the Travel Aggregator App.

##### Key Dependencies

- [Seaborn](https://seaborn.pydata.org/) is a Python data visualization library based on [matplotlib](https://matplotlib.org/). It provides a high-level interface for drawing attractive and informative statistical graphics.

- [Pandas](https://pandas.pydata.org/) is a fast, powerful, flexible and easy to use open source data analysis and manipulation tool, built on top of the Python programming language.

- [Numpy](https://numpy.org/) offers comprehensive mathematical functions, random number generators, linear algebra routines, Fourier transforms, and more.

- [Matplotlib](https://matplotlib.org/) is a comprehensive library for creating static, animated, and interactive visualizations in Python

## Running the program

##### Note

`This project was executed on a machine running` **Windows 10** . `Any OS will work fine just some minor changes. You can easily "google" your way out!` <br><br>
Ensure you are working in your virtual environment.<br>
Navigate to the `/PROJECT_1` directory and open [Visual Studio](https://visualstudio.microsoft.com/downloads/) from that directory. <br>
For this project, you can use any other preferred _Integrated Development Environment (IDE)_ or you can choose to run everything completely on [Google Colab](https://colab.google/) (Colab is a hosted Jupyter Notebook service that requires no setup to use and provides free of charge access to computing resources, including GPUs and TPUs. Colab is especially well suited to machine learning, data science, and education).

## Tasks

| No   | Completed | Task Description                                                                                                                                                                                                        |
| :--- | :-------: | :---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| 1.   |  **[x]**  | Find the number of distinct bookings, sessions, and searches from the data sets.                                                                                                                                        |
| 2.   |  **[x]**  | Find the number of sessions that have more than one booking..                                                                                                                                                           |
| 3.   |  **[x]**  | Determine which days of the week have the highest number of bookings; with a pie chart to show the distribution for all the days of the week.                                                                           |
| 4.   |  **[x]**  | Display for each of the service names, the total number of bookings and the total Gross Booking Value in INR.                                                                                                           |
| 5.   |  **[x]**  | Determine for customers who have more than 1 booking, which is the most booked route(from_city to to_city).                                                                                                             |
| 6.   |  **[x]**  | Find the top 3 departure cities from where customers book mostly in advance, provided that there have been at least 5 departures from that city.                                                                        |
| 7.   |  **[x]**  | Give a visual representation of the correlations among the numerical columns and report which pair of numerical columns in the bookings data set, have the maximum correlation.                                         |
| 8.   |  **[x]**  | Determine for each service, which is the most used device type for making bookings on the platform.                                                                                                                     |
| 9.   |  **[x]**  | Display the trends at a quarterly frequency for the number of bookings by each of the device types; i.e., dsiplay a time series for each year and quarter showing the number of bookings performed by each device type. |
| 10.a |  **[x]**  | Determine the average oBSR for each month of the year.                                                                                                                                                                  |
| 10.b |  **[x]**  | Determine the average oBSR for each day of the week.                                                                                                                                                                    |
| 10.c |  **[x]**  | Display a time series of oBSR on all the given dates.                                                                                                                                                                   |

## Datasets

The Datasets directory in this project consists of the following two files:

1. _Bookings.csv:_ This is a `comma-separated-values`file comprising of the following columns--

   ```
       • customer_id
       • booking_id
       • from_city
       • from_country
       • to_city
       • to_country
       • booking_time
       • device_type_used
       • INR_Amount
       • service_name
       • no_of_passengers
       • days_to_departure
       • distance_km
   ```

2. _Sessions.csv:_ This is a `comma-separated-values`file comprising of the following columns--

   ```
       • session_id
       • search_id
       • search_time
       • session_starting_time
   ```

## Author

- [Benedict Ayamga](https://github.com/ayamgabenedict)

## Submission & Acknowledgements

- [Edureka](https://www.edureka.co/) This project is submitted to Edureka as part of the requirements for `Data Science and Machine Learning Internship Program`.

## Screenshots

**The following are screenshoots of the outputs of required tasks in this project:**


![Q1 output](https://github.com/ayamgabenedict/Travel-Aggregator/blob/8ab220855027c1fc770701b3d62b8204f41b3794/imgs/Q1_output.png)

![Q2 output](https://github.com/ayamgabenedict/Travel-Aggregator/blob/8ab220855027c1fc770701b3d62b8204f41b3794/imgs/Q2_output.png)

![Q3 A output](https://github.com/ayamgabenedict/Travel-Aggregator/blob/3e309300bbd8eb9d77f1662ba38b5e8ba6b48d63/imgs/Q3_a_output.png)

![Q3 B output](https://github.com/ayamgabenedict/Travel-Aggregator/blob/8ab220855027c1fc770701b3d62b8204f41b3794/imgs/Q3_b_output.png)

![Q4 output](https://github.com/ayamgabenedict/Travel-Aggregator/blob/8ab220855027c1fc770701b3d62b8204f41b3794/imgs/Q4_output.png)

![Q5 output](https://github.com/ayamgabenedict/Travel-Aggregator/blob/8ab220855027c1fc770701b3d62b8204f41b3794/imgs/Q5_output.png)

![Q6 output](https://github.com/ayamgabenedict/Travel-Aggregator/blob/8ab220855027c1fc770701b3d62b8204f41b3794/imgs/Q6_output.png)

![Q7 A output](https://github.com/ayamgabenedict/Travel-Aggregator/blob/8ab220855027c1fc770701b3d62b8204f41b3794/imgs/Q7_a_output.png)

![Q7 B output](https://github.com/ayamgabenedict/Travel-Aggregator/blob/8ab220855027c1fc770701b3d62b8204f41b3794/imgs/Q7_b_output.png)

![Q8 output](https://github.com/ayamgabenedict/Travel-Aggregator/blob/8ab220855027c1fc770701b3d62b8204f41b3794/imgs/Q8_output.png)

![Q9 A output](https://github.com/ayamgabenedict/Travel-Aggregator/blob/8ab220855027c1fc770701b3d62b8204f41b3794/imgs/Q9_a_output.png)

![Q9 B output](https://github.com/ayamgabenedict/Travel-Aggregator/blob/8ab220855027c1fc770701b3d62b8204f41b3794/imgs/Q9_b_output.png)

![Q10 A output](https://github.com/ayamgabenedict/Travel-Aggregator/blob/8ab220855027c1fc770701b3d62b8204f41b3794/imgs/Q10_a_output.png)

![Q10 B output](https://github.com/ayamgabenedict/Travel-Aggregator/blob/8ab220855027c1fc770701b3d62b8204f41b3794/imgs/Q10_b_output.png)

![Q10 C output](https://github.com/ayamgabenedict/Travel-Aggregator/blob/8ab220855027c1fc770701b3d62b8204f41b3794/imgs/Q10_c_output.png)


![Q1 output](imgs/Q1_output.png)
