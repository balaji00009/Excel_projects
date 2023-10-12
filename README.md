# Excel_projects
Great Learning Excel Projects (Regression Analysis) and (Data Analysis Tool Pack)
This project Helped to get understand about Statistical Tools,Data Analysis Tool Pack and also Regression
Simple Linear Regression (SLR)
Multilinear Regression (MLR)

  




 

TERRO’S_REA
REAL ESTATE AGENCY
REPORT TOWN BOSTON
BALAJI K| PRICE ESTIMATION | 11th June 2023
 Assignment Submission



Q1:-Generate the summary statistics for each variable in the table. (Use Data analysis tool pack). Write down your observation.
 








                     













                  












                        












                    












                          













                            













                          










                          












                                













Q2) Plot a histogram of the Avg_Price variable. What do you infer?

 








 
Q3) Compute the covariance matrix. Share your observations

	CRIME_RATE	AGE	INDUS	NOX	DISTANCE	TAX	PTRATIO	AVG_ROOM	LSTAT	AVG_PRICE
CRIME_RATE	8.52									
AGE	0.56	790.79								
INDUS	-0.11	124.27	46.97							
NOX	0.00	2.38	0.61	0.01						
DISTANCE	-0.23	111.55	35.48	0.62	75.67					
TAX	-8.23	2397.94	831.71	13.02	1333.12	28348.62				
PTRATIO	0.07	15.91	5.68	0.05	8.74	167.82	4.68			
AVG_ROOM	0.06	-4.74	-1.88	-0.02	-1.28	-34.52	-0.54	0.49		
LSTAT	-0.88	120.84	29.52	0.49	30.33	653.42	5.77	-3.07	50.89	
AVG_PRICE	1.16	-97.40	-30.46	-0.45	-30.50	-724.82	-10.09	4.48	-48.35	84.42

Co-Variance Measure: - (Deep Summary)
•	The term generally defines that how far the observations from the mean, in case of two variables it is called as Co-Variance
•	Crime Rate & Age their values are positive which their values of both were above or below average.
•	Indus & Crime rate their values tend to have negative value, so one of their variable averages is likely to have negative side
•	Indus & Age both variable values were above their averages so it is Positive.
•	NOx & Crime rate has no relation to each other in value tend to have Zero as average.
•	NOx & Age both of their values were above or below their averages, so its covariation tends to remain Positive.
•	NOx & Indus Both of their values were above or below their averages, so its covariation tends to remain Positive.
•	Distance & NOx one of their variables tend to have less value than their average so it tends to have the negative value.
•	Distance & age, Distance & Indus, Distance & NOx all these tend to have both respective variable value High or Low than their averages so it is also positive
•	Tax & crime rate, one of the variables mean tend to have lower mean so this says it is a negative co variance.
•	Tax & Age, Tax & Indus, Tax & NOx, Tax & Distance all the variables of each column gave their mean above or below their average, so it is having positive Co-variation
•	PTRATIO & Crime rate, PTRATIO & Age, PTRATIO & Indus, PTRATIO & NOx, PTRATIO & Distance, PTRATIO & Tax all these tend to have their above or below so it is having positive Co-Variation number.
•	AVG_ROOM & Crime Rate tend to have their variable value above or below their average so it holds the positive Co-Variation.
•	AVG_ROOM & Age, AVG_ROOM & Indus, AVG_ROOM & NOx, AVG_ROOM & Distance, AVG_ROOM & Tax, AVG_ROOM & PTRATIO all the other holds a Negative Co-variance.
•	LSTAT & Crime rate holds negative Co-variance which holds one of their variables is having low value than their average.
•	LSTAT & Age, LSTAT & Indus, LSTAT & NOx, LSTAT & Distance, LSTAT & Tax, LSTAT & PTRATIO all the other holds a positive Co-variation.
•	LSTAT & AVG_ROOM holds a negative Co-variation.
•	AVG_Price & Crime Rate holds a Positive Co-variation which holds a value of above or below their averages.
•	AVG_Price & Age, AVG_Price & Indus, AVG_Price & NOx, AVG_Price & Distance, AVG_Price & Tax, AVG_Price & PTRATIO, AVG_Price & LSTAT Holds a Negative Co-Variation.
•	AVG_Price & AVG_Room Has Positive Co-Variation.





















Q4) Create a correlation matrix of all the variables (Use Data analysis tool pack).

 	CRIME_RATE	AGE	INDUS	NOX	DISTANCE	TAX	PTRATIO	AVG_ROOM	LSTAT	AVG_PRICE
CRIME_RATE	1.00									
AGE	0.01	1.00								
INDUS	-0.01	0.64	1.00							
NOX	0.00	0.73	0.76	1.00						
DISTANCE	-0.01	0.46	0.60	0.61	1.00					
TAX	-0.02	0.51	0.72	0.67	0.91	1.00				
PTRATIO	0.01	0.26	0.38	0.19	0.46	0.46	1.00			
AVG_ROOM	0.03	-0.24	-0.39	-0.30	-0.21	-0.29	-0.36	1.00		
LSTAT	-0.04	0.60	0.60	0.59	0.49	0.54	0.37	-0.61	1.00	
AVG_PRICE	0.04	-0.38	-0.48	-0.43	-0.38	-0.47	-0.51	0.70	-0.74	1.00









