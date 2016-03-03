#Horizontal Trench GHEX Design
**Use the previously entered climatic data, peak heating and cooling loads, and GSHP performance data to design a horizontally-trenched ground heat exchanger (GHEX).** 

**Name:** The name given to the horizontally-trenched GHEX design, saved in the GHEX section within the sidebar navigation panel. Use the name to differentiate between multiple designs for comparison. 

##Earth Temperature Data Location

**Country/State/City:** Select the location nearest to the actual project location. Soil temperature data is imported and used to design the horizontally-trenched GHEX.

##Soil Details
**Soil TC (Thermal Conductivity):** The thermal conductivity (Btu/hr-ft-F) of the soil. Soil TC is dependent on soil type, moisture content, and density. Thermal conductivity is a measure of how fast heat moves through a material due to a temperature difference. 

**Soil Diffusivity:** The thermal diffusivity (ft2/day) of the soil. Soil diffusivity is dependent on soil type, moisture content, and density. Thermal diffusivity is a measure of how fast heat moves relative to the heat storage capacity of the material. 

**Calculate Estimate:** Click this button to open an interactive calculator that will enable you to estimate your formation thermal properties based on a weighted average of soil properites from a drill log.

**View Reference Table:** Click this button to open a reference table of thermal properties for a various soils.

For more information on soil properties, refer to Section 5.3.2.2 and Table 5.15 (Chapter 5, pages 59-62) in IGSHPA's *Ground Source Heat Pump Residential and Light Commercial Design and Installation Guide.* 

