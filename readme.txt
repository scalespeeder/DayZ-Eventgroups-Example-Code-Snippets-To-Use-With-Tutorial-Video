<!--Event Group Examples Notepad-->
	
		<!--events entry-->
	
	   <event name="StaticShipWreck">
        <nominal>1</nominal>
        <min>0</min>
        <max>0</max>
        <lifetime>1800</lifetime>
        <restock>0</restock>
        <saferadius>1000</saferadius>
        <distanceradius>1000</distanceradius>
        <cleanupradius>1000</cleanupradius>
        <secondary>InfectedIndustrial</secondary>
        <flags deletable="1" init_random="0" remove_damaged="0"/>
        <position>fixed</position>
        <limit>child</limit>
        <active>1</active>
        <children/>
		</event>
	
	<!--END OF events entry-->
	
	<!--cfgeventspawn entry-->
	
		<event name="StaticShipWreck">
		<zone smin="0" smax="0" dmin="1" dmax="2" r="20" />
    	<pos x="856.249" z="1737.43" a="0" y="1.02763" group="ShipWreck_Tikhi"/>
    	<pos x="856.249" z="1737.43" a="0" y="1.02763" group="ShipWreck_Tulga"/>
		<pos x="15203.9" z="13586.9" a="0" y="2.06908" group="ShipWreck_Brerezhki"/>
    	
		</event>
	
	<!--END OF cfgeventspawn entry-->
	
	
	<!--cfgeventgroup entry-->
	
		<!--<pos x="856.249" z="1737.43" a="0" y="1.02763" group="ShipWreck_Tikhi"/>-->
		<group name="ShipWreck_Tikhi">
		<child type="StaticObj_Wreck_Ship_Big_Lifeboat" deloot="0" lootmax="3" lootmin="2" x="0" z="0" y="0" a="0"/>
		<child type="StaticObj_Wreck_Ship_Big_Lifeboat" deloot="0" lootmax="3" lootmin="2" x="-7.77704" z="-5.32007" y="-0.081225" a="70.4661"/>
		<child type="StaticObj_Wreck_Ship_Big_Lifeboat" deloot="0" lootmax="3" lootmin="2" x="-17.354" z="-10.4501" y="-0.502424" a="0"/>
		<child type="StaticObj_Wreck_Ship_Big_FrontA" deloot="0" lootmax="10" lootmin="5" x="174.291" z="-297.93" y="3.97342" a="311.4"/>
		</group>
		
		<!--<pos x="13554.4" z="5093.33" a="0" y="-0.179798" group="ShipWreck_Tulga"/>-->
	<group name="ShipWreck_Tulga">
		<child type="StaticObj_Wreck_Ship_Big_Lifeboat" deloot="0" lootmax="3" lootmin="1" x="0" z="0" y="0" a="186.005"/>
		<child type="StaticObj_Wreck_Ship_Big_Lifeboat" deloot="0" lootmax="3" lootmin="1" x="-12.9004" z="-2.29004" y="1.39575" a="352.904"/>
		<child type="StaticObj_Wreck_Ship_Big_Lifeboat" deloot="0" lootmax="3" lootmin="1" x="-10.2002" z="-9.99023" y="1.19179" a="139.512"/>
		<child type="StaticObj_Big_Castle" deloot="0" lootmax="3" lootmin="1" x="295" z="50.3398" y="3.95744" a="77.2024"/>
	</group>
	
	
		
			<!--<pos x="15203.9" z="13586.9" a="0" y="2.06908" group="ShipWreck_Brerezhki"/>-->
	<group name="ShipWreck_Brerezhki">
		<child type="Land_Mil_Tent_Big1_1" deloot="0" lootmax="3" lootmin="1" x="0" z="0" y="0" a="220.41"/>
		<child type="StaticObj_Wreck_Ship_Big_Lifeboat" deloot="0" lootmax="3" lootmin="1" x="13.0996" z="16.5" y="0.91512" a="197.64"/>
		<child type="StaticObj_Wreck_Ship_Big_Lifeboat" deloot="0" lootmax="3" lootmin="1" x="8.7998" z="23.0996" y="0.59399" a="142.83"/>
		<child type="StaticObj_Wreck_Ship_Big_Lifeboat" deloot="0" lootmax="3" lootmin="1" x="4.2998" z="15.1992" y="0.78399" a="218.699"/>
	</group>
	
	<!--END OF cfgeventgroup entry-->
	

	<!-- MAPGROUPPROTO ENTRY-->
		
		<group name="StaticObj_Wreck_Ship_Big_Lifeboat" lootmax="6">
				<container name="lootFloor">
						<category name="tools" />
						<category name="containers" />
						<category name="clothes" />
						<category name="food" />
						<category name="weapons" />
						<tag name="floor" />
						<tag name="shelves" />
						<point pos="-0.793789 -0.916977 0.463328" range="0.445801" height="0.541259" flags="32" />
						<point pos="-0.021646 -0.247688 1.410591" range="0.256104" height="0.640260" />
						<point pos="-0.704363 -0.620522 -1.257256" range="0.346191" height="0.197007" flags="32" />
						<point pos="0.291881 -0.349426 0.060435" range="0.289795" height="0.724121" />
						<point pos="0.888018 -0.400253 0.585617" range="0.274902" height="0.687256" flags="32" />
						<point pos="0.317482 -0.150864 0.568186" range="0.100000" height="0.250000" />
						<point pos="-0.449876 0.130165 0.540850" range="0.100000" height="0.250000" />
						<point pos="0.467333 -0.202347 -0.579927" range="0.100000" height="0.250000" />
						<point pos="0.949122 -0.400253 -1.039286" range="0.307129" height="0.767822" flags="32" />
						<point pos="-0.930526 -0.400253 -0.637608" range="0.349245" height="0.313591" flags="32" />
				</container>
		</group>
		
	
		<group name="StaticObj_Wreck_Ship_Big_FrontA" lootmax="8">
				<usage name="Military" />
				<container name="lootFloor" lootmax="8">
						<category name="containers" />
						<category name="clothes" />
						<category name="food" />
						<category name="weapons" />
						<category name="explosives" />
						<tag name="floor" />
						<tag name="shelves" />
		<point pos="3.641194 -3.089303 -9.305564" range="1" height="1" /> 
		<point pos="4.516093 -3.155503 -6.416615" range="1" height="1" /> 
		<point pos="-2.727647 -1.952442 -13.780646" range="1" height="1" /> 
		<point pos="-0.056051 -1.937647 -18.580786" range="1" height="1" /> 
		<point pos="-2.741714 -2.793435 -21.053299" range="1" height="1" /> 
		<point pos="-0.949713 -2.616685 -29.623449" range="1" height="1" /> 
		<point pos="-4.671024 -2.568659 -31.551800" range="1" height="1" /> 
		<point pos="-3.174208 -0.185478 -4.287016" range="1" height="1" /> 
		<point pos="-1.528969 -5.634512 -3.026155" range="1" height="1" /> 
		<point pos="4.577390 -5.616018 -8.476450" range="1" height="1" /> 
		<point pos="-2.941901 -5.604004 -19.813147" range="1" height="1" /> 
		<point pos="-9.188093 -5.619301 -12.766195" range="1" height="1" /> 
		<point pos="-6.459465 -5.619739 -22.931187" range="1" height="1" /> 
		<point pos="-1.486695 -5.596580 -21.485157" range="1" height="1" /> 
		<point pos="-11.186644 -5.624625 1.155367" range="1" height="1" /> 
				</container>
		</group>
		
		<group name="StaticObj_Wreck_Ship_Big_Castle" lootmax="8">
	<usage name="Military" />
	<container name="lootFloor" lootmax="8">
		<point pos="4.608090 -0.713224 -2.124152" range="1" height="1" /> 
		<point pos="6.037775 -0.712969 0.915404" range="1" height="1" /> 
		<point pos="3.449404 -0.712914 1.511781" range="1" height="1" /> 
		<point pos="-0.753943 -0.713217 -2.203725" range="1" height="1" /> 
		<point pos="-5.413679 -0.713055 -0.046404" range="1" height="1" /> 
		<point pos="8.892473 -3.406798 -0.614049" range="1" height="1" /> 
		<point pos="9.585731 -3.406800 2.617952" range="1" height="1" /> 
		<point pos="4.468747 -3.406801 5.439377" range="1" height="1" /> 
		<point pos="9.725948 -3.406798 6.905118" range="1" height="1" /> 
		<point pos="-4.221551 -3.406799 4.760492" range="1" height="1" /> 
		<point pos="-10.062245 -3.406799 -0.417997" range="1" height="1" /> 
		<point pos="-5.899074 -2.422422 7.111179" range="1" height="1" /> 
		<point pos="-3.825054 -3.406799 -0.023243" range="1" height="1" /> 
		<point pos="-2.005827 -3.406827 -1.265260" range="1" height="1" /> 
		<point pos="0.500489 -3.406895 -1.890034" range="1" height="1" /> 
		<point pos="5.845097 -3.406800 1.698657" range="1" height="1" /> 
		<point pos="5.151532 -3.406805 -2.098748" range="1" height="1" /> 
	</container>
