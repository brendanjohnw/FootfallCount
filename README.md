# OpenCV People Tracker and Counter 
## A Customer Footfall Count Project. (Brendan Lee and Seak Jian De)
The following project is a computer vision customer footfall counter that utilizes OpenCV for object tracking and detection. 
The detectiion mechanism was supplemented by pre-trained YoloV4 datasets, which were adapted from Common Objects in Common (COCO).

The main application of the project was to count the in-rate and out-rate of people enterring a particular premise such as a train station
shopping mall or retail store.


## Data Visualization using Tableau (Kong Yuki)
**Initial plan:** Use Tableau to visualize data set generated from OpenCV in a dashboard

Problem encountered: Video is too short, little can be predicted based on raw coordinates of all people per frame.

Alternative: Use Toronto Station Bikeshare Data (sample data) as an example on how to visualize footfall count data

Dashboard for mock data set (OpenCV):
https://public.tableau.com/views/E1_16387797643930/CoordinatesbyFrame?:language=en-US&publish=yes&:display_count=n&:origin=viz_share_link

Dashboard for Toronto Station Bikeshare Data (sample data):
https://public.tableau.com/views/E2_16388590856170/FootfallCountoverStartTimeByWeekday?:language=en-US&publish=yes&:display_count=n&:origin=viz_share_link

## Limitations

## Future Directions

## Dependencies

OpenCV:https://docs.opencv.org/4.x/d4/db1/tutorial_documentation.html

Numpy: https://numpy.org/doc/stable/

Matplotlib: https://matplotlib.org/stable/api/index

YoloV4: https://github.com/pjreddie/darknet

# References

Toronto Station Bikeshare Data (sample data): https://www.kaggle.com/apexinsideapex/station-footfall-analysis/data
