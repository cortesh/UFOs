
# UFOs : "The Truth Is Out There"

## Overview of Project: 
The objective of this project is to take Dana’s webpage and dynamic table, and provide a more in-depth analysis of UFO sightings by allowing users to filter for multiple criteria at the same time. City, state, country, and shape filters will be added to the date field for this purpose.

## Results: 
This website has great potential provided that the data is robust and comprehensive.  Users simply type in to the search box their search criteria and hit enter, and the results magically appear.  Say your user wishes to see how many sightings there was on "1/1/2020" in "ca" whose shape was "light".  The user need only type in the search criteria based on format in the default values in the fields and the result would look like this:

![search](https://user-images.githubusercontent.com/26439642/126041761-489593af-6994-484f-be05-15036f19c574.PNG)



## Summary: 

This webpage is well designed and attractive to view. However, the search capabilities are quite limited.  The main drawback to this design is that there is no ability to aggregate finds, making it very difficult to gain any meaningful insights from the data.  If this ability were built, users would be able to discover which states have the highest sightings for example.

![top_10_states](https://user-images.githubusercontent.com/26439642/126041773-ad648d76-4885-4d81-8366-37cf68b1931c.png)


Even more interesting is whether there are any significant differences by country region or better still, how many sightings took place near military installations.  For that, one would need to enrich the dataset with external geodata.

We might also be able to analyze what kinds of shapes are most prevalent.

![top_10_shapes](https://user-images.githubusercontent.com/26439642/126041784-dd8dbeda-ec20-4d78-bf50-d8bfea542a59.png)

Other issues include the duration field which has not been normalized, making analysis of the data impossible in its current form.  Another potential analysis would be to use JavaScript to parse words in the comment field to find patterns of descriptions.
