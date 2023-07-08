# So do you want to go to the beach?
## Project 2

This is my submission for the LEDE Program’s second project – that includes a simple analysis in pandas, a Datawrapper graphic and a Datawrapper map. 

I wanted to explore what was the quality of water in beaches in Puerto Rico for the week of June 23rd, when some neighbors of San Juan, publicly denounced the discharge of dirty water on the beach of El Escambrón. 

Periodically, the Beach Monitoring and Public Notification Program takes samples of water in 35 beaches to look for the number of enterococci bacteria. If the concentration level of enterococci for a beach exceeds the “Beach Action Value” of 70 colonies per 100 milliliters of water (colonies/100mL) authorities will be required to alert the public about the risk.

### Data Collection Process

I downloaded data from the Puerto Rico Department of Natural and Environmental Resources in PDF, converted it to CSV and cleaned using pandas.

The data included the names and id’s of the beaches, its coordinates, the date when the sample was taken and the amount of enterococci found in a sample of 100 mL of water. 

I only used the results from the last two monitoring because I wanted to see what the actual situation was and compare it to the results of the previous monitoring. 

### Data Analysis Process

Here is the CSV file:

•	[Recent Beach Monitoring Results](https://github.com/cristinadelmar/beaches-and-enterococci/blob/main/recent_beach_monitoring.csv)

After collecting the data, I used pandas to clean it and to answer the questions I had about the results, and to identify the beaches who were over the Beach Action Value (a maximum of 70 enterococci colonies per 100 mL of waters).

I saved some of the results in CSV to be able to visualize them in a graph and in a map. 

•	[Change on water quality in two weeks](https://github.com/cristinadelmar/beaches-and-enterococci/blob/main/graph_1.csv)
•	[Map of beaches](https://github.com/cristinadelmar/beaches-and-enterococci/blob/main/map.csv)

The story webpage is here: [So do you want to go to the beach?](https://cristinadelmar.github.io/beaches-and-enterococci/)

### Skills learned:

I’m very new to data visualization, so I acquired more skills working with Datawrapper, customizing the graphs and adding annotations. 

Using pandas, I got to know other commands I hadn’t used before, like working with datetime columns. 

Things I would’ve liked to do:

My focus for this project was to get deeper into data analysis and make better visualizations. Because of the time, and because I knew I needed to get better in the basics to the buildup on that, I decided to finish basic graphs on Datawrapper and then try to work in some ait2html and D3.

