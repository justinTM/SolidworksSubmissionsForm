# ENGR248 Solidworks Submission Form
A Windows Form Application to help/automate the grading process for Solidworks parts, submitted by Oregon State University student in ENGR 248. This project uses Windows Form Applications with the Solidworks API - both in C#.

This Form shows student folders, their parts, and each part's sketch as nodes within a TreeView. This GREATLY speeds up workflow when grading, as it removes the need to navigate the filesystem. To begin, select a root directory containing student submission folders (eg. downloaded from Canvas and unzipped).

Future goals for this Form include:
 - Opening sketches in Normal-To view, from the TreeView
 - Scraping data from features (timestamps, owner, # of undefined sketches, etc.)
 - Saving/exporting scraped data for upload into spreadsheet
 - Dimension-checking (ie. user can specify correct dimensions, then select contours within Solidworks to verify proper dimensions)
 - Determining "true" undefined sketches (vs. sketches with an undefined but unused point/line)