# UFOs

## Overview of the Analysis
This html file shows UFO findings using Javascript, html, CSS, and Bootstrap. Users will have the ability to enter search specific criterias and see all reported sightings for query.

## Results
The html includes a brief summary on the purpose and a data table. The table includes date, city, state, country, shape, duration and comments provided by the witnesses. To perform a search, users can type a search criteria using the prepopulated text as an example, then press the enter key. The prepopulated example text will not have an effect on the query. In the below search, I have entered "1/1/2010" as my search criteria which has returned over 20 results. 

![image](https://user-images.githubusercontent.com/114771735/210470761-1c96b91c-f705-44bc-b7e6-a58493085769.png)

I can see the results and narrow down my search by adding a second field. I will enter "el cajon" as the city. The below shows all reported sightings on 1/1/2010 in El Cajon, CA. All sightings had "3 redt lights (or objects)" reported! 

![image](https://user-images.githubusercontent.com/114771735/210470984-178373f3-7538-4b02-a365-ce553d33ddfa.png)

## Summary
A drawback to this design is that users must type an exact match to the existing data then press the enter key for info to be returned. For example, user typed "1/1/2010" but if user types "01/01/2010" no data will return. The query is also case sensitive so if user enters "El Cajon" instead of "el cajon" or "CA", "California" instead of "ca" no data will return. To avoid this I suggest:

- replace text field with drop-down field which will have all possible options available and eliminate any possible misspelling, case-sensitive, missing etc. 
- change the "listen to event" code to update the table whenever a new dropdown field has been select vs. pressing enter key
