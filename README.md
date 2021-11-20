# Short-story-SanDiego
### Course: CMPE255-Data Mining
### Professor: Vijay Eranti
### TA: Tamanna Mehta, Devangi Doshi
### Presentation Video:
### Presentation Slides: https://docs.google.com/presentation/d/17ZX8kZje-dQUQ2G0Wna53GixhZbr0rNb/edit?usp=sharing&ouid=117008265698718757170&rtpof=true&sd=true


San Diego’s housing market, like the rest of California, is seeing an increase in housing prices and sales. For 11 months in a row, the median home value in Southern California has grown by the double digits. Homes on the market are selling quickly, with numerous offers frequently exceeding the sellers’ asking price. In 2021, buyer desire is likely to continue strong, but rising mortgage interest rates will put a strain upon that.

When purchasing a home, we evaluate factors such as the size of the property, the number of rooms, the location, the walkscore, and whether or not the area is in a suitable school district, HOA ,Mortgage etc. Basically, real estate rates are increasing!! But, in the end, everyone wants to buy a property with good amenities that meets the above-mentioned evaluation criteria.

### Now the question is how should buyer select or consider such options?

Make use of internet appraisal tools. “How much is my house worth?” is a question that many people ask. There are numerous of house value estimators available online.
1.Obtain a market comparison analysis

2.Use the FHFA Property Price Indices Analyzer to figure out how much your. home is worth

3.Engage the services of a competent appraiser

4.Compare and contrast equivalent real estate

If our business case is to find the fine property in san diego, feature importance is best which helps to find best features for the business case.We may employ the latent variables of walk score, crime rate, and school proximity rank in fractal clustering and prediction to improve the model’s accuracy. Clustering algorithms could help to get to know property distribution by zip code.Moreover you can analyze if the property price is high then what is the walkscore of the real estate in addition to this, you can identify if the crimerate is less in that particular area etc.

### Feature Transformation and Data enrichment

1. The technique of changing your data while maintaining the knowledge is known as feature transformation. These changes will make it much easier to grasp Machine Learning methods, resulting in improved outcomes. In feature transformation we can merge two colums and create one column from it. 
2. Lets say I have two columns one has Street Address and other has zipcodes simply, I can merge those two columns and create another column Full Address which will have street address and zip codes. Code snippet will be as follows

### Web Scraping

1. Web scrapping helps to get the data from zillow which has data of properties. We can scrape the data either by tool or by coding. By doing so we can find walkscore, Crime rate, School Proximity etc and simply merge all the dataset for better visualization and better understansing of the dataset.
2. Web scraping on Zillow centered on a location and postcode can provide information about each property such as rent, Zestimate, HOA, Mortgage, Expected payment, sold cost, percent rise in price in the last 12 months, and percent increase for the following year. 
3. By introducing headers and reading only just few records at a time, we can fix the captcha and cookie issues. The first step in data enrichment was to combine it with the housing dataset. Following are the essential imports for Web Scrapping.

### Feature Engineering

1. We can use Linear Regression to predict the house prices and along with that we can find a corelation between categories and draw a heatmap showing correlation between each columns.
2. Linear regression model to predict a continuous scale variable to use a set of extracted features, whereas Logistic Regression is used to forecast a categorical variable. Regression issues are resolved using linear regression, while classification problems are solved using logistic regression.
3. So basically logical and linear regression would help to define if particular property is best to buy by spliiting data in test and train.