Q5) Build an initial regression model with AVG_PRICE as ‘y’ (Dependent variable) and LSTAT variable as Independent Variable. Generate the residual plot
SUMMARY OUTPUT								
								
Regression Statistics							
Multiple R	0.737662726							
R Square	0.544146298							
Adjusted R Square	0.543241826							
Standard Error	6.215760405							
Observations	506							
								
ANOVA								
 	df	SS	MS	F	Significance F			
Regression	1	23243.914	23243.914	601.6178711	5.0811E-88			
Residual	504	19472.38142	38.63567742					
Total	505	42716.29542	 	 	 			
								
 	Coefficients	Standard Error	t Stat	P-value	Lower 95%	Upper 95%	Lower 95.0%	Upper 95.0%
Intercept	34.55384088	0.562627355	61.41514552	3.7431E-236	33.44845704	35.65922472	33.44845704	35.65922472
LSTAT	-0.950049354	0.038733416	-24.52789985	5.0811E-88	-1.0261482	-0.873950508	-1.0261482	-0.873950508

 
 





 
6)Build a new Regression model including LSTAT and AVG_ROOM together as independent variables and AVG_PRICE as dependent variable.

SUMMARY OUTPUT								
								
Regression Statistics							
Multiple R	0.799100498							
R Square	0.638561606							
Adjusted R Square	0.637124475							
Standard Error	5.540257367							
Observations	506							
								
ANOVA								
 	df	SS	MS	F	Significance F			
Regression	2	27276.98621	13638.49311	444.3308922	7.0085E-112			
Residual	503	15439.3092	30.69445169					
Total	505	42716.29542	 	 	 			
								
 	Coefficients	Standard Error	t Stat	P-value	Lower 95%	Upper 95%	Lower 95.0%	Upper 95.0%
Intercept	-1.358272812	3.17282778	-0.428095348	0.668764941	-7.591900282	4.875354658	-7.591900282	4.875354658
AVG_ROOM	5.094787984	0.4444655	11.46272991	3.47226E-27	4.221550436	5.968025533	4.221550436	5.968025533
LSTAT	-0.642358334	0.043731465	-14.68869925	6.66937E-41	-0.728277167	-0.556439501	-0.728277167	-0.556439501
















7)Build another Regression model with all variables where AVG_PRICE alone be the Dependent Variable and all the other variables are independent. Interpret the output in terms of adjusted R square, coefficient and Intercept values. Explain the significance of each independent variable with respect to AVG_PRICE.
SUMMARY OUTPUT								
								
Regression Statistics							
Multiple R	0.832978824							
R Square	0.69385372							
Adjusted R Square	0.688298647							
Standard Error	5.1347635							
Observations	506							
								
ANOVA								
 	df	SS	MS	F	Significance F			
Regression	9	29638.8605	3293.206722	124.9045049	1.9328E-121			
Residual	496	13077.43492	26.3657962					
Total	505	42716.29542	 	 	 			
								
 	Coefficients	Standard Error	t Stat	P-value	Lower 95%	Upper 95%	Lower 95.0%	Upper 95.0%
Intercept	29.24131526	4.817125596	6.070282926	2.53978E-09	19.77682784	38.70580267	19.77682784	38.70580267
CRIME_RATE	0.048725141	0.078418647	0.621346369	0.534657201	-0.105348544	0.202798827	-0.105348544	0.202798827
AGE	0.032770689	0.013097814	2.501996817	0.012670437	0.00703665	0.058504728	0.00703665	0.058504728
INDUS	0.130551399	0.063117334	2.068392165	0.03912086	0.006541094	0.254561704	0.006541094	0.254561704
NOX	-10.3211828	3.894036256	-2.650510195	0.008293859	-17.97202279	-2.670342809	-17.97202279	-2.670342809
DISTANCE	0.261093575	0.067947067	3.842602576	0.000137546	0.127594012	0.394593138	0.127594012	0.394593138
TAX	-0.01440119	0.003905158	-3.687736063	0.000251247	-0.022073881	-0.0067285	-0.022073881	-0.0067285
PTRATIO	-1.074305348	0.133601722	-8.041104061	6.58642E-15	-1.336800438	-0.811810259	-1.336800438	-0.811810259
AVG_ROOM	4.125409152	0.442758999	9.317504929	3.89287E-19	3.255494742	4.995323561	3.255494742	4.995323561
LSTAT	-0.603486589	0.053081161	-11.36912937	8.91071E-27	-0.70777824	-0.499194938	-0.70777824	-0.499194938

















 	Coefficients	Description
