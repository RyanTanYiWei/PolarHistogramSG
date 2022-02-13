# Generating Polar Histograms for each DGP in Singapore

![Visuals](https://github.com/RyanTanYiWei/PolarHistogramSG/blob/main/OutputVisuals/byEntropy5x11_sample.jpeg)

<b>Description</b>

Street Networks support a wide range of urban processes and often describe the environmental, economic, demographic and social dimensions of urban livelihood. This analysis looks into the geometric orientation of Singapore's street networks - examining the spatial logic and order of the different configurations of our 55 planning areas (URA Master Plan 19).

The following method of street network analysis is inspired by Geoff Boeing, where he conceptualized the use of a polar histogram to compare orientations of streets in cities around the world. The polar histogram charts out the frequencies of streets at different angles. For instance, a cross (+) appearance would imply a grid-like street network structure. The analysis accounts for a multi-modal street network and the number of line segments is shown on the number to the right of each planning area's name.

Human behaviour is heavily influenced by the shape and the configuration of our environment. Viewing our streets through a quantitative lens enables us to understand as well as compare the underlying spatial structures of our community spaces that determine our movement patterns and experiences. Personally, I am interested in studying if the spatial configuration of our planning areas can provide insights into the vibrancy of the neighbourhood. Beyond this, the data visualization also intends to capture the aesthetics of our local streets in a rather unorthodox form and allows us to appreciate the unique identities and historical influences of our neighbourhood environment.

<b>Stages</b>
1) Read Street Network (snet has line segment data with labelled boundaries - DGP + Electorial)
2) Divide Street Network by Boundaries (DGP)
3) Compile Data and Process Angles for each Zone's Network 
4) Binning and Calculation of Basic Network Entropy Measures
5) Compute All Plots
6) Generating TIFFs (sorted by Zone/ Entropy)
  
  *note North-Eastern Islands is excluded due to lack of data outside of the main island.
