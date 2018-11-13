# Electoral margin vs. tax inflow/outflow

## Objective
This project endeavors to analyze patterns underlying the relationship between federal spending and electoral margins of congressional districts. Prior to delving into the data, I believe that three possible scenarios may exist:
<ul><li>Wider electoral margins may provide more strength to politicians, enabling them to secure more resources for their constituents.</li>
<li>Narrower margins may help politicians persuade the congressional peers of the importance to support the district in order to avoid having the seat fall into possession of the opposition party.</li>
<li>No discernible relationship may be clear.</li></ul>

## Prior Work
Some writers have already compiled data comparing net federal funds flow for states (e.g. <a href="https://wallethub.com/edu/states-most-least-dependent-on-the-federal-government/2700/">WalletHub.com</a>). To my knowledge, such analyses have sought to question the fairness of lopsided flows. I have not yet been able to locate research examining reasons for the existence of such disparities.

## Novelty
The novelty of my approach is examining electoral margins at a congressional district level. It was somewhat surprising to me how difficult it was to obtain detailed vote counts. In what I considered to be the most basic public information, I was only able to locate compilations that had been prepared by the U.S. House of Representatives (i.e. <a href="https://history.house.gov/Institution/Election-Statistics/Election-Statistics/">House.gov</a>). Further, this appears to be available only in PDF format, which requires a substantial amount of manual effort for the Extract, Transform, Load (<a href="https://en.wikipedia.org/wiki/Extract,_transform,_load">ETL</a>) process.

## Relevance
If a relationship is determined, this would provide light on such scenarios. By making such relationships public knowledge and clearly showing their existence, it could help shape public perception. It could help political entities understand where limited resources could be allocated to shape future elections.

## Presentation
I intend to compile charts showing whether a relationship in positive, negative, or non-existent. To the extent that time (and my abilities) permit, I would like to use geographical visuals rather than merely graphs. Slides will also be used to summarize conclusions, further areas to consider, etc.

## Sources
I have obtained PDFs for congressional election results with detail counts for each district. I have already cleaned this data for the 2016. If time permits, I would like to include data from other elections as well. Unfortunately, this is an extremely manual process. (The 2016 election tabulation that I compiled manually consisted of 2,000 rows of data.)
For spending, I have downloaded a 43 Gb zip file that I should be able to decompress into PostgreSQL (<a href="https://files.usaspending.gov/database_download/">USAspending.gov</a>). I have not yet converted this zip file into usable format.

## Concerns & mitigations
My main concern is the detail that is available in the data. In order to mitigate this, I have already looked in detail at the 2016 election results. I still have more data to review to ensure its usability for my project.

## Next steps
My next steps are to continue the ETL process for the data that I have obtained. After that, I need to lay out the statistical model for my analysis, and build a minimum viable product for the results in 2016. To the extent possible, I would like to provide a better temporal understanding of any such relationships across a variety of electoral cycles.

For reference, the initial proposal is available <a href="Project3a.md">here</a>.
