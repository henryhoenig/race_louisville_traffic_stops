## Race in Louisville traffic stops (2015-2018)


![Alt Text](capstone_images/stopped.jpg)



### Introduction: 

* A dataset from the Stanford Open Policing Project contains details on several years' of police traffic stops in Louisville, Kentucky. I examined the data with the goal of determining whether race played a role in the outcomes of traffic stops in Louisville--and if so, what racial dynamics were at play. As it did across the U.S., the issue of race and policing dominated headlines last year in Louisville, where the police shooting of Breonna Taylor in March was a factor in sparking nationwide protests. 


### The data: 

https://openpolicing.stanford.edu/data/

The dataset contained details on more than 100,000 traffic stops over three years. Features included:

* Age, race and gender of people stopped 
* Age, race and gender of police officers who stopped them
* Location (latitude and longitude) of the stop
* Police division where the stop occurred
* The stated reason for the stop
* Whether the citizen was searched, frisked, given a citation



### Among the questions asked and answered:

* Do Black citizens face a higher probability of being searched than white citizens? 
    -- Yes. 

* Are white officers or Black officers more likely to search a Black citizen?
    -- White officers.
    
* Are Black officers more likely to search a Black citizen or a white one?
    -- A Black one. 

* Are Latino officers more likely to search someone than a white officer?
    -- Yes. 


&nbsp;
&nbsp;
&nbsp;
### The findings
&nbsp;
&nbsp;
#### An overview of stops, searches and citations by race of citizens
&nbsp;
&nbsp;
* Blacks are overrepresented as a percentage of the population in stops, searches and citations.

* Whites, Latinos and Asians are underrepresented
&nbsp;

![Alt Text](capstone_images/pop_all_stops.png)

&nbsp;
&nbsp;

* The percentage of Black motorists who were searched was nearly double that of whites. 

* But white citizens were given citations at a higher rate.
&nbsp;

![Alt Text](capstone_images/stops_pct_searched_race.png)
&nbsp;
&nbsp;
&nbsp;
&nbsp;
#### The probability of Black and white citizens being searched
&nbsp;
* In 10,000 simulations, the probability that Blacks face a higher probability of being searched than whites: 1.0
&nbsp;
* Plotting the beta distributions of searches of Blacks and whites:  worlds apart
&nbsp;
&nbsp;
![Alt Text](capstone_images/black_white_all_officers.png)
&nbsp;
&nbsp;
&nbsp;
&nbsp;
#### What role might the officer's race play? 
&nbsp;
&nbsp;
* Blacks were searched the highest percentage of the time by white, Black and Asian officers
&nbsp;
&nbsp;
* Latino officers searched whites the most often, followed by Latinos
&nbsp;
&nbsp;
![Alt Text](capstone_images/stopped_pct_searched_race_off.png)










































