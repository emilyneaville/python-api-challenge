#### What is the weather like as we approach the equator?

That’s obvious. It gets hotter. But, if pressed for more information, how can we prove it? Data's true power is its ability to definitively answer questions such as this. This project will utilize Python requests, APIs, and JSON traversals to answer this fundamental question and provide meaningful insight.

---

#### Part 2: The Ideal Vacation

Part 2 of this project utilizes Jupyter notebooks, the geoViews Python library, and the Geoapify API to plan future vacations and create map visualizations. First is a map that displays a point for every city from part 1. The size of the point is the humidity in each city. 

![bokeh_plot](https://user-images.githubusercontent.com/119391399/217397532-49febb51-82c1-4dc4-9f0f-d4b7398c55f9.png)

Using this visualization, we can begin to plan our ideal vacation cities, complete with the nearest hotels. The ideal vacation cities have:
- A max temperature lower than 27 degrees (C) but higher than 21 (C)
- Wind speed less than 4.5 m/s
- Zero cloudiness

![bokeh_plot1](https://user-images.githubusercontent.com/119391399/217397654-c587200e-da93-4ac2-80b5-16631b81b6e0.png)