</group>
		
		<!-- END OF MAPGROUPPROTO ENTRY-->
		
		
		<!--types entry-->
		
		<type name="StaticObj_Wreck_Ship_Big_FrontA">
        <nominal>0</nominal>
        <lifetime>0</lifetime>
        <restock>0</restock>
        <min>0</min>
        <quantmin>-1</quantmin>
        <quantmax>-1</quantmax>
        <cost>100</cost>
        <flags count_in_cargo="0" count_in_hoarder="0" count_in_map="0" count_in_player="0" crafted="0" deloot="0"/>
    </type>
	
		<type name="StaticObj_Wreck_Ship_Big_Lifeboat">
        <nominal>0</nominal>
        <lifetime>0</lifetime>
        <restock>0</restock>
        <min>0</min>
        <quantmin>-1</quantmin>
        <quantmax>-1</quantmax>
        <cost>100</cost>
        <flags count_in_cargo="0" count_in_hoarder="0" count_in_map="0" count_in_player="0" crafted="0" deloot="0"/>
    </type>
	
	
	<type name="StaticObj_Wreck_Ship_Big_Castle">
        <nominal>0</nominal>
        <lifetime>0</lifetime>
        <restock>0</restock>
        <min>0</min>
        <quantmin>-1</quantmin>
        <quantmax>-1</quantmax>
        <cost>100</cost>
        <flags count_in_cargo="0" count_in_hoarder="0" count_in_map="0" count_in_player="0" crafted="0" deloot="0"/>
    </type>
	
	<!--END OF types entry-->
	
	
	<!-- NOTESSSSS -->
	
	