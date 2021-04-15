# pic16b_project

Travel Planning
Planned Deliverables: Concisely what you are going to create and what capabilities it will have. Are you making a webapp? A Python package for others to use? Code that creates a novel data set? Etc. Please consider two scenarios:
We will create a travel recommendation generator that will give hotel and sightseeing recommendations based on where you want to go in California. We will also generate the optimal traveling route to go to each of the different locations. The user will input a city in California that they want to go to, which will generate the sightseeing recommendations, then generate hotel recommendations, and the optimal routes between the sightseeing locations and the hotel location.

“Full success.” What will your deliverable be if everything works out for you exactly as you plan?
Our deliverable will be a web app that allows the user to input the city and generates recommendations based on what the user selects. It will then display the optimal routes for traveling between the sightseeing locations and the hotel location.

“Partial success.” What useful deliverable will you be able to offer even if things don’t 100% work out? For example, maybe you aren’t able to get that webapp together, but you can still create a code repository that showcases the machine learning pipeline needed to use to support the app. Have a contingency plan!
Partial success will be defined by a web app that only generates the optimal routes provided that the user has already decided on a hotel and some sightseeing locations.

Resources Required: Do you need certain data sets? Do you know whether those data sets exist? Are they freely accessible? You should do at least a small amount of research for this part, in which you convince me that there is good reason to believe that you will be able to access or obtain the resources needed for your proposal.
TripAdvisor will have the data on the sightseeing locations and the hotel locations, and the google map API will generate the optimal routes.

Tools/Skills Required: What skills will you need? Machine learning, database management, complex visualization, something else? If you know the names of Python packages that you will need to use, include them here. If you’re not sure, just describe the skills or tasks you will need to accomplish.
Web scraping for both hotel and sightseeing recommendations (scrapy)
geographic visualization for plotting sightseeing recommendations (plotly)
Complex visualizations for generating maps of travelling routes  (google maps API)

Risks: What are two things that could potentially stop you from achieving the full deliverable above? Maybe it turns out that the data doesn’t exist and you need to change plan? Or maybe your idea requires more computational power than is available to you? What particular risks might be applicable for your project?
Maybe we can’t scrape Tripadvisor for the data we need, so we would need to find an alternative source of data (either from another website or from a dataset on Kaggle). We also don’t have experience using APIs so it might end up being too difficult to learn how to use an API by ourselves.
Important data component doesn’t exist or for technical reasons, it’s really hard to scrape, or we managed to scrape, but they exist on two sources that we can’t merge.

Ethics: All projects we undertake involve decisions about whose interests matter; which problems are important; and which tradeoffs are considered acceptable. Take some time to reflect on the potential impacts of your product on its users and the broader world. If you can see potential biases or harms from your work, describe some of the ways in which you will work to mitigate them. Remember that even relatively simple ideas can have unexpected and impactful biases. Here’s a nice introductory video for thinking about these questions, and here’s one that goes into somewhat more detail. Here are some relevant examples:
Depending on what recommendations Tripadvisor gives us, maybe the sightseeing locations will privilege some cultural sites above others, depending on what races and ethnicities are more prevalent in a location. Also, if we’re recommending sightseeing and hotel locations, Tripadvisor might favor larger and more popular sites rather than smaller sites.

Tentative Timeline: There will be checkpoints for the project at approximately two-week intervals. With this in mind, please describe what you expect to achieve after two, four, and six weeks. At each stage, you should have “something that works.” For example, maybe by Week 2 you’re ready to demonstrate the data acquisition pipeline, by Week 4 you can demonstrate some data analysis, and by Week 6 you have your full machine learning pipeline set up. Please keep in mind that you’ll be asked to present at each of these checkpoints. Showing “something that works” will usually be necessary for full credit. The “something that works” idea is related to the common concept of “minimum viable products” in software development, and is visually illustrated here:
After two weeks:

After four weeks:

After six weeks:
