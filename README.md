# testplugin_pi
Plugin to test JSON and ODAPI

The idea is really to debug the process to see what happens. 
The testplugin should 'do' what a plugin would do to create stuff, 
i.e. it is a working example, 
and it allows me to test the API without having to drive another plugin.

Only ODAPI is working at the moment. JSON is being developed now.

1. With the ODAPI select the type of object you want to create, 
2. click on the chart to pick the click location for its creation or provide the lat/lon, 
3. then click create. 
4. The object 'should' be created. T

NOTE the Boundary works, but may initially crash opencpn, until the initialization has taken.
Try selecting the number of boundary points first.
