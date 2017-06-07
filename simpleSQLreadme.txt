[some client information redacted. Active reference material:]

The syntax is broken down into sections: the first section formats the nested data so it’s easier to work with and assumes MySQL version > 5.5 and CREATE privileges. There’s a subsection dedicated to each of the events and signal trigger types. They’re treated independently throughout. 

The second section creates output tables (eventsOutput, signalsOutput) in the same format as the .xls file that was sent with the job. I assumed that percentage was relative to the whole dataset, and saved the “Percentage of Triggering” in separate tables in case that needs to be revisited (eventsOutputPercentage, signalsOutputPercentage). I’m happy to do revisit those tables if need be. 

Feel free to be in touch if you have any questions or concerns.

Caitlyn