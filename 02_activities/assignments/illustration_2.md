Source: https://data.ontario.ca/dataset/ontario-top-baby-names-female

Plot 2: 'Frequency of "Mina" as a baby girl name in Ontario through history'

> What software did you use to create your data visualization?
    Python
> Who is your intended audience? 
    Potential parents or individuals who are interested in the name 'Mina' and its popularity throughout history in Ontario.
> What information or message are you trying to convey with your visualization? 
    The historical frequency of the name 'Mina' for baby girls in Ontario, showing how the frequency changes (increases in this case) throughout the years.
> What design principles (substantive, perceptual, aesthetic) did you consider when making your visualization? How did you apply these principles? With what elements of your plots? 
    *The graph focused on the trend of the name 'Mina' through time, giving audience a clear view of its general trend. 
    *By plotting the data over time using a line plot, the visualization shows the changes in frequency year by year. Markers are used to highlight each data point.
    *Because the graph focuses on change over time, the size was selected to be (10, 3) to make it longer in the x direction.
    *The markers are red to distinguish it from the line, which uses a dashed style to show the trend, but still ensure readability to not overpower the markers.
    
> How did you ensure that your data visualizations are reproducible? If the tool you used to make your data visualization is not reproducible, how will this impact your data visualization? 
    This is done in the same way as plot 1, so the answer is similar:
    *Pandas and Matplotlib are used for data analysis and plotting. There are no random variables generated so there's no need to set a seed. The dataset is reproducable using the same coding logic.
    *Comments are added to the code to explain certain portions and ensure readability.
    *If the tool used to make the data visualization was not reproducible, this would limit access and flexibility, making it difficult for others to replicate the original work or tweak the visualization in any way for their own purposes.
> How did you ensure that your data visualization is accessible?  
    *Color contrast: I used pink trend lines and red markers because I wanted to use the same color theme, but I recognize that this may not be colorblind friendly. To accomodate for this, dashed lines are used and marker size was chosen to make it distinguishable and readable.
    *Font: the axis labels, title and data labels are set to readable font size.
> Who are the individuals and communities who might be impacted by your visualization?  
    Expecting parents in Ontario looking to name their baby Mina who want to see how popular the name is or has been. People who's name is Mina and want to see how popular it was during the year they were born and how it changed throughout time.
> How did you choose which features of your chosen dataset to include or exclude from your visualization? 
    I wanted to show the frequency of the name 'Mina' chosen as baby girl name over the years in Ontario and used the entire range of the dataset (1913 to 2023). I only wanted to focus on the trend in one name so I excluded other names to not overwhelm the viewer.
> What ‘underwater labour’ contributed to your final data visualization product?
    *Hospital staff and other organizers who faciliated in the data collection.
    *Record keepers that went back in history to compile the data in this csv format.