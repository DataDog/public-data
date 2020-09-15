# Public Data Release

The data here are website hits to Datadog's application for a contiguous 4-week
period sometime in the last two years.  It does not include any customer data,
only counts of web requests to our application.

Each row in the data is from a Datadog API query.  The first column is the
number of seconds since the beginning of the period, which is 12:00AM on a
Saturday.  Each row represents the sum queries over a ten second period starting
at that relative timestamp, relative to the raw median for the entire dataset.
So, a value of .9 will indicate that the webserver hit-count over that 10
seconds is 90% of the median for all 10-second periods over the 4 weeks.

The data is licensed under a Creative Commons CC BY-SA 4.0 license.
