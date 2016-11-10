# PBISentimentAnalysis
Simple demo of Sentiment Analysis using Azure, Power BI and Cortana Analytics.

Thanks to Gil from DataChant. His example and samples from the PBI Community are extremely helpful and got me started on incorporating Sentiment Analysis from Azure Cognitive Services into Power BI: http://community.powerbi.com/t5/Community-Blog/Sentiment-Analysis-in-Power-BI/ba-p/55898. His full working sample is awesome and it is here: https://app.powerbi.com/view?r=eyJrIjoiMjU5NWM3MTMtMTg0NS00YzE2LTk0YTYtMmZkZWM4NjYwMmFjIiwidCI6IjIyNzNjNDFiLWI4ZDAtNDVhZi1iZWU2LWUwODQ5NmFlNjcxOCIsImMiOjN9.

To use this sample, just download the PBIX and open it with Power BI Desktop. I recommend going into the detailed PBI Community like from Gil above, it rocks and gives you the background you need to customize this for yourself.

For this demo, I included Gil's Trump & Clinton Facebook sentiment analysis data on Tab 2 of the report view on PBI. Tab 1 has Microsoft BI Facebook sentiment data. Each of those datasets is run through the Cognitive Services API for Sentiment Analysis, part of the Text Analytics suite.

To make it work for you, follow Gil's instructions on getting an API key from Cognitive Services and plug in your API Key in the GetSentimentResults function in the Power Query / Edit query tool.
