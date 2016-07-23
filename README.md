# Reproducible_Research_Project1_Activity

## INTRODUCTION
It is now possible to collect a large amount of data about personal movement using activity monitoring devices such as a Fitbit, Nike Fuelband, or Jawbone Up. These type of devices are part of the "quantified self" movement -- a group of enthusiasts who take measurements about themselves regularly to improve their health, to find patterns in their behavior, or because they are tech geeks. But these data remain under-utilized both because the raw data are hard to obtain and there is a lack of statistical methods and software for processing and interpreting the data.

This assignment makes use of data from a personal activity monitoring device. This device collects data at 5 minute intervals through out the day. The data consists of two months of data from an anonymous individual collected during the months of October and November, 2012 and include the number of steps taken in 5 minute intervals each day.

## DATA
The data for this assignment can be downloaded from the course web site:
•Dataset: Activity monitoring data [52K]

The variables included in this dataset are:

•steps: Number of steps taking in a 5-minute interval (missing values are coded as  NA )


•date: The date on which the measurement was taken in YYYY-MM-DD format


•interval: Identifier for the 5-minute interval in which measurement was taken

The dataset is stored in a comma-separated-value (CSV) file and there are a total of 17,568 observations in this dataset.

## ASSIGNMENT
The objective is to write a report that answers the questions detailed below. Ultimately, the entire assignment should be completed in a single R markdown document that can be processed by knitr and be transformed into an HTML file.

### 1. What is mean total number of steps taken per day?
For this part of the assignment, the missing values in the dataset are ignored.

### 2. What is the average daily activity pattern?
2.1. Make a time series plot (i.e. type = "l") of the 5-minute interval (x-axis) and the average number of steps taken, averaged across all days (y-axis)

2.2. Which 5-minute interval, on average across all the days in the dataset, contains the maximum number of steps?

### 3. Imputing missing values
3.1. Calculate and report the total number of missing values in the dataset (i.e. the total number of rows with NAs);

3.2. Devise a strategy for filling in all of the missing values in the dataset. The strategy does not need to be sophisticated. For example, you could use the mean/median for that day, or the mean for that 5-minute interval, etc.;

3.3. Create a new dataset that is equal to the original dataset but with the missing data filled in;

3.4. Make a histogram of the total number of steps taken each day and Calculate and report the mean and median total number of steps taken per day. Do these values differ from the estimates from the first part of the assignment? What is the impact of imputing missing data on the estimates of the total daily number of steps?

### 4. Are there differences in activity patterns between weekdays and weekends?
4.1. Create a new factor variable in the dataset with two levels – “weekday” and “weekend” indicating whether a given date is a weekday or weekend day;

4.2. Make a panel plot containing a time series plot (i.e. type = "l") of the 5-minute interval (x-axis) and the average number of steps taken, averaged across all weekday days or weekend days (y-axis). See the README file in the GitHub repository to see an example of what this plot should look like using simulated data;


