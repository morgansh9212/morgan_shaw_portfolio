<strong>| [Home Page](https://morgansh9212.github.io/morgan_shaw_portfolio/) | [#MakeoverMonday](https://morgansh9212.github.io/morgan_shaw_portfolio/MakeoverMonday_34.html) | [final project I](https://morgansh9212.github.io/morgan_shaw_portfolio/finalproject_part_i.html) | [final project III]() | </strong>


# Storyboarding
---
As I dug deeper into my representations of Eviction Rates, I soon realized it was going to be difficult to show the effect of Right to Counsel on a municipal level. The data I had showed *some* changes with Right to Counsel adoption, but the changes were too subtle to easily show with a visualization. 
As I tweaked with the visualizations, I uncovered a new narrative.
The [Eviction Lab](evictionlab.org) was collecting data long before the COVID-19 pandemic hit the US, but they quickly saw that this was going to lead to big changes in eviction rates across the country. As cities across the nation adopted eviction moratoriums and the CDC adopted one of their own, the Eviction Lab started to track Evictions as a percentage of the Pre-COVID-19 Average. This helped to show the massive decline created by the moratoriums and the pandemic. It also created a potential opportunity to advocate for _**keeping those rates low**_. 

### And so the new story that I felt compelled to tell was this one. 

In 2020, our country saw a historic drop in Eviction rates.
The moratorium kept rates low for nearly a year in many cities across the US. 
The benefits of not evicting people were maybe difficult to see during the pandemic, but the harms we know are caused by eviction likely decreased preciptiously as well. 
When the CDC eviction moratorium was ended by the courts, eviction rates again started to climb back to their pre-COVID levels. 

### *And so the question becomes, do we have to let them get back to COVID-19 levels?*

To tell this story I built two visualizations. 

First, I built a bar graph that showed how eviction rates changed in Kansas City over the 4 years following COVID-19. 
The Eviction Data is highly seasonal, so I compared each year within each month. 
----

<div class='tableauPlaceholder' id='viz1728019788624' style='position: relative'><noscript><a href='#'><img alt='Kansas City, Evictions Relative to Pre-COVID-19 Average ' src='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;KC&#47;KC_evictionrates_v1&#47;KansasCityEvictionsRelativetoPre-COVID-19Average&#47;1_rss.png' style='border: none' /></a></noscript><object class='tableauViz'  style='display:none;'><param name='host_url' value='https%3A%2F%2Fpublic.tableau.com%2F' /> <param name='embed_code_version' value='3' /> <param name='site_root' value='' /><param name='name' value='KC_evictionrates_v1&#47;KansasCityEvictionsRelativetoPre-COVID-19Average' /><param name='tabs' value='no' /><param name='toolbar' value='yes' /><param name='static_image' value='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;KC&#47;KC_evictionrates_v1&#47;KansasCityEvictionsRelativetoPre-COVID-19Average&#47;1.png' /> <param name='animate_transition' value='yes' /><param name='display_static_image' value='yes' /><param name='display_spinner' value='yes' /><param name='display_overlay' value='yes' /><param name='display_count' value='yes' /><param name='language' value='en-US' /><param name='filter' value='publish=yes' /></object></div> <script type='text/javascript'> var divElement = document.getElementById('viz1728019788624'); var vizElement = divElement.getElementsByTagName('object')[0]; vizElement.style.width='100%';vizElement.style.height=(divElement.offsetWidth*0.75)+'px'; var scriptElement = document.createElement('script'); scriptElement.src = 'https://public.tableau.com/javascripts/api/viz_v1.js'; vizElement.parentNode.insertBefore(scriptElement, vizElement);                
</script>

## Next, I used the pages function to build a time-series data source that showed how a 3 month moving average of Eviction Rates changed.  
----
<div class='tableauPlaceholder' id='viz1728020109675' style='position: relative'><noscript><a href='#'><img alt='Eviction Filings, 3 Month Moving Average: January 2020 ' src='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;TS&#47;TSWD_allcities_timeseries&#47;EvictionFilings3MonthMovingAverage&#47;1_rss.png' style='border: none' /></a></noscript><object class='tableauViz'  style='display:none;'><param name='host_url' value='https%3A%2F%2Fpublic.tableau.com%2F' /> <param name='embed_code_version' value='3' /> <param name='site_root' value='' /><param name='name' value='TSWD_allcities_timeseries&#47;EvictionFilings3MonthMovingAverage' /><param name='tabs' value='no' /><param name='toolbar' value='yes' /><param name='static_image' value='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;TS&#47;TSWD_allcities_timeseries&#47;EvictionFilings3MonthMovingAverage&#47;1.png' /> <param name='animate_transition' value='yes' /><param name='display_static_image' value='yes' /><param name='display_spinner' value='yes' /><param name='display_overlay' value='yes' /><param name='display_count' value='yes' /><param name='language' value='en-US' /><param name='filter' value='publish=yes' /></object></div> <script type='text/javascript'> var divElement = document.getElementById('viz1728020109675'); var vizElement = divElement.getElementsByTagName('object')[0]; vizElement.style.width='100%';vizElement.style.height=(divElement.offsetWidth*0.75)+'px'; var scriptElement = document.createElement('script'); scriptElement.src = 'https://public.tableau.com/javascripts/api/viz_v1.js'; vizElement.parentNode.insertBefore(scriptElement, vizElement); </script>

----
Data Source (for both visualizations): Peter Hepburn, Jacob Haas, Renee Louis, Adam Chapnik, Danny Grubbs-Donovan, Olivia Jin, Jasmine Rangel, and Matthew Desmond. Eviction Tracking System: Version 2.0. Princeton: Princeton University, 2020. (www.evictionlab.org)

This visualization was one I came up with later in the process but in trying to find a way to show the "pulsing" of eviction trends, this showed those changes very well.  
-----  

### Turning it into a story?

With these visualizations and some story ideas, I turned to user research to see how this might play out more specifically. 

# User research 

## Target audience
Initially my target audience were largely policy makers, but my shift to broader trends in Eviction and COVID-19 led me to expand my audience to include those interested in housing policy and housing rights in general. While I'd like to hope the general population could still use my graphs to understand eviction better, I figured my graphs would be best reviewed by people studying and implementing policy.

## Interview script

I mostly stuck with the 18F IDEO format to form my questions. I conducted my interviews fairly informally, with the aim of getting as natural of a reaction out of my audience as possible. My general thought was that if they came across these visualizations while doing research for a memo/brief or a desire to learn more about eviction and housing poicy, how they initially react would be indicative of their propensity to use my visualization or attempt to learn something using it. 


### Research Goals: 

My goal was to have data visualizations that told a clear story and simple enough to understand upon a quick review, but sophisticated enought that they triggered further investigation by my audience. 
I wanted to know if my viz made them ask questions they wanted answers to and made them reconsider their assumptions about evictions, especially if they weren't particularly familiar with its idiosyncrasies. 

Text here!

| Goal | Questions to Ask |
|------|------------------|
|Easy to understand/Read | What is your first impression of this visualization? |
| A clear narrative structure | Do my visualizations tell the story you expected to see?| 
| Generate more questions, not just answers | What parts of the viz and story do you want to know more about? |
| Useful and challenging for people in policy. |As a policy person, did this change any of your preconceived notions about eviction?|


## Interview findings
> Detail the findings from your interviews.  Do not include PII.  Capture specific insights where possible.

Text here!

| Questions               | Interview 1 | Interview 2 | Interview 3 |
|-------------------------|--------------------------------|-------------|-------------|
| *What is your first impression of this/these visualization(s)?* | The pulsing of the circles was clear and interesting  | The bar graphs are very interesting and the use of the band is clear.| The colors and pulsing shapes of the circles is very cool and tells a good story |
| *Do my visualizations tell the story you expected to see?* | It does a good job of showing the ratio, but the timeline effect of the bar graph is tough to parse. Maybe bigger grain of date? | I found it difficult to get the time factor out of the bar graph, there might be too many bars to get a good visualization | Can this be changed to a quarterly measure or similar? Also, make sure the colors don't get confused for numbers in the bar graph.|
| *What parts of the viz and story do you want to know more about?*| Why are some months so high? What patterns lead to this big seasonality? | Why do some cities have such high evictions comparatively? | What is causing evictions to climb back to normal levels? And when exactly was the moratorium? |
| *Did this change any of your preconceived notions about eviction?* | I really did not know about the effects of weather and holidays on Eviction. | I knew evictions dropped during COVID, but i never considered they would climb back up so quickly. | Eviction is far more widespread a problem than I initially thought|


# Identified changes for Part III

Overall, it was clear my bar graphs needed some work to help tell the time-story associated with my narrative. I did not want to give up the granularity of monthly data, because knowing those changes month-over-month I found to be too important for understanding the way eviction can shift dramatically. 


| Research synthesis                       | Anticipated changes for Part III                                                |
|------------------------------------------|---------------------------------------------------------------------------------|
|A clearer depiction of time to make comparing months YOY easier. | I will break my bar graph into the sections of the narrative I described above. One for each section of changing eviction rates. |
| Making sure color convention is clear between the two visualizations | Reducing colors in the bar graph so there is no confusion between the two. |
|Leaning into the pulsing of the circles may help | Increasing the size jumps for the circles to show the more subtle pulsing changes more clearly |
|Make the period of the moratorium clearer for the audience| Add an annotation or change in color scheme to show how the moratorium coincides with lower values in Kansas City.|

## Looking Ahead to Part III

I think what will benefit my visualizations most is tying them more closely to my narrative. I am a bit nervous about making these fit into my 1 minute time limit, but I think with good, clear annotation or use of symbology, I can show how eviction rates are climbing to unsustainable rates yet again. 

