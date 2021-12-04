# Temperature Sensor QAQC Report

This repository contains an RMarkdown report to be used for QAQC on stream temperature data and a separate script to generate multiple reports at once.  The report is a simple set of plotly graphs showing:
- One graph per station showing all 3 sensors data at the respective station (e.g. air, surface water and subsuface)
- One graph per sensor type showing all sensors of the same type (e.g. surface water) within the basin.
- Raster representation of surface water. 

Sample input data is provided in the data_input folder and a "key" to tie specific sensors to specific sites is in the metadata folder.  The report can be generated manually per basin or through the iterator script.  
