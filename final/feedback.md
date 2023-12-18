# Feedback on your final

**Final Score: 42/60**

The grading rubric for the final can be found in GitHub: https://github.com/paulboal/hds5210-2023/blob/main/final/final-instructions.pdf

**Functional Requirements**
* 5 points - Uses data from at least two different sources: local file, internet, web service, relational database, AWS S3, etc; and formats: CSV, JSON, database, XML, Excel, etc
* 5 points - Data from multiple sources has to be joined together at least twice
* 5 points - Data is aggregated or pivoted at least twice during the program
* 5 points - Some kind of field-level transformation is performed at least 5 times
* 5 points - The program creates 3 or more data visualizations 
* 5 points - The program serves a theoretical purpose described in documentation, that could potentially do something in healthcare or another industry of interest

**Modularity / Style**
* 15 points - The code is broken up into various functions or classes to make testing and reuse easier

**Documentation and Professionalism**
* 15 points - All functions are documented and notebook cells include annotations and explanations.


**Thank you for laying out your plan for the project at the start. It's made it very easy to follow.**

**Note that creating functions for a single-line is not usually a very helpful thing to do.  For example, "findNullValues" just calls pd.isnull().any().**

**(-1) You merged on the state information from the BSA site, but didn't do anything special with that information.  In fact, that didn't really have anything useful to add to the analysis.  If you had needed it to translate from State Name to State Code, that would have been helpful.**

**(-1) Plotting histograms of all your data fields isn't necessarily helpful.  The distribution of values for Shape Length and Shape Area and FID, for example, mean nothing.**

**(-5) You laid out the steps ahead of time and then noted when you were doing each step, but none of your documentation describe why those were the appropriate steps for your analysis.  You needed to describe why this was a useful analysis.  Your datasets were very limited (obesity rates and total population).  There's very little you can actually do with that information.**

**(-4) You didn't do any grouping by or pivoting of data.  You computed one overall mean, but that isn't sufficient for full credit.**

**(-5) Your conclusion reads that this analysis "has shown several interesting trends and revelations", but i'm not clear on what those are.  We really only have one metric that we're reporting on.  The correlation between population and obesity rates doesn't show much of interest.  I think we would expect there to be no correlation and that's how it appears to me.**

**(-2) You didn't do as much field-level data transformation as required.  You simply didn't have enough data to work with for this project.**

**Overall, your code did a good job addressing the scope of the analysis you did on this report, but your scope was just too small.  You didn't have enough variety of data to give you the opportunity to do many interesting things.  Nice work on your coding, though.  It was good.**