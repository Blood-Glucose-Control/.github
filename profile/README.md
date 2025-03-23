# Blood Glucose Control with [WAT.ai](https://watai.ca/) and [Gluroo Imaginations Inc](https://gluroo.com/).

Welcome to the Blood Glucose Control AI Design Team organization page!

* Our hugging face account: [Blood-Glucose-Control](https://huggingface.co/Blood-Glucose-Control)

* TPMs: [Christopher Risi](https://github.com/RobotPsychologist), [Walker Payne](https://github.com/walkerpayne), [Dvir Zagury-Grynbaum](https://github.com/dvirzg).

* [Check out our FAQs](https://github.com/RobotPsychologist/bg_control/wiki/Frequently-Asked-Questions)!

## Background

Diabetes requires a unique way of living. Type 1 impacts nearly 10 million people worldwide, and Type 2 impacts over 500 million. For most, to successfully manage the disease and avoid its long-term adverse effects, you must have detailed fitness and nutrition tracking, not unlike professional athletes or bodybuilders, but with the added complication of knowing how and when to administer insulin. Some can get away without detailed monitoring if they are highly habitual. For most, that’s an undesirable restriction, but where a Person with Diabetes (PWD) falls on that scale is a trade-off that depends on the individual.

Our industry parterner Gluroo, aims to alleviate PWD's cognitive burden by making fitness, nutrition, and insulin tracking as streamlined as possible. With good tracking and monitoring, the PWD may learn minor behavioural modifications that improve their BG control. Learning these modifications on your own can take months or years of experimentation and often requires waiting months for long meetings with diabetic care professionals to evaluate what changes are necessary. With our organization BGC-AI, one of our main goals is to develop AI tools that directly make this process simpler.

Our projects focus on improving short-term prandial (during meal-time) and postprandial blood glucose level outcomes; to leverage semi-supervised learning to identify unlabelled meals in time-series blood glucose data; to develop meal-scoring functions; explore causal machine-learning techniques to suggest optimal treatments for user profiles; develop probalistic forcasting models to alleviate diabetes distress around nocturnal hypoglycemia, and much more! We aim to provide actionable insights to PWDs and their care practitioners, enhancing health outcomes and quality of life.

### Affiliations

* [Gluroo](https://gluroo.com/) is our main industry partner. Gluroo provides us access to massive de-identified datasets that allow us to push our models to the limits. Diabetes is a challenging space for AI research due to the lack of large real-world datasets, Gluroo helps solve that problem for us. Two of our TPMs work/consult for Gluroo, and we're also thrilled that numerous BGC-AI members have been hired for paid internships at Gluroo.
* [skTime](https://www.sktime.net/en/stable/) continues to be one of the most integral libraries to our work. They also provide research mentorship through access to world class time series researchers Franz Kiraly, Martin Tveten, and Benedikt Heidrich. Some of our members have also had the opportunity to make  open source contirbutions to skTime! So this has been a mutually beneficial partnership that our orgnaization is grateful for.
* [WAT.ai](https://watai.ca/) is a student-run Artificial Intelligence organization at the University of Waterloo. Our TPMs started this organization through their organization, WAT.ai was integral in providing a pipeline to hundreds of talented students interested in developing or showcasing thier AI development skills.

## Active Projects

1. **Automatic Meal Identification** develop the ability to identify unlabelled meals in time series BG data. The goal of this project is to be able to identify the top 'n' most significant meals of a PWD per day from continuous glucose monitor data alone. The time series detection models are evaluated on various metrics that measure the proximity of the identified meal regions or change poitns to ground truth labels. Detailed meal logging can help contributed to improved glycemic control, but continue to be a burden

   - **_AI Topics:_** _Feature Engineering, Time Series Annotation, Time Series Representation Learning, Supervised Learning, Semi-Supervised Learning_

2. **Semi-Supervised Time Series Meal Identification Benchmark** - 

3. **Causal and Time Series Modeling for Diabetes Management: Prandial Interventions and Counterfactuals** develop and explore various causal machine learning techniques for estimating the effects of and suggesting pre/postprandial interventions to improve meal scores (uplift modeling, intervention estimations). Develop the ability to provide hindsight (counterfactuals) to PWD, providing interactive experimentation abilities to diabetic care practitioners. This helps PWDs find their personalized best call of action to get intended health results and helps them experiment with different strategies and their direct effects. This is seen in counterfactual estimations as recommendations for better T1D management. E.g. if a user did $X$ during that meal, the glucose response curve would have looked like $Y$.
   - **_AI Topics:_** _Time Series Causal Modelling, Causal Inference, Intervention and Counterfactual Estimation, Causal AI._

   Improving short-term prandial (meal-time) / postprandial outcomes by providing counterfactuals to PWDs and their diabetic care practitioners.

      > improved short-term decisions -> improved long-term disease outcomes

   Many things impact a ‘relatively successful’ prandial BG behaviour, the main behavioural ones to focus on tend to be insulin dosing quantity, insulin dosing timing, basal insulin requirements, physical activity (in preceding hours and immediately postprandial), quantity of carbohydrates consumed, glycemic index of carbohydrates consumed, alcohol consumed with meal (slows absorption of carbs), amount of fat and protein consumed with meal (slows absorption of carbs but creates a delayed glucose spike).

   If we can provide counterfactuals that improve PWD’s postprandial BG characteristics, we will have made thousands to millions of people’s lives significantly easier and more enjoyable, we will be increasing their freedom to enjoy a wider variety of foods safely, and potentially extending their years living a happy and healthy life.

4. **Long-range nocturnal hypoglycemic forecasting** one of the most distressing aspects of living with T1D is the anxiety and fear surrounding [Dead in Bed (DIB) syndrome](https://www.thieme-connect.com/products/ejournals/pdf/10.4103/2321-0656.140880.pdf). Our goal with this project is to provide T1Ds with a long-range glycemic sleep forecast. Strong, practical, and useable results in this space would [significantly impact the diabetes community in relieving diabetes distress](https://journals.sagepub.com/doi/full/10.1177/19322968241267886).
   - **AI Topics**: *Time series Forecasting*

5. **Blood Glucose Controller** develop a simulated insulin BG-controller using [open source FDA approved blood glucose control simulators](https://github.com/jxx123/simglucose).
   - **_AI Topics:_** _Representation Learning, Time Series Forecasting, Reinforcement Learning, Neuromorphic Computing._

### Future Projects

1. **Diabetes Foundation Model**
   
2. **Meal Scoring** develop the ability to score/evaluate T1D postprandial Blood Glucode Level (BGL) characteristics to serve as a meal-scoring function. Find prandial measures that strongly correlate or predict long-term diabetic health indicators like [Time-in-Range (TIR)](https://jdrf.ca/resources/time-in-range/), [HbA1C%](https://www.breakthrought1d.org/news-and-updates/jdrf-report-how-hba1c-came-1976/), [Glucose Management Indicator](https://diabetesjournals.org/care/article/41/11/2275/36593/Glucose-Management-Indicator-GMI-A-New-Term-for), and [Glucose Variability (GV)](https://journals.lww.com/indjem/fulltext/2013/17040/glycemic_variability__clinical_implications.10.aspx).
   - **_AI Topics:_** _Feature Engineering, Time Series Forecasting, Time Series Representation Learning_



