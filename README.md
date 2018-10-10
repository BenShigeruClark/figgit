# figgit - Online Media Search Tool

With our project we wanted to address a growing online issue, the quest for truth. With fake news taking over our news feed, how do we know what is fact and what is fiction?

We live in an age where information is available in overabundance. Everyday we are bombarded with news stories on social media, television, radio and our mobile devices. While many of these stories sound true, it’s important to research anything we decide to pass on or repost to avoid spreading false or misleading information. So how do we research the news that we hear?  Where do we start and how do we know we can trust the results we come up with to be unbiased and true?

The Figgit app seeks to solve these dilemmas by providing a comprehensive online search tool that provides background information on news articles and their sources. A simple keyword search returns relevant news articles based on the users location and the keyword entered in the search bar. The results will provide source information for each article along with a media bias rating scale. 

Search results are sorted by keyword relevancy and he users location. This helps to narrow down the search results and return only the most relevant articles to the search. Each search result contains the source, headline, publication date, and author of the article. 

It also contains a Bias Rating scale that illustrates the media bias commonly associated with that particular news source. The Bias Rating is based on news source reporting and its tendency to publish stories with a liberal, conservative or neutral view. The rating is defined by a row of boxes, with the red box depicting views from left to right, the far left being the extreme left or liberal view and the far right being the extreme right or conservative view. The ratings are based on data researched from various sources like Market Watch, Business Insider and AllSides.com, a website that collects community feedback to present a media bias rating for online news sources.

The purpose of the bias rating is not to tell the reader whether a story is accurate or fake news, but to provide the user with information pertaining to where the story originated while also providing additional stories on the same subject from an alternate source. It encourages the reader to view information from a different perspective and, ultimately, be better informed.

## Design Process

Our design process began with a discussion about the potential projects we could work on and what we hoped to achieve by completing the site. We decided on addressing the issue of fake news and media bias. We began searching various News Site API’s. We decided on NewsAPI.org because it offered the widest range of news sources available. We discussed the look and functionality of our site and concluded that a simple “Google” like interface would work best. 

While coming up with a simple logo design and user interface layout, we developed the backend code to get data from the API servers and convert it to JavaScript objects. Once the UI development was complete, we then targeted the appropriate page elements to pull values from and push data to the page.

Once the initial search and response process was working, we began adding more functionality to the site like location identification and language preference. We also added the Media Bias Rating scale based on research from numerous media rating sites.

The final launch required more code development to refine the search results to return specific relevant data to the search query. Final bug fixes and code correction were done on GitHub. We utilized GitHub Projects and Slack to communicate during the project.

## Technologies Used

* HTML - Provides the framework for the page. Displays all the graphics, text, input fields and a results section to post the search results data.
* CSS - Adds styling to the page, not only for aesthetics, but also to provide the user an intuitive interface.
* JavaScript - Adds functionality and controls the events that dynamically push and pull data to and from the page. 
* jQuery - Abbreviates the JavaScript code, making it easier to read and write.
* API Servers - Two API servers are used to collect data. www.APInews.org for media source data  and www.googleapis.com for user location data. Results from these servers are pushed to the page as search results and user location information. The user location is also used to filter the search results by region.
* AJAX - AJAX makes a call to the API servers so Figgit can be updated asynchronously by exchanging data with the News API and IP API behind the scenes.
* JSON - JSON formats the data that is returned by the AJAX call to an object array which we can easily be converted into Javascript objects.
* GitHub - Github is the site we used to collaborate and post changes while working on different areas of the scripts. Github pages is hosting the site.

## Plans for Future Development

Our plans for future development include:

* Refining data response to limit search results so that only articles relevant to the user search input will appear.
* Creating a database that will allow the user to rate articles and news sources and dynamically update Media Bias ratings accordingly.
* Filter news articles by region and offer translation options in various languages.
* Filter search results by the author of the article.
* Add an option for user to request more results if desired.