| [home page](https://morgansh9212.github.io/morgan_shaw_portfolio/)



# Eviction and the Right To Counsel
-----------
## The Eviction Lab

While I was looking for a data viz to critique for my [previous assignment](MakeoverMonday_34.html), I saw that one of the vizualizations put forth by Matthew Desmond's [Eviction Lab](evictionlab.org) was put up for a redesign. 
While I ended up choosing a dataset focused on vacancy rates, I spent several minutes scouring the wealth of research on eviction they've produced and provided to the public for free. 
Matthew Desmond's *Evicted* (2016) tells the stories of landlords and tenants in Milwaukee, WI and how eviction harms the most vulnerable people in society. 
Whether it is older men on SSI and unable to work being forced onto the street or children struggling to succeed in school because of frequent moves, they are all hurt by eviction.

Their mapping of eviction shows how widespread this damaging practice is. 
<div data-pym-src="https://evictionlab.org/map/?m=raw&c=p&b=efr&s=all&r=states&y=2018&z=3.94&lat=38.14&lon=-97.54&lang=en&embed=true">Loading...</div><script type="text/javascript" src="https://pym.nprapps.org/pym-loader.v1.min.js"></script>

One of the reasons evictions are so high in some places is that tenants do not know how to or are unable to get representation to defend themselves when their eviction case comes before a judge. This year the state of Pennsylvania and Pittsburgh passed legislation to expand funding for a right to counsel for all tenants. Pittsburgh and Pennsylvania are certainly not the only places to start to institute this protection measure, so I was curious to see how I could use Eviction Lab's data to tell the story of Right To Counsel. If it's true that this kind of program might keep more tenants from being subjected to spurious eviction and its damaging consequences, policymakers and the public should know. If the program is not producing obvious results, maybe we should look at what might be keeping tenants from utilizing this protection. The program may me need more lawyers or more funding to produce real results. 

And so I downloaded the data available on the Eviction Lab and began to look through it.

## Initial sketches
Before I did much data cleaning, I drew up a sketch of a line graph showing a potential city that adopted a Right To Counsel law at some point close to the middle of the range of the data the Eviction Lab provided (somewhere between 2020 and 2024). I aimed to show how evictions might reduce over time with this rules' adoption and naturally considered a line graph with a clear marker for the date eviction was adopted.  

<img src="/fp_pi_sketch1.png"
  width="600"/>

After I did some cleaning and playing around with the data and made some initial visualizations, it was clear the data was going to be very noisy. Evictions are highly seasonal and change from month to month for a number of reasons. 
**For example, the average filings by month in Kansas City show lots of movement up and down throughout the year, making it difficult to visualize any trends in the data.**  

![Line graph of average filings in KC showing lots of movement up and down](/kc_avgevictionfilingsbymonth.png)

To show how these rates might be changing over time, I considered how I might group this data by month rather than by just one straight time line. 
*Perhaps I could show the 3 or 4 years of change in the span of 12 months?*  


<img src="/fp_pi_sketch2bar.png"
    width="600"/>

------------------------------------  
# The Eviction Lab's Data

The Eviction Lab has a rich database of evictions filings across many cities in the US. If I were to try and plot eviction rates across all of these different cities, it would be difficult to parse to say the least. 
I will be using the large dataset of monthly eviction data for all cities and then breaking it down into the various cities I plan to analyze, specifically Pittsburgh and Kansas City. Kansas City passed a [Right to Counsel law in 2022](https://www.kansascity.com/news/politics-government/article256472976.html), putting them right in the middle of the range of my data. Pittsburgh has only recently [expanded funding](https://www.post-gazette.com/news/politics-local/2024/09/04/pittsburgh-city-council-funding-eviction-prevention-programs/stories/202409040078#:~:text=City%20Council%20approves%20additional%20funding%20for%20eviction%20prevention%20programs,-Hallie%20Lauer&text=Nearly%20a%20quarter%20of%20Pittsburgh's,by%20City%20Council%20on%20Wednesday.) for this provision, so it can provide a good comparison.  


| Name | URL | Description |
|------|-----|-------------|
|Nationwide Monthly Eviction Counts, Eviction Lab|[**LINK**](https://evictionlab.org/eviction-tracking/get-the-data/#:~:text=Monthly%20Data-,All%20Cities,-%2D)| Counts of Evictions in all cities being tracked by Month.|
|Pittsburgh Monthly Eviction Counts|[**LINK**](/pgh_eviction_data.csv)|Monthly counts of Evictions in Pittsburgh, PA, cleaned from Eviction Lab Data|
|Kansas City Monthly Eviction Counts|[**LINK**](/kc_evictions_sepdate.csv)|Monthly counts of Evictions in Kansas City, MO, cleaned from Eviction lab Data|
--------
# Method and medium
I intend to use Tableau to create my data visualizations and potentially use Shorthand to build an effective storytelling page. 
To make sure my data is ready for tableau, I plan to use R to clean and wrangle the data to make sure the numbers I am showing are both useful and accurate. 
I will likely try to show some spatial relationships of eviction in my chosen cities so I may use some of my experience in ArcGIS to build a map on the zip code/census tract level. 