Intercept	29.24131526	Intercept Holds a pretty good value of 29.24($$$)
CRIME_RATE	0.048725141	Since this value having the P-value of 0.53 which is not acceptable should be < 0.05, so it is not considered as good predictor and also this contains almost no relation with Avg_Price (0.04)
AGE	0.032770689	For each value Increase of age variable, the average predicted price of House increases by 0.0327
INDUS	0.130551399	For each value of Increase of Indus variable predicted price of House increases by 0.1305 which Impacts the House price to increase (as this increases Employment chances when Industries started to Implement their Plants over Boston.
NOX	-10.3211828	For each value Increase of NOx variable, the average predicted price of House decreases by -10.32, this affects the pricing because Higher NOx in the air tends to be Poisonous & also leads to Pollution of air creates brown layer in Air causing accidents, etc
DISTANCE	0.261093575	For each value Increase of distance variable predicted price of House increases by 0.2610, so people want to stay in City side rather than staying nearby highways.
TAX	-0.01440119	For each value Increase of tax variable, the average predicted price of House decreases by -0.014, which affects the house pricing when tax Increases
PTRATIO	-1.074305348	For each value of Increase of PTRATIO variable the average predicted price of House decreases by -1.074, this area contains lack of Pupil or Lack of Teacher which Impacts the future student’s life & also affects the house pricing
AVG_ROOM	4.125409152	For each value of Increase of AVG_ROOM variable predicted price of House increases by 4.1254, when number of rooms increases the average price of House also Increases, Considered as good factor.
LSTAT	-0.603486589	For each value Increase of LSTAT variable the average predicted price of House decreases by -0.603, the lower the status of people tend to affect the house pricing, maybe they lack in paying the house rent or some other factors








8)Pick out only the significant variables from the previous question. Make another instance of the Regression model using only the significant variables you just picked and answer the questions below:

SUMMARY OUTPUT								
								
Regression Statistics							
Multiple R	0.832835773							
R Square	0.693615426							
Adjusted R Square	0.688683682							
Standard Error	5.131591113							
Observations	506							
								
ANOVA								
 	df	SS	MS	F	Significance F			
Regression	8	29628.68142	3703.585178	140.6430411	1.911E-122			
Residual	497	13087.61399	26.33322735					
Total	505	42716.29542	 	 	 			
								
 	Coefficients	Standard Error	t Stat	P-value	Lower 95%	Upper 95%	Lower 95.0%	Upper 95.0%
NOX	-10.27270508	3.890849222	-2.640221837	0.008545718	-17.9172457	-2.628164466	-17.9172457	-2.628164466
PTRATIO	-1.071702473	0.133453529	-8.030529271	7.08251E-15	-1.333905109	-0.809499836	-1.333905109	-0.809499836
LSTAT	-0.605159282	0.0529801	-11.42238841	5.41844E-27	-0.70925186	-0.501066704	-0.70925186	-0.501066704
TAX	-0.014452345	0.003901877	-3.703946406	0.000236072	-0.022118553	-0.006786137	-0.022118553	-0.006786137
AGE	0.03293496	0.013087055	2.516605952	0.012162875	0.007222187	0.058647734	0.007222187	0.058647734
INDUS	0.130710007	0.063077823	2.072202264	0.038761669	0.006777942	0.254642071	0.006777942	0.254642071
DISTANCE	0.261506423	0.067901841	3.851242024	0.000132887	0.128096375	0.394916471	0.128096375	0.394916471
AVG_ROOM	4.125468959	0.44248544	9.323400461	3.68969E-19	3.256096304	4.994841615	3.256096304	4.994841615
Intercept	29.42847349	4.804728624	6.124898157	1.84597E-09	19.98838959	38.8685574	19.98838959	38.8685574


















Regression Analysis Output: -

Predicted AVG_PRICE = 29.428 – 10.272 * NOX – 1.071 * PTRATIO – 0.605 * LSTAT – 0.014 * TAX + 0.032 *AGE + 0.130 * INDUS + 0.261 * DISTANCE + 4.125 * AVG_ROOM 

Conclusion (Negative Factors): - 
		    This equation itself shows the House price affecting factors are NOX, PTRATIO, LSTAT, TAX.
	To conclude this EDA and regression analysis, Terro’s Rea agency must focus on NOX may be Boston must be polluted area if Industries and factories, Vehicles, such factors increase the Pricing of this area will decrease.

	PTRATIO ratio is also tends affect because in Boston town there may be lack of schools, this is also a considering factor while purchasing the House, in this model this also tends to decrease.

	LSTAT ratio Lower the status of population % increase people can not afford the Houses as your agency quoted price, increase in lower status tends to decrease the pricing of Houses in that Area.


	Tax of the property Increases, this also tends to affect the pricing

Conclusion (Positive Factors): -

	Age of Houses tend to increase the predicted price of House also tends to Increase which is good Positive factor for Agency’s Consideration, because people likely to buy the House before 1940.

	Indus the proportion of non-Retail land Business acres per town in this case people are expecting for Industrial accommodation for their future work, so this factor is also considered as Price increasing factor for Agency.



	Distance from High way is also good factor people don’t want to stay near High way rather they choose to reside nearby Town or Cities, so distance from High way Increases the House pricing also tends to Increase.

	The Average Room Size Increase the pricing also tends to Increase, this is good factor when it comes to pricing.







Result:
Terro’s Rea agency can Focus the above-mentioned equation for predicting price of the Houses in Boston Town for the given data set of 506 Houses.
 

 



