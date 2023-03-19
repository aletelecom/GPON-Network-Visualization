# GPON Network Visualization

This repository contains a collection of visualizations that represent the key performance indicators (KPIs) of GPON (Gigabit Passive Optical Network) and FTTx (Fiber to the x) networks.


## Visualizations


## 1. OLT Heatmap

The OLT Heatmap is a visualization that resembles the front panel of an OLT (Optical Line Terminal) and allows you to represent multiple KPIs simultaneously. The heatmap is color-coded, with each color representing a different KPI. This visualization is useful for quickly identifying areas of the network that may require attention.


![Heatmap](/Visualization-1/Complete-viz-four.png)


# 2. PON Port Occupancy Scatter Plot

The PON Port Occupancy Scatter Plot is a visualization that shows the relationship between the occupation of the PON (Passive Optical Network) port and the number of clients within the same PON port. This visualization can help identify congested areas of the network and can inform capacity planning decisions.


![Scatterplot](/Visualization-2/Vizualization-2-Scatter-plot.png)


# 3. Average Client Speed Bubble Plot

The Average Client Speed Bubble Plot is a visualization that shows the average client speed vs the number of clients per OLT. This visualization uses bubble size to represent the number of clients and bubble color to represent the average client speed. This visualization can help identify areas of the network where clients may be experiencing slow speeds.


![Scatterplot](/Visualization-3/Viz-3.png)


# 4. Optical Receiving Power Histograms and Scatter Plot

The Optical Receiving Power Histograms and Scatter Plot is a compound visualization that helps you see the relationship between the optical receiving power at the ONT (Optical Network Terminal) and the distance to said ONT. This visualization consists of two histograms and a scatter plot, and can help identify areas of the network where clients may be experiencing poor signal quality.


![Scatterplot](/Visualization-4/Viz_4.png)


# 5. Sankey plot for OLT and ODF interconnection


The Sankey plot in this visualization will help you grasp how "messy" is the interconnection between the OLT and the ODF that will connect it to the outside plant FTTx network. On the left side you will have all your OLTs (you can filter by Central Office) and all the ODF that make the aforementioned interconnection.


![Sankey](/Visualization-5/OC-1-Sankey.png)




# Conclusion

These visualizations provide a powerful way to represent KPIs for GPON and FTTx networks. Use them to quickly identify areas of the network that require attention and to inform capacity planning decisions.