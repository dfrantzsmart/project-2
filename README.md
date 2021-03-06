# Project 1: <span style='color:blue'> Exploratory Data Analysis</span> 

***We are excited to use our growing Data Science knowledge to help WomenTechWomenYes (WTWY) engage  with individuals passionate about women in technology and to fundraise for its annual gala.***

### *<span style='color:green'>**Assumptions**:</span>*

>  * `Adequate budget and availability of canvassers`
>  * `Canvassing efforts will be no less than a week`
>  * `MTA day-to-day ridership not affected by COVID`
>  * `Canvassing will be in July and August`

### *<span style='color:green'>**Our Ideal Gala Attendee:**</span>*

> * `Local (Tristate Area) resident`
> * `High Annual Income ($100,000 +)`
> * `Female (but we hope to engage all genders!)`
> * `College-educated`
> * `Interested in Tech`

### <span style='color:green'>***Our Ideal Gala Attendee:*** </span>

> * `High density of women working or living`
> * `High income population`
> * `Near tech hubs`
> * `Near universities with STEM programs`



## <span style='color:blue'>Data Methodology: </span>

### *<span style='color:green'>**Data Collection:**</span>*

#### MTA turnstile data:

> * Two months before the event
> * 2019 data for better representation of NYC volume

#### NYU Furman Center - American Community Survey:

* > State of NYC’s Housing & Neighborhoods for 2006, 2010 and 2018

### *<span style='color:green'>**MTA Analysis:**</span>*

1. **Filtered turnstiles for errors**

   > a. Counts > 1 Million between days
   >
   > b. Summed entries and exit counts

2. **Grouped and Summed turnstiles in each station**

   > a. Avoiding duplicate station naming by grouping each station with its subway line.

   

### *<span style='color:green'>**MTA Results:**</span>*

> 1. Daily station average across 2 month period.
> 2. Daily station average by day of the week.

<img src="https://raw.githubusercontent.com/meehirpathare/project-1/master/image%20files/Top%2020%20Stations-%20pretty.png">

​															`	Top stations by turnstile traffic`

<img src="https://raw.githubusercontent.com/meehirpathare/project-1/master/image%20files/Top%2010%20out%20of%2020%20Stations-%20highres.png">

​				`Top 10 Stations that meet 'Idea Candidate' criteria marked in red `


<img src="https://raw.githubusercontent.com/meehirpathare/project-1/master/image%20files/heat%20map%20day%20of%20week.png">

​					`Recommended stations boxed in red. Day of the week recommendations starred `

### *<span style='color:green'>**Visualizing Demographics:**</span>*

<img src="https://github.com/meehirpathare/project-1/blob/master/image%20files/subway%20stations%20and%20zip%20geopandas.png">

​		`PYTHON: Subway station locations using Geopandas Package  ` 

<img src="https://github.com/meehirpathare/project-1/blob/master/image%20files/recommended%20stations%20tableau%20pic.png">

​		`TABLEAU: Median Household Income shaded in green and our station recommendations starred in red  ` 



## <span style='color:blue'>Our Recommendations: </span>
<img src="https://raw.githubusercontent.com/meehirpathare/project-1/master/image%20files/end%20recommendations.png">

- [x] <span style='color:green'>***Balance between MTA and contextual demographic data***</span>
- [x] <span style='color:green'>***Gala target attendees are more likely live and work in certain neighborhoods***</span>
- [x] <span style='color:green'>***Recommended stations fall within the relevant neighborhoods***</span>
- [x] <span style='color:green'>***Canvassers can target stations based on busiest days of the week***</span>



## <span style='color:blue'>Further Considerations: </span>

> ***<span style='color:green'>When should canvassing be done? </span>***
>
> ***<span style='color:green'>And at what time? </span>***
>
> ***<span style='color:green'>And with how many people? </span>***


## <span style='color:blue'>Packages and Programs Used: </span>  
> * Pandas
> * Numpy
> * Seaborn
> * Matplotlib
> * Geopandas
> * Tableau
