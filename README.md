# Airport Data vizualization
Airport Traffic data visualisation

Aim of the visualisation
A static, overview dashbord empowered with interactive html widgets for highlighting the details. By adding Shiny to a flexdashboard, you can create dashboards that enable viewers to change underlying parameters and see the results immediately, or that update themselves incrementally as their underlying data changes.

Data
Yearly, monthly based traffic data of the Budapest Airport for 2013-2017. 

    Year, Month: period of time
    Country, City: destination
    ATM (AIR Traffic Movement): Nr of movements(landing and taking off)
    PAX: Nr of passengers
    Capacity: available seats
    
Especially, the following highlights can be noted on the dashboard:
1. Top destinations by the number of passangers
2. Top destinations trend on yearly basis
3. %changes of passengers for top destinations (pl. 2016-hez)
4. Nr of passengers on monthly basis
5. Nr of passangers and capacity timeline 
6. Calculated features: ‘utilization’ - how many 'Capacity' was actually used (in %), ‘seats’ - average nr of passengers on an aircraft

Data visualisation
For effective visualisation plots, tables és htmlwidgets, especially leaflets were used. Interactivity is realised through Shiny enabled widgets, reactive functions and crosstalk technology. 
For plots the Economist style have been applied.

Applied tools
main softver: R, R markdown
IDE: RStudio
dashbord: flexdashbord
interactivity: plotly, shiny, crosstalk
interactive timeseries: dygraphs
plots: ggplot2
data analysis: dplyr, tidyr, reshape2
sstyle: Economist folyóirat által használt: Economisttheme

Link to the deployed app
https://szintakacseva.shinyapps.io/index/
