## Loading and Preprocessing Data
1. Load the data 
if(!file.exists('activity.csv')){
    unzip('activity.zip')
}
activityData <- read.csv('activity.csv')

