# InsightCodeChallengeREADME.md
by Zheng Kuang, April 5, 2017

# Envrionment
Python 3.5

# Dependencies
numpy, 
re, 
pandas.Series, 
pandas.DataFrame, 
codecs, 
datetime


# Additional features
1. The file hours_no_overlap reports the most busy hours that are not overlaping with each other. To expediate the procession, those time windows for this feature is define at an interval of one minute. Server managers could use this information to better allocate their server resources.

2. The file resources_no401 filters out requests of resources that did not succeed so that the bandwith has not been actually occupied, which might be more informative than the summed sizes of resources of each request.

# Special notes

For some reason I have no time to get to since it turned up really late, the "run_test.sh" bash has being reading in a test file that contains double quotes that do not seem to be standard UTF-8 coded, therefore could not be picked up by my code. However, I have tested my code with the downloaded full dataset and it seems to be working fine. In order to get the code to run, it may be necessary to resave the resource data as a standard UTF-8 text file :/
