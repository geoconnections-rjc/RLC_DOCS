<a href="http://looplinkrlc.com" title="LoopLink RLC- Residential/Light Commercial Geothermal Design Made Simple">![LoopLink RLC Help](img/RLC_help_header.png)</a>

#Pond Loop Design
**Use the previously entered climatic data, peak heating and cooling loads, and GSHP performance data to design a closed-loop surface water heat exchanger, commonly referred to as a Pond Loop.**

This Pond Loop design module assumes that the body of water being used is large enough so that the GSHP system does not alter the natural temperature of the reservoir by more than 1 degree F. According to ASHRAE, the maximum recommended load for a reservoir is 20 tons/acre in cooling mode and 10 tons/acre in heating mode. These rates should not be exceeded unless a detailed analysis is performed.  Refer to Chapter 5 of [Geothermal Heating and Cooling: Design of Ground-Source Heat Pump Systems](http://www.techstreet.com/ashrae/standards/geothermal-heating-and-cooling-design-of-ground-source-heat-pump-systems?gateway_code=ashrae&product_id=1887017) (Kavanaugh and Rafferty, 2014) for more information.

##GHEX Name

**Name:** The name given to the Pond Loop design, saved in the GHEX section within the sidebar navigation panel. Use the name to differentiate between multiple designs for comparison.

##Pond Details
**Describe the body of water in which you will install your loopfield.**<br>
**Is a Flowing Body of Water:** Select this box if the pond loop will be placed in a moving body of water (such as a river or stream). The default setting for this field is false, meaning the pond loop will be placed in a static body of water (such as a lake or pond with no inflow/outflow).  This box modifieds the lower limit allowed for the Pond Temperature Heating input field.<br>
**Pond Condition:** The condition of the water in the reservoir at the loop installation depth. The selection is used to determine the increased heat transfer resistance due to fouling on the outside surface of the pipe.<br>

##Fouling Factors for Pond Loop Coils
<table cellspacing="0" cellpadding="0">
<thead>
  <tr>
  <td width="175" >Condition<br /></td>
  <td width="120" >Fouling Factor<br />
        (Btu/h-ft-F)</td>
  </tr>
</thead>
<tbody>
  <tr>
    <td width="175" class="leftIndent" >Clean Reservoir</td>
    <td width="120" class="centeredData" >500</td>
  </tr>
  <tr class="alternatingCell">
    <td width="175" class="leftIndent" >Muddy Reservoir</td>
    <td width="120" class="centeredData" >300</td>
  </tr>
  <tr>
    <td width="175" class="leftIndent" >Sanitary Sewer Water</td>
    <td width="120" class="centeredData" >125</td>
  </tr>
  <tr class="alternatingCell">
    <td width="175" class="leftIndent" >Untreated Spray Pond</td>
    <td width="120" class="centeredData" >300</td>
  </tr>
  <tr>
    <td width="175" class="leftIndent" >Mud Layer - 1/16 in.</td>
    <td width="120" class="centeredData" >200</td>
  </tr>
  <tr class="alternatingCell">
    <td width="175" class="leftIndent" >Mud Layer - 1/8 in.</td>
    <td width="120" class="centeredData" >100</td>
  </tr>
  <tr>
    <td width="175" class="leftIndent" >Biological Growth - 1/8 in.</td>
    <td width="120" class="centeredData" >40</td>
  </tr>
  </tbody>
</table>
*Source: Kavanaugh and Rafferty (2014)*

**Pond Depth:** The average depth of the water where the loops will be installed. A minimum reservoir depth of 10 ft. is recommended in order to be considered for use with a GSHP system. This depth should be measured at the lowest seasonal level.

**Pond Area:** The area of the reservoir to be used. According to ASHRAE, the maximum recommended load for a reservoir is 20 tons/acre in cooling mode and 10 tons/acre in heating mode.

**A detailed study should be performed to determine the appropriate temperature values to be used for the purposes of Pond Loop design. Geological surveys for most states include lake and stream temperature reports, which serve as the best source for information.  Refer to the [Association of American State Geologists](http://www.stategeologists.org/surveys.php) to find the geological survey for your state.**

**Pond Temperature Heating:** The reservoir temperature at the installation depth of the loop during peak heating conditions.
<ul><li>If the pond loop is placed in a static, frozen body of water (such as a lake or pond with no inflow/outflow), the water temperature at the bottom of the reservoir will be 39.2F (4C), which is the value where water reaches its maximum density. Ice as well as water at any temperature other than 39.2F (4C) will float on top of the water where maximum density has been reached.</li>
<li>In a shallow reservior that is frozen, the thickness of the layer of water at 39.2F (4C) can be very small. Extreme caution should be used when designing a pond loop in a reservoir that is less than 10 ft. deep.</li>
<li>If the pond loop is placed in a moving body of water (such as a river or stream), the water at the bottom can fall below 39.2F (4C) due to mixing effects. In extremely cold locations, water temperatures may fall to just above the freezing point of water, which is 32F (0C).</li></ul>

**Pond Temperature Cooling:** The reservoir temperature at the installation depth of the loop during peak cooling conditions.
<ul><li>The temperature of rivers, streams, and shallow lakes will approach the average air temperature for the location in the summer.</li>
<li>Deeper lakes typically consist of cold water stratified at the bottom throughout summer when sunlight doesn't reach to lower depths.  In such cases, there will be a sharp change in temperature from warm to cold water, which is referred to as the thermocline.</li></ul>

Refer to [GeoKiss: Surface Water Temperatures](http://www.geokiss.com/surwatertemps.htm) for examples of surface water temperatures versus location, depth and time of year.

##Layout Details
**Pond Loop Configuration:** The type of Pond Loop configuration to be installed.  The choices are:

1. Coils with <a href="http://www.geopondclips.com/pond_loop_assembly" target="_blank">Spacers</a>: To limit thermal interference, the minimum c-c spacing between coils is 10 ft. Additionally, spacers should be arranged such that tube spacing is at least one-fourth of the outside coil diameter (Tube Spacing > 0.25 x Nom. Pipe Diameter)
2. Extended Slinky: To limit thermal interference, the minimum c-c spacing between slinky loops is 10 ft. Additionally, slinky coils should be constructed with a 10" pitch (minimum).

**Pipe Material:** The material from which the u-bend is made.  Different materials exhibit different resistance to heat transfer as a result the selection of material will impact loop lengths.

**Pipe Nominal Diameter:** The u-bend nominal diameter to be used in the active section of the GHEX. The available diameters will vary depending on the piping material selected.

For more information about proper Pond Loop pipe selection and layout, refer to Chapter 5 of [Geothermal Heating and Cooling: Design of Ground-Source Heat Pump Systems](http://www.techstreet.com/ashrae/standards/geothermal-heating-and-cooling-design-of-ground-source-heat-pump-systems?gateway_code=ashrae&product_id=1887017) (Kavanaugh and Rafferty, 2014).

**Number of Loops:** The number of loops to be used in the Pond Loop layout. It is generally recommended to use between 0.75 and 1.25 loops per ton of GSHP capacity (one loop per ton with 3/4" HDPE pipe is most common). 

**Minimum Spacing:** The minimum recommended center to center spacing between coils. 

##GHEX Summary
**Number of Loops:** The total number of parallel loops in the Pond Loop.

**GPM per Loop:** The design flow rate (gpm, gallons per minute) through each parallel loop in the Pond Loop. The system should be designed such that the design flow rate is approximately 3 gpm per loop for 3/4" u-bends, 4.5 gpm per loop for 1" u-bends, and 6-9 gpm per loop for 1-1/4" u-bends. 

**System Flow Rate:** The total system flow rate (gpm, gallons per minute) to be circulated through the GHEX, determined by the flow rate required by the GSHP equipment selected to serve the zones in the system.

###Heating
**EWTmin:** The minimum entering water temperature the closed-loop ground connection will be designed to provide under peak heating conditions, typically assumed to be 30 degrees F in heating-dominant applications. This parameter is specified on the **PROJECT DETAILS** page. 

**Heating Rate per Acre:** The rate of heat extraction (tons) divided by the area of the reservoir (acres). This value should be less than 10 tons/acre in heating mode.

**System Rn Fraction:** A measure of equipment run-time during the design month in heating (January), expressed as a decimal. A 0.600 run fraction means that the equipment will run approximately 60% of the time during the design month. Run fraction is a function of equipment capacity as it relates to building load and weather data for the geographical location. 

**Total Loop Length:** The total pipe length required to maintain the minimum entering water temperature given the parameters used to design the Pond Loop in the heating mode. 

**Length per Loop:** The length of pipe to be installed in each loop to maintain the minimum entering water temperature given the parameters used to design the Pond Loop in the heating mode, calculated by dividing the total heating pipe length by the number of loops in the system. 

###Cooling
**EWTmax:** The maximum entering water temperature the closed-loop ground connection will be designed to provide under peak cooling conditions, typically assumed to be 90 degrees F in cooling-dominant applications. This parameter is specified on the **PROJECT DETAILS** page. 

**Cooling Rate per Acre:** The rate of heat rejection (tons) divided by the area of the reservoir (acres). This value should be less than 20 tons/acre in cooling mode.

**System Run Fraction:** A measure of equipment run-time during the design month in cooling (July), expressed as a decimal. A 0.600 run fraction means that the equipment will run approximately 60% of the time during the design month. Run fraction is a function of equipment capacity as it relates to building load and weather data for the geographical location. 

**Total Loop Length:** The total pipe length required to maintain the maximum entering water temperature given the parameters used to design the Pond Loop in the cooling mode. 

**Length per Loop:** The length of pipe to be installed in each loop to maintain the maximum entering water temperature given the parameters used to design the Pond Loop in the cooling mode, calculated by dividing the total cooling pipe length by the number of loops in the system. 

***The Pond Loop design length for a given system will be determined by whichever design is dominant (i.e. - whichever total pipe length is longer).*** 

All design length calculations are performed according to the procedures given in Chapter 5 of [Geothermal Heating and Cooling: Design of Ground-Source Heat Pump Systems](http://www.techstreet.com/ashrae/standards/geothermal-heating-and-cooling-design-of-ground-source-heat-pump-systems?gateway_code=ashrae&product_id=1887017) (Kavanaugh and Rafferty, 2014) 

