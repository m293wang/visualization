Source: https://data.ontario.ca/dataset/ontario-top-baby-names-female

Plot 1: 'Top 20 female baby names in Ontario 2023'

> What software did you use to create your data visualization?
    Python
> Who is your intended audience? 
    Potential parents in Ontario who are interested in the top baby girl names from 2023 (the most recent available datapoint), this could be interested for people looking for inspiration.
> What information or message are you trying to convey with your visualization? 
    The top 20 chosen baby girl names in Ontario for the year 2023, displaying how often each name was chosen, with a visual ranking based on frequency.
> What design principles (substantive, perceptual, aesthetic) did you consider when making your visualization? How did you apply these principles? With what elements of your plots? 
    *Substantive: the graph focused on presenting clear, accurate and relevant data by sorting the popularity of the names in descending order.
    *Perceptual: bar charts are good for comparing quantities, such as the frequency of each name in this case. This makes it clear to see the differences in name popularity.
    *Aesthetic: I used pink as a color because the names are for baby girls! The names on the x axis labels are rotated to make sure they do not overlap and the data callouts are shrank in size for readability.
    
> How did you ensure that your data visualizations are reproducible? If the tool you used to make your data visualization is not reproducible, how will this impact your data visualization? 
    *Pandas and Matplotlib are used for data analysis and plotting. There are no random variables generated so there's no need to set a seed. The dataset is reproducable using the same coding logic.
    *Comments are added to the code to explain certain portions and ensure readability.
    *If the tool used to make the data visualization was not reproducible, this would limit access and flexibility, making it difficult for others to replicate the original work or tweak the visualization in any way for their own purposes.
> How did you ensure that your data visualization is accessible?  
    *Spacing and data callout: even though the colors are the same (all pink), there's sufficient spacing between each bar with data labels to distinguish each data/name from the other.
    *Font: the axis labels, title and data labels are set to readable font size.
> Who are the individuals and communities who might be impacted by your visualization?  
    Expecting parents in Ontario looking for recent popular baby names for inspiration. Researcher/government that want to monitor the trend in data or any cultural patterns.
> How did you choose which features of your chosen dataset to include or exclude from your visualization? 
    I chose the top 20 names from the year 2023 because 2023 is the most recent year in the dataset. There were too many datapoints to display if I were to choose all names to be displayed, so I excluded anything that's not in the top 20 to provide clean and organized chart to avoid overwhelming the viewer with too much information
> What ‘underwater labour’ contributed to your final data visualization product?
    *Hospital staff and other organizers who faciliated in the data collection
    *Record keepers that went back in history to compile the data in this csv format