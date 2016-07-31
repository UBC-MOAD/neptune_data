The IPython Notebooks in this directory are made by Ben for
quick sharing of results.

The links below are to static renderings of the notebooks via
[nbviewer.ipython.org](http://nbviewer.ipython.org/).
Descriptions below the links are from the first cell of the notebooks
(if that cell contains Markdown or raw text).

* ##[NEPTUNE_adcp_subsample_and_filter.ipynb](http://nbviewer.ipython.org/urls/bitbucket.org/salishsea/NEPTUNE_data/raw/tip/notebooks/NEPTUNE_adcp_subsample_and_filter.ipynb)  
    
    **Try out pandas subsampling and Ben's Doodson filter**  
      
    Doodson filter requires hourly data for best results but NEPTUNE's POD2 75KHz ADCP has data points every 2 seconds. So I will subsample (using a mean) to hourly output and then use Ben's doodslon filter from Salish Sea tools / tidetools.  
      
    **NEPTUNE - ADCP metadata**  
      
    **Data points every 2 SECONDS **  
      
    platform_depth = 395. ;  
    site_name = "UpperSlope_IP_2012-06" ;  
    device_name = "RDI Workhorse Long Ranger ADCP 75 kHz (9202)" ;  
    		  
    **dimensions**:  
    	time = 33654 ;  
    	depth = 50 ;  
    	latitude = 1 ;  
    	longitude = 1 ;  
      
    **variables**:  
    	  
    	double time(time) ;  
    		time:standard_name = "time" ;  
    		time:long_name = "time" ;  
    		time:units = "days since 19700101T000000Z" ;  
    		time:axis = "T" ;  
    		time:calendar = "gregorian" ;  
    	float depth(depth) ;  
    		depth:standard_name = "depth" ;  
    		depth:long_name = "approx. water depth of measurement bin" ;  
    		depth:units = "meters" ;  
    		depth:axis = "Z" ;  
    		depth:positive = "down" ;  
    	float latitude(latitude) ;  
    		latitude:standard_name = "latitude" ;  
    		latitude:long_name = "latitude" ;  
    		latitude:units = "degrees_north" ;  
    		latitude:axis = "Y" ;  
    	float longitude(longitude) ;  
    		longitude:standard_name = "longitude" ;  
    		longitude:long_name = "longitude" ;  
    		longitude:units = "degrees_east" ;  
    		longitude:axis = "X" ;  
    	float u(time, depth) ;  
    		u:standard_name = "eastward_sea_water_velocity" ;  
    		u:long_name = "eastward sea water velocity" ;  
    		u:units = "meters/second" ;  
    		u:_FillValue = -9999999.f ;  
    	float v(time, depth) ;  
    		v:standard_name = "northward_sea_water_velocity" ;  
    		v:long_name = "northward sea water velocity" ;  
    		v:units = "meters/second" ;  
    		v:_FillValue = -9999999.f ;  
    	float w(time, depth) ;  
    		w:standard_name = "upward_sea_water_velocity" ;  
    		w:long_name = "upward sea water velocity" ;  
    		w:units = "meters/second" ;  
    		w:_FillValue = -9999999.f ;  
    	float temp(time) ;  
    		temp:standard_name = "sea_water_temperature" ;  
    		temp:long_name = "sea water temperature" ;  
    		temp:units = "K" ;  
    		temp:_FillValue = -9999999.f ;  


* ##[NEPTUNE_POD2_75kHz_adcp_look_at_data.ipynb](http://nbviewer.ipython.org/urls/bitbucket.org/salishsea/NEPTUNE_data/raw/tip/notebooks/NEPTUNE_POD2_75kHz_adcp_look_at_data.ipynb)  
    
    NEPTUNE - Barkley Upper Slope ADCP  
    ================================  
      
    **Data points every 2 SECONDS **  
      
    platform_depth = 395. ;  
    site_name = "UpperSlope_IP_2012-06" ;  
    device_name = "RDI Workhorse Long Ranger ADCP 75 kHz (9202)" ;  
    		  
    **dimensions**:  
    	time = 33654 ;  
    	depth = 50 ;  
    	latitude = 1 ;  
    	longitude = 1 ;  
      
    **variables**:  
    	  
    	double time(time) ;  
    		time:standard_name = "time" ;  
    		time:long_name = "time" ;  
    		time:units = "days since 19700101T000000Z" ;  
    		time:axis = "T" ;  
    		time:calendar = "gregorian" ;  
    	float depth(depth) ;  
    		depth:standard_name = "depth" ;  
    		depth:long_name = "approx. water depth of measurement bin" ;  
    		depth:units = "meters" ;  
    		depth:axis = "Z" ;  
    		depth:positive = "down" ;  
    	float latitude(latitude) ;  
    		latitude:standard_name = "latitude" ;  
    		latitude:long_name = "latitude" ;  
    		latitude:units = "degrees_north" ;  
    		latitude:axis = "Y" ;  
    	float longitude(longitude) ;  
    		longitude:standard_name = "longitude" ;  
    		longitude:long_name = "longitude" ;  
    		longitude:units = "degrees_east" ;  
    		longitude:axis = "X" ;  
    	float u(time, depth) ;  
    		u:standard_name = "eastward_sea_water_velocity" ;  
    		u:long_name = "eastward sea water velocity" ;  
    		u:units = "meters/second" ;  
    		u:_FillValue = -9999999.f ;  
    	float v(time, depth) ;  
    		v:standard_name = "northward_sea_water_velocity" ;  
    		v:long_name = "northward sea water velocity" ;  
    		v:units = "meters/second" ;  
    		v:_FillValue = -9999999.f ;  
    	float w(time, depth) ;  
    		w:standard_name = "upward_sea_water_velocity" ;  
    		w:long_name = "upward sea water velocity" ;  
    		w:units = "meters/second" ;  
    		w:_FillValue = -9999999.f ;  
    	float temp(time) ;  
    		temp:standard_name = "sea_water_temperature" ;  
    		temp:long_name = "sea water temperature" ;  
    		temp:units = "K" ;  
    		temp:_FillValue = -9999999.f ;  



##License

These notebooks and files are copyright 2013-2016
by the Salish Sea MEOPAR Project Contributors
and The University of British Columbia.

They are licensed under the Apache License, Version 2.0.
http://www.apache.org/licenses/LICENSE-2.0
Please see the LICENSE file for details of the license.
