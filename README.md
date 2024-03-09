# cement-manufacturing-automation

by Shashi Ranjan Yadav

Dataset
Concrete is the most important material in civil engineering. The Cement Manufacturing Dataset is a survey of concrete samples providing the measurement records of ingredients used. These ingredients include cement, blast furnace slag, fly ash, water, superplasticizer, coarse aggregate, and fine aggregate - all measured in kg in a m3 mixture. The actual concrete compressive strength (MPa) for a given mixture under a specific age (days) was determined from laboratory. Thus, the data has eight (8) quantitative input variables,and one (1) quantitative output variable, and 1030 instances (observations).


Summary of findings

My main features of interest in this dataset are factors that affects or are directly related to the compressive strength values that was determined from the concrete mixture samples. The findings I derived are based on a cleaned dataset that has neither null nor zero values for all columns.

During the exploration, I found the following:
Majority of the concrete samples fall in the moderate category of strength level, followed by the high category. The less count of observations goes to the 'low' category, while the least count of observations goes to the 'very high' category of strength level.
Across each specific range of cement quantity used, increasing minimal strength is observed with increasing quantity of cement.
The lower the water-to-cement ratio, the greater the compressive strength.
Grade A (the least water-cement ratio) has the highest occurence while Grade F has the least occurence. Grade C has the second highest occurence, followed by Grade B,D, and E in that order.
The maximum compressive strength increases with decreasing water-to-cement(w/c) ratio.
The median value of fine-to-coarse aggregate ratio decreases from grade-A to C (water-cement ratio). Then further increases from grade-D to F.
Low quality water-cement grades D,E & F have maximum compressive strength values of about 40MPa, whereas higher grades of A,B, and C have compressive strength values that goes beyond 40MPa.
Just grade A (water-cement ratio) has cement quantities of 300kg and above only, while the rest has only cement quantities lesser than 250 kg.
Grade-A contains concrete samples that consumed superplastic quantities of 15kg more or less, where as the other grades contains superplastic quantites lesser than 15kg.
Slag is used to complement cement during mixing of concrete, and for each water-to-cement ratio category - increased quantity of slag used improves the maximum compressive strength.
The mode of aggregate ratio which occured between the range of 0.73 to 0.9 is probably too small to make quite a great significant difference in the compressive strengths of concretes taken in this sample.
I'll be introducing the 1st, 4th, 5th, and 10th findings above as key insights for presentation. Other findings from above are either focused on other variables of the dataset or are a repetiton (in some way) of the chosen four key insights.

Key insights for presentation

I introduced the distribution of compressive strength across the sample, and also showed the categorical percentage proportion of compressive strength present in the dataset. Afterwards, I showed the distribution of water-to-cement ratio only, then the bivariate relationship between compressive strength and water-to-cement ratio. Lastly, I communicated the significance of slag in concrete mixtures through multivariate plots that depicts the relationship between slag, cement, compressive strength, and water-to-cement ratio. The changes in design are increasing the data-ink ratio through the removal of border lines; addition of proportion labels to bars to make comprehension easier; using appropriate titles and axis labels; and removing ticks where necessary. I also used different color_palette for different qualitative variables to avoid ambiguity.
