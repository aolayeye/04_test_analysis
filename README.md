### 04_test_analysis
### Choosing the right smoothing technique
![Wk4_p17](https://github.com/aolayeye/04_test_analysis/assets/67847583/923155b7-e2d9-40d3-9340-7cfbb36879de)


## Chapter 8
### Modeling a Price-Demand Function

A market research study has collected data on sales volumes for different levels of pricing of a particular product. The data and a scatter diagram are shown in Figure 8.2 (Excel file Price-Sales Data). The relationship between price and sales clearly appears to be linear, so a linear trendline was fit to the data. 

### Predicting Crude Oil Prices

Figure 8.3 shows a chart of historical data on crude oil prices on the first Friday of each month from January 2006 through June 2008 (data are in the Excel file Crude Oil Prices). Using the Trendline tool, we can try to fit the various functions to these data (here x represents the number of months starting with January 2006). 

Procter & Gamble (P&G) laundry products are global household brands that include Tide, Dash, and Gain and are offered in several physical product forms, including powders, liquids, pods, tablets, and bars. These products are manufactured at more than 30 sites and sold in more than 150 countries worldwide. The design of laundry product formulations (that is, ingredient composition of chemical mixtures) has become more complex over the years because of challenges such as product-portfolio expansion, rapidly changing ingredient costs and availability, and increasing competitive activity.

P&G’s research and development organization is at the forefront of the development and adoption of modeling tools that enable the company to make better decisions on product formulation, processing, and manufacturing. These include empirical models that predict chemical reactions during manufacturing, in-use physical properties of the product, technical performance of the product, and even consumer acceptance rates. These tools enable researchers to instantly predict a product’s physical properties and performance, integrate models, and balance production trade-offs using a variety of predictive and prescriptive capabilities. Predictive models the company has used include third-order polynomial functions that capture the two performance qualities of a mixture: stain removal and whiteness. For example, stain removal performance is predicted by the stain removal index (SRI) response function, which has the following form:
where Ci represent coefficients and vi represent design variables: such as wash concentrations (milligrams per liter) of chemical ingredients and wash conditions (for example, temperature).

### Home Market Value Data

The market value of a house is typically related to its size. In the Excel file Home Market Value (see Figure 8.6), data obtained from a county auditor provide information about the age, square footage, and current market value of houses in a particular subdivision. We might wish to investigate the relationship between the market value and the size of the home. The independent variable, X, is the number of square feet, and the dependent variable, Y, is the market value.

### Analytics in Practice: Using Linear Regression and Interactive Risk Simulators to Predict Performance at Aramark4

4The author expresses his appreciation to John Toczek, Manager of Decision Support and Analytics at Aramark Corporation.
[Return to reference]

Aramark is a leader in professional services, providing award-winning food services, facilities management, and uniform and career apparel to health care institutions, universities and school districts, stadiums and arenas, and businesses around the world. Headquartered in Philadelphia, Aramark has approximately 255,000 employees serving clients in 22 countries.

Aramark’s Global Risk Management Department (GRM) needed a way to determine the statistical relationships between key business metrics (for example, employee tenure, employee engagement, a trained workforce, account tenure, service offerings) and risk metrics (for example, OSHA rate, workers’ compensation rate, customer injuries) to understand the impact of these risks on the business. GRM also needed a simple tool that field operators and the risk management team could use to predict the impact of business decisions on risk metrics before those decisions were implemented. Typical questions they would want to ask were, What would happen to our OSHA rate if we increased the percentage of part time labor? and How could we impact turnover if operations improved safety performance?

Aramark maintains extensive historical data. For example, the GRM group keeps track of data such as OSHA rates, slip/trip/fall rates, injury costs, and level of compliance with safety standards; the Human Resources department monitors turnover and percentage of part-time labor; the Payroll Department keeps data on average wages; and the Training and Organizational Development Department collects data on employee engagement. Excel-based linear regression was used to determine the relationships between the dependent variables (such as OSHA rate, slip/trip/fall rate, claim cost, and turnover) and the independent variables (such as the percentage of part-time labor, average wage, employee engagement, and safety compliance).

Although the regression models provided the basic analytical support that Aramark needed, the GRM team used a novel approach to implement the models for use by their clients. They developed “interactive risk simulators,” which are simple online tools that allowed users to manipulate the values of the independent variables in the regression models using interactive sliders that correspond to the business metrics and instantaneously view the values of the dependent variables (the risk metrics) on gauges similar to those found on the dashboard of a car.

Figure 8.19 illustrates the structure of the simulators. The gauges are updated instantly as the user adjusts the sliders, showing how changes in the business environment affect the risk metrics. This visual representation made the models easy to use and understand, particularly for nontechnical employees.
Figure 8.19 Structure of an Interactive Risk Simulator
An illustration shows a 3 stages process.

 
#### Figure 8.19 Full Alternative Text

GRM sent out more than 200 surveys to multiple levels of the organization to assess the usefulness of the interactive risk simulators. One hundred percent of respondents answered “Yes” to “Were the simulators easy to use?” and 78% of respondents answered “Yes” to “Would these simulators be useful in running your business and helping you make decisions?” The deployment of interactive risk simulators to the field has been met with overwhelming positive response and recognition from leadership within all lines of business, including frontline managers, food-service directors, district managers, and general managers.

### Modeling Beverage Sales Using Curvilinear Regression

The Excel file Beverage Sales provides data on the sales of cold beverages at a small restaurant with a large outdoor patio during the summer months (see Figure 8.34). The owner has observed that sales tend to increase on hotter days. Figure 8.35 shows linear regression results for these data. The U-shape of the residual plot (a second-order polynomial trendline was fit to the residual data) suggests that a linear relationship is not appropriate. To apply a curvilinear regression model, add a column to the data matrix by squaring the temperatures. Now, both temperature and temperature squared are the independent variables. Figure 8.36 shows the results for the curvilinear regression model. 

## Chpater 9
### Analytics in Practice:Forecasting Call-Center Demand at L.L.Bean1

1Andrews, B.H., and S. M. Cunningham, “L.L. Bean Improves Call-Center Forecasting,” Interfaces, Vol. 25, No. 6, pp.1-13, November-December, 1995.
[Return to reference]

Many of you are familiar with L.L.Bean, a retailer of high-quality outdoor gear. A large percentage of the company’s sales are generated through orders to its call center (the call center can account for over 70% of the total sales volume). Calls to the L.L.Bean call center are classified into two types: telemarketing (TM) and telephone inquiry (TI). TM calls are those made for placing an order, whereas TI calls involve customer inquiries, such as order status or order problems. TM calls and TI calls differ in duration and volume. The annual call volume for TM calls is much higher than that for TI calls, but the duration of a TI call is generally much longer than the duration of a TM call.

Accurately forecasting the demand of TM and TI calls is very important to L.L.Bean to reduce costs. Accurate forecasts allow for properly planning the number of agents to have on hand at any point in time. Too few agents result in lost sales, loss of customer loyalty, excessive queue times, and increased phone charges. Too many agents obviously result in unnecessary labor costs.

L.L.Bean developed analytical forecasting models for both TM and TI calls. These models took into account historical trends, seasonal factors, and external explanatory variables such as holidays and catalog mailings. The estimated benefit from better precision from the two forecasting models was approximately $300,000 per year.


### Predicting the Price of Oil

In early 1998, the price of oil was about $22 a barrel. However, in mid-1998, the price of a barrel of oil dropped to around $11. The reasons for this price drop included an oversupply of oil from new production in the Caspian Sea region, high production in non-OPEC regions, and lower-than-normal demand. In similar circumstances in the past, OPEC would meet and take action to raise the price of oil. Thus, from historical analogy, we might forecast a rise in the price of oil. OPEC members did, in fact, meet in mid-1998 and agreed to cut their production, but nobody believed that they would actually cooperate effectively, and the price continued to drop for a time. Subsequently, in 2000, the price of oil rose dramatically, falling again in late 2001.

### Identifying Trends in a Time Series

Figure 9.1 shows a chart of total energy consumption from the data in the Excel file Energy Production & Consumption. This time series shows an upward trend. However, we see that energy consumption was rising quite rapidly in a linear fashion during the 1960s, then leveled off for a while and began increasing at a slower rate through the 1980s and 1990s. At the end of the time series, we actually see a slight downward trend. This time series, then, is composed of several different short trends.

#### Using Excel’s Moving Average Tool

For the Tablet Computer Sales Excel file, select Data Analysis and then Moving Average from the Analysis group. Excel displays the dialog box shown in Figure 9.7. You need to enter the Input Range of the data, the Interval (the value of k), and the first cell of the Output Range. To align the actual data with the forecasted values in the worksheet, select the first cell of the Output Range to be one row below the first row of the time series. (See Figure 9.8. The first value of the time series starts in cell B4, so the output range is chosen to start in cell C5.). You may also obtain a chart of the data and the moving averages, as well as a column of standard errors, by checking the appropriate boxes. However, we do not recommend using the chart or error options because the forecasts generated by this tool are not properly aligned with the data (the forecast value aligned with a particular data point represents the forecast for the next month) and, thus, can be misleading. Rather, we recommend that you generate your own chart, as we did in Figure 9.6. Figure 9.8 shows the results produced by the Moving Average tool (with some customization of the formatting). Note that the forecast for week 18 is aligned with the actual value for week 17 on the chart. Compare this to Figure 9.6 and you can see the difference.

### Double Exponential Smoothing

Figure 9.13 shows a portion of the Excel file Coal Production, which provides data on total tons produced from 1960 through 2011. The data appear to follow a linear trend. We will apply double exponential smoothing on just the first ten years of the data to illustrate the process.

### Regression-Based Forecasting for Natural Gas Usage

With monthly data, as we have for natural gas usage in the Gas & Electric Excel file, we have a seasonal categorical variable with
levels. As discussed in Chapter 8, we construct the regression model using

dummy variables. We will use January as the reference month; therefore, this variable does not appear in the model:
This coding scheme results in the data matrix shown in Figure 9.17. This model picks up trends from the regression coefficient for time and seasonality from the dummy variables for each month. The forecast for the next January will be The variable coefficients (betas) for each of the other 11 months will show the adjustment relative to January. For example, the forecast for next February will be and so on.

### Forecasting Gasoline Sales Using Simple Linear Regression

Figure 9.22 shows gasoline sales over ten weeks during June through August along with the average price per gallon and a chart of the gasoline sales time series with a fitted trendline (Excel file Gasoline Sales). During the summer months, it is not unusual to see an increase in sales as more people go on vacations. The chart shows a linear trend, although
is not very high. 


### Analytics in Practice: Forecasting at NBCUniversal2

2Based on Srinivas Bollapragada, Salil Gupta, Brett Hurwitz, Paul Miles, and Rajesh Tyagi, “NBC-Universal Uses a Novel Qualitative Forecasting Technique to Predict Advertising Demand,” Interfaces, 38, 2 (March–April 2008): 103–111.
[Return to reference]

NBCUniversal (NBCU), a subsidiary of Comcast, is one of the world’s leading media and entertainment companies in the distribution, production, and marketing of entertainment, news, and information. The television broadcast year in the United States starts in the third week of September. The major broadcast networks announce their programming schedules for the new broadcast year in the middle of May. Shortly thereafter, the sale of advertising time, which generates the majority of revenues, begins. The broadcast networks sell 60% to 80% of their airtime inventory during a brief period starting in late May and lasting two to three weeks. This sales period is known as the upfront market. Immediately after announcing their program schedules, the networks finalize their ratings forecasts and estimate the market demand. The ratings forecasts are projections of the numbers of people in each of several demographic groups who are expected to watch each airing of the shows in the program schedule for the entire broadcast year. After they finalize their ratings projections and market-demand estimates, the networks set the rate cards that contain the prices for commercials on all their shows and develop pricing strategies.


Forecasting upfront market demand has always been a challenge. NBCU initially relied on historical patterns, expert knowledge, and intuition for estimating demand. Later, it tried time-series forecasting models based on historical demand and leading economic indicator data and implemented the models in a Microsoft Excel–based system. However, these models proved to be unsatisfactory because of the unique nature of NBCU’s demand population. The time-series models had fit and prediction errors in the range of 5% to 12% based on the historical data. These errors were considered reasonable, but the sales executives were reluctant to use the models because the models did not consider several qualitative factors that they believed influence the demand. As a result, they did not trust the forecasts that these models generated; therefore, they never used them. Analytics staff at NBCU then decided to develop a qualitative demand forecasting model that captures the knowledge of the sales experts.

Their approach incorporates the Delphi method and “grass-roots forecasting,” which is based on the concept of asking those who are close to the end consumer, such as salespeople, about the customers’ purchasing plans, along with historical data to develop forecasts. Since 2004, more than 200 sales and finance personnel at NBCU have been using the system to support sales decisions during the upfront market when NBCU signs advertising deals worth more than $4.5 billion. The system enables NBCU to sell and analyze pricing scenarios across all NBCU’s television properties with ease and sophistication while predicting demand with a high accuracy. NBCU’s sales leaders credit the system with having given them a unique competitive advantage.