Users in the U.S.A. may reference the [USDA Printed Surveys](http://soils.usda.gov/survey/printed_surveys) for detailed soil information by state and county.

##Piping Details
**GHEX Configuration:** The type of horizontally-trenched GHEX configuration to be installed. 

**Pipe Configuration:** When a selection is made, the corresponding trench detail and loop configuration diagram is displayed. 

**Trench/Track Width:** The width of the selected piping configuration. When multiple values are possible, a dropdown will appear. 

**Trench/Pit Depth:** The depth of the trench/pit to be excavated. 

**C-C Spacing/Pit Width:** The center to center spacing between trenches for Standard and Slinky configurations or the overall pit width for Racetrack configurations. 

**Pipe Diameter:** The pipe diameter to be used in the active section of the horizontally-trenched GHEX. Choose between 3/4", 1", and 1-1/4" horizontal loop pipe diameters. 

**Flow Paths per Trench:** The number of parallel flow paths per trench. When multiple values are possible, a dropdown will appear. 

**Number of Flow Paths:** The total number of parallel flow paths in the GHEX. This must be an even multiple of **Flow Paths per Trench**. 

**Horizontal Spacing:** The spacing between individual pipe runs in the trench, calculated based on trench/track width for the selected Pipe Configuration. This field will only appear when applicable.

##Fixed Length Mode
Check this box to use **Fixed Length Mode**. When enabled, specify the target trench/pit length and configuration (number of flow paths, C-C spacing/pit width, trench/pit depth, etc. and the program will calculate the minimum and maximum EWT's that will be supplied by the specified ground heat exchanger configuration. 

**Fixed Length Mode** is only available for one GHEX configuration per project. All other GHEX design calculations will be performed such that they will provide the same EWT's as the configuration with **Fixed Length Mode** Enabled.

##GHEX Summary
**Number of Trenches:** The total number of trenches required to build the GHEX, calculated by taking the number of flow paths divided by the number of flow paths per trench. 

**Average Burial Depth:** The average pipe burial depth of the horizontally-trenched GHEX. If the pipe is laid flat in the bottom of the trench (laying configuration), the average pipe burial depth will be equal to the trench depth. If the pipe is standing in the trench (standing configuration), the average pipe burial depth will be at the center of the standing configuration. 

***Refer to the following figure to view the correlation between pipe configuration and average pipe burial depth:*** 
![Avg Pipe Depth](img/avg_pipe_depth_horizontal_trench.gif)

**Soil Resistance:** The heat transfer resistance (hr-ft-F/Btu) in the horizontally-trenched GHEX. Soil resistance is a function of loop pipe diameter, spacing and configuration of the pipes in the trench, the center-center spacing between trenches, the number of trenches to be installed, and soil thermal conductivity. 

For more information on soil resistance, refer to Tables 5.17-5.29 (Chapter 5, pages 64-69) in IGSHPA's *Ground Source Heat Pump Residential and Light Commercial Design and Installation Guide.* 

**GPM per Flow Path:** The design flow rate (gpm, gallons per minute) through each parallel flow path in the GHEX. The system should be designed such that the design flow rate is approximately 3 gpm per flow path for 3/4" horizontal loops, 4.5 gpm per flow path for 1" horizontal loops, and 6-9 gpm per flow path for 1-1/4" horizontal loops. 

**Number of Flow Paths:** The total number of parallel flow paths in the GHEX. 

**System Flow Rate:** The total system flow rate (gpm, gallons per minute) to be circulated through the GHEX, determined by the flow rate required by the GSHP equipment selected to serve the zones in the system.

###Heating
**EWTmin:** The minimum entering water temperature the closed-loop ground connection will be designed to provide under peak heating conditions, typically assumed to be 30 degrees F in heating-dominant applications. This parameter is specified on the **PROJECT DETAILS** page. 

**Soil Temp:** The temperature of the soil at the average pipe burial depth during peak heating conditions (at the end of January). Soil temperature is a function of average pipe burial depth, soil type, and time of year when the installation depth is less than 15 feet below grade. 

***Refer to the figure below to see how soil temperature in Chicago, IL varies with depth and time of year for a given soil type:*** 
![Chicago Soil Temp](img/chicago_il_air_soil_temps.gif) 

For more information on soil temperature swing through the year, refer to Section 5.3.2.1, Table 5.11 and Figures 5.21-5.23 (Chapter 5, pages 52-59) in IGSHPA's *Ground Source Heat Pump Residential and Light Commercial Design and Installation Guide.* 

**System Run Fraction:** A measure of equipment run-time during the design month in heating (January), expressed as a decimal. A 0.600 run fraction means that the equipment will run approximately 60% of the time during the design month. Run fraction is a function of equipment capacity as it relates to building load and weather data for the geographical location. 

**Total Pipe Length:** The total pipe length required to maintain the minimum entering water temperature given the parameters used to design the GHEX in the heating mode. 

**Pipe Length per Trench:** The length of pipe to be installed in each trench to maintain the minimum entering water temperature given the parameters used to design the GHEX in the heating mode, calculated by dividing the total heating pipe length by the number of trenches in the system. 

**Individual Trench Length:** The length of each trench necessary to install the amount of pipe required by the design, calculated by dividing the heating pipe length per trench by the pipe density of the selected configuration (feet of pipe per foot of trench).

###Cooling
**EWTmax:** The maximum entering water temperature the closed-loop ground connection will be designed to provide under peak cooling conditions, typically assumed to be 90 degrees F in cooling-dominant applications. This parameter is specified on the **PROJECT DETAILS** page. 

**Soil Temp:** The temperature of the soil at the average pipe burial depth during peak cooling conditions (at the end of July). Soil temperature is a function of average pipe burial depth, soil type, and time of year when the installation depth is less than 15 feet below grade. 

**System Run Fraction:** A measure of equipment run-time during the design month in cooling (July), expressed as a decimal. A 0.600 run fraction means that the equipment will run approximately 60% of the time during the design month. Run fraction is a function of equipment capacity as it relates to building load and weather data for the geographical location. 

**Total Pipe Length:** The total pipe length required to maintain the maximum entering water temperature given the parameters used to design the GHEX in the cooling mode. 

**Pipe Length per Trench:** The length of pipe to be installed in each trench to maintain the maximum entering water temperature given the parameters used to design the GHEX in the cooling mode, calculated by dividing the total cooling pipe length by the number of trenches in the system. 

**Individual Trench Length:** The length of each trench necessary to install the amount of pipe required by the design, calculated by dividing the cooling pipe length per trench by the pipe density of the selected configuration (feet of pipe per foot of trench). 

***The GHEX design length for a given system will be determined by whichever design is dominant (i.e. - whichever GHEX design length is longer).*** 

All design length calculations are performed according to the procedures given in Section 5.3 (Chapter 5, pages 49-79) in IGSHPA's *Ground Source Heat Pump Residential and Light Commercial Design and Installation Guide.*