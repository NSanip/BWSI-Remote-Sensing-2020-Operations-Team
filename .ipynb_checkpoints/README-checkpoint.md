This is a readme - Gabe was not here... Yash says Yipee! Edited

# Operations team
## Situational Awareness
### Deep Learning Classifier
Using the LADI dataset (not necessarily MA images), create a tool that can detect multiple types of damage, and multiple types of infrastructure. Possible considerations and enhancements:
- Multi-label classification (ie. 'this image has flooding, rubble' vs 'this image has flooding')
- Performance characterization: ROC or PR curves, Confusion Matrices
- Optimizations for training
- Object localization (you may need to create additional training data + different network architecture for this)

### CAP Image Localization tool
Enhance the CAP image localization tool to improve the localization performance. Potential enhancements:
- Using DEM to adjust for elevation and non-levelness of terrain
- Automatically incorporating other data sources, such as satellite, for additional context
- Using the CAP image footprint and OSM, get the roads, buildings, airports, etc which appear inside the CAP image

### Deploy/Implement xView2
Run one of the xView2 solutions from https://github.com/DIUx-xView
Evaluate the performance, generate a report with demonstrations. If you'd like, you can attempt to to improve or modify their solutions (outside of the scope of the class).