# WIAC Map

### The Wisconsin Intercollegiate Athletic Conference, or WIAC for short, is a Division III athletic conference whose member schools are all located in the state of Wisconsin. This map shows where!

"Wait, what map?" The one that you can access [right here!](https://notfogel.github.io/WIAC-map)











I created this map because, as someone who is not native to Wisconsin, but came to adopt it as my home state after attending the University of Wisconsin-Madison, I have always been enamored by the culture of smaller, affiliate universities of Wisconsin located in smaller cities across the state. Whereas all of my friends from back in suburban Chicago who didn't attend the state's flagship university (University of Illinois Urbana-Champaign) mostly attended state schools in neighboring states, like the University of Iowa and Indiana University, the friends I met at UW-Madison had friends who mostly went to places like UW-La Crosse, UW-Milwaukee, UW-Whitewater, and so on and so forth. I have always admired the sustained infrastructural support required to sustain great universities in smaller places, and have found myself incredibly dismayed to learn about the state government's austertity policy towards those schools in recent years, leading to the [closing of branch campuses in many places across the state](https://www.jsonline.com/story/news/education/2024/09/17/uw-system-no-longer-readily-releasing-branch-campus-enrollment-data/75075570007/), following national trends towards austerity of public education more broadly. Love it or hate it, college athletics is an unavoidable byproduct of university life in the United States; these smaller UW schools aren't just schools: they're football powerhouses! 






To create the map, I used WIAC's website to create a .csv file containing the names of each member school (and former member), then used Wisconsin.edu to add enrollment numbers to this data. I also used county and highway layers to help orient those familiar with Wissconsin's geography with where these schools are located. Some of the state's prominent cities do not have WIAC schools, so I made a separate .csv sheet to ensure that these cities were labeled, too, again to provide geographic context, especially for those less familiar with the state. The labels for each of the schools went through a couple of iterations: at first, I'd had the universities' full names written out (e.g. "University of Wisconsin-Stevens Point"), but after playing around with rule based labeling to try and make them appear nicely, I cut my losses and modified the .csv to shorten "University of Wisconsin" to "UW." This made labeling a breeze, aside from the rule based labeling I had to implement with the western cluster of schools (i.e. UW-Eau Claire, UW-Stout, UW-River Falls), which kept on overlapping with each other. The data that came from the Wisconsin DNR Open Data Portal came projected in the Wisconsin Transverse Mercator Projection (NAD83), and since none of my other data was projected, I opted to stick with that projection for the sake of simplicity (and of course, geometric accuracy).


Enrollment data as of 2023. Sourced from [Wisconsin.edu.](https://www.wisconsin.edu/education-reports-statistics/enrollments/)
Location data calibrated to the center of the logo in the school's football stadium, collected using Google Maps Satellite view.
Graphics from [SVGRepo.com.](svgrepo.com) 
County boundaries, state boundary, and major roads shapefiles from [Wisconsin DNR Open Data Portal.](https://data-wi-dnr.opendata.arcgis.com/)
WIAC alumni data from [Pro Football Reference.](https://www.pro-football-reference.com)
Projection: Wisconsin Transverse Mercator (NAD83).

![If the map isn't loading, yes it is.](WIAC%20layout%20small.png)