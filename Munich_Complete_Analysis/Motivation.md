# Motivation - Bachelor Thesis - Bike Count Analysis

What are the underlying reasons or justifications for choosing this particular topic for my research. 
Why the subject matter is interesting, relevant, or important to me? and potentially to the academic or real-world community.

-> Gaining experience in data related topics -> being able to truly understand what a data scientist does and how they approach different problems that appear when analyzing unknown data from different sources and with different formats

### Personal Interest:
Why am I personally interested in this topic? 
Eventhough it is not a super complex group of data sets, it is complex enough for a bachelor thesis, to learn different methods for dealing with data comming from different places and in different shapes and formats

### Gap in Knowledge:
Does my thesis aim to address a gap or deficiency in existing literature or research? What specific contribution do I hope to make?

### Practical Significance:
Is there practical significance to my research? Will the findings have real-world applications or implications?

### Future Impact:
Consider how my thesis might contribute to future research or understanding in the field. What could be the potential impact of your work?

### Curricular Requirements:
My thesis is part of academic requirements: how does it fit into the overall curriculum and why it's relevant for my academic and professional development.

it is mobility related -> also, gaining experience with a programming language such as python and again, how to deal with data, is completely relevant for an engineer in the autonomous driving area.
Bein able to analyze and draw conclusions depending on trends and working on models that could predict what is going to happen "next"/in the future is of course also something that should be known, at least the basics 


## Trying to answer those questions:
### Urban Mobility Trends:
Munich has been at the forefront of promoting sustainable transportation. Analyzing the time series data allows us to uncover trends in bike usage, providing insights into the evolving patterns of urban mobility.

### Weather Impact on Bike Usage:
The inclusion of meteorological variables such as temperature, precipitation, and sunlight hours enables an exploration of how weather conditions influence bike ridership. This analysis can contribute to our understanding of the interplay between environmental factors and transportation choices.

### Data Preprocessing Challenges:
The dataset spans multiple years, necessitating meticulous data preprocessing to ensure consistency and accuracy. Addressing issues like variations in date formats and column naming conventions highlights the importance of data cleaning in time series analysis.

### Time Series Components Exploration:
Utilizing methodologies like moving averages, exponential smoothing, and decomposition, the research aims to dissect the time series into its fundamental components—trend, seasonality, cyclicity, and irregularities. This exploration is crucial for a nuanced understanding of the factors driving bike count variations.

### Forecasting for Future Urban Planning:
Time series forecasting techniques, including the application of models such as Autoregressive Integrated Moving Average (ARIMA), will be employed to predict future bike counts. This forecasting aspect is instrumental for informed urban planning, allowing for proactive measures to accommodate and encourage sustainable transportation.

### Contributions to Time Series Analysis:
The thesis contributes to the broader field of time series analysis by addressing the challenges specific to bike count data. It establishes a roadmap for handling time series data with a focus on urban mobility trends, providing valuable insights for researchers and practitioners in the field.

### Spatial Considerations:
The initial dataset records bike counts at six distinct locations in Munich, providing a spatial dimension to the analysis. The challenge lies in determining whether to aggregate the data into a unified city-wide perspective or to maintain granularity by analyzing each location separately. This decision necessitates careful consideration of urban dynamics and local variations in bike usage.

### Feature Selection and Aggregation:
To streamline the analysis, the dataset is refined by selecting relevant features and aggregating information. The decision to focus on the total daily bike count for the entire city addresses the challenge of dealing with multiple locations. The aggregation process involves summing the daily counts while retaining crucial meteorological variables like minimum temperature, maximum temperature, precipitation, and others.

### Chronological Integrity:
Acknowledging the fundamental importance of chronological order in time series analysis, the date column is designated as the index of the DataFrame. This strategic choice ensures the preservation of temporal sequencing, a prerequisite for accurate analysis and modeling. The chronological integrity facilitates a closer examination of trends, seasonality, and cyclic patterns that unfold over the years.

### Univariate Time Series Focus:
While the dataset initially presents a multivariate time series, the analysis zeroes in on the "univariate" aspect concerning daily bike counts. This focused approach is crucial for comprehending and predicting the fluctuations in bike usage throughout the year, contributing to a deeper understanding of the temporal dynamics associated with urban mobility.

### Temporal Enhancements:
To enhance the temporal aspect of the dataset, the 'datum' column undergoes conversion to datetime format. This modification lays the groundwork for leveraging time series analysis techniques effectively. Additionally, the inclusion of 'DayOfWeek' and 'DayOfWeek_name' attributes provides insights into weekly patterns and allows for more nuanced temporal analysis.
