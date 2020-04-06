# PySchools-Pandas

## Challenge Objectives
1. Filter DataFrames using logical operators.
2. Replace the incorrect values with NaN.
3. Explain how your PyCitySchools analysis changes after you handle the incorrect data.

### Challenge Summary:

-----The challenge objective was to filter all data regarding ninth-graders who attended Thomas High School, replace their reading and math scores with NaN values, and note any changes. Filtering for Thomas High School ninth grade data was achieved using the loc method and np.nan. The NaN alteration affected 461 unique student entries, leaving 38,709 total entries unaltered. The district summary's average math score, % passing math, % passing reading, and % overall passing were minimally affected by the score change. The average math score dropped by one-tenth, and % passing math, % passing reading, and % overall passing fell by one percent. The per school summary remained largely unaffected; the only change was in Thomas High School's metrics for average math score, average reading score, % passing math, % passing reading, and overall % passing. In the top schools rating, Thomas High School dropped from second to third place; the change was the same in the bottom schools ratings. The only change in reading and math scores after the alteration was the ninth grade scores were changed to NaN. The average reading score, the percent passing in reading and math, and the percentage of overall passing students changed for the spending range of $633 to $644 per student. The size summary did not change. In the type summary, the percent passing math and reading, as well as percent overall passing dropped for charter schools after the change by a few percentage points.

-----My understanding from the documentation is NaN values are largely ignored or treated as zero in Pandas. If treated as a zero, any of the calculated ratios would be reduced due to a smaller numerator. The effects seen in the percentage of scores and percent of overall passing are small because only 461 entries from Thomas High School were affected, i.e., about 1.18% of the entire data. 
