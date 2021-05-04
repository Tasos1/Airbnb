# Project Overview
This is an exploratory project to analyze publicly available London Airbnb data. In particular the analysis focuses on:
<ol>
<li>Identifying the most expensive Airbnb areas in London </li>
<li>Identifying price discrepancies within areas</li>
<li>Identifying amenities that are associated with high and low priced listings</li>
<li>Building a linear model to predict the advertised price</li>
</ol>

# Installation
The requirements are the libraries in the Anaconda distribution of python (versions 3.*) plus the following libraries:
<ul>
<li>plotly (4.5.0)</li>
<li>plotly-express (0.4.1)</li>
<li>seaborn (0.11.1)</li>
<li>scikit-learn (0.19.1)</li>
</ul>

And in cases of compatibility issues, the below versions are used:
<ul>
<li>numpy (1.14.2)</li>
<li>pandas (0.22.0)</li>
<li>matplotlib (2.0.2)</li>
<li>jupyter (1.0.0)
</ul>

# The files
<ol>
<li>London Airbnb.ipynb: The notebook containing the analysis </li>
<li>listings.csv: The data (London August 2020 listings data from http://insideairbnb.com/ )</li>
<li>london_boroughs.json: A geojson file used to plot geographical data in London</li>
<li>southwark_map.PNG: A map of Southwark, on which Airbnb listings were superimposed</li>
</ol>


# Running the code
The code is stored in the "London Airbnb.ipynb"  Jupyter notebook.

 It's possible that the choropleth visualisation gives an 'IOPUB data rate exceeded' error and doesn't display the chart. If so then:

<ol>
<li>Exit the notebook and shut down the kernel</li>
<li>Open a command prompt in the same directory as the London Airbnb notebook</li>
<li>Run: "jupyter notebook --NotebookApp.iopub_data_rate_limit=1.0e10"  </li>
<li>Then open the notebook from the started kernel </li>
</ol>

# Results 
The main findings of the code can be found at the post available [here](https://medium.com/@Tasos1/airbnb-london-what-defines-the-price-ab283b0515ae)






