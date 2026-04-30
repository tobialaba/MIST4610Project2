# MIST4610Project2

## Team name and members:
  1. Tobi Alaba [@tobialaba](https://github.com/tobialaba)
  2. Claire Gracey [@clairegracey28-blip](https://github.com/clairegracey28-blip)
  3. Naysa McFarlane [@ndm53209](https://github.com/ndm53209)
  4. Andy Smith [@Anderson-MIS](https://github.com/Anderson-MIS)

## Describing your dataset and what data it contains:
The Electric Vehicle Population Data was pulled from the data.gov website and represents BEVs (Battery Electric Vehicles) and PHEVs (Plug-In Hybrid Electric Vehicles) that are registered through the Washington State Department of Licensing currently. The dataset has around 280,000 rows with 16 descriptive columns. Columns include a vehicle VIN, county, city, state, postal code, model year, make, model, EV type (BEV or PHEV), Clean Alternative Fuel Vehicle Eligibility, electric range, legislative district, DOL vehicle ID, vehicle location, electric utility, and 2020 census tract. The vehicle VIN is assigned by the manufacturer to distinguish each vehicle. The county, city, state, and postal code are all pieces of information regarding where the vehicle was registered in the state of Washington. The model year, make, and model are all attributes of the car. The EV type can either be a Battery Electric Vehicle which doesn't rely on gasoline at all or a Plug-In Hybrid which means the car combines both battery power and gasoline. The Clean Alternative Fuel Vehicle Eligibility refers to whether or not the vehicle is eligible for tax credits based on criteria set by the IRS. The electric range is how far the car can go on just battery-powered capabilities. The legislative district is the district within Washington where the vehicle is registered. The DOL vehicle ID is the ID that the Washington DOL assigns each vehicle. The vehicle location is the mailing/home address (longitude and latitude) of where the vehicle is registered. The electric utility is the electricity supplier of where the vehicle is registered. Finally, the 2020 census tract is a code assigned by the US Census Bureau to divide areas for research. As an additional note, all research was filtered by state to only Washington to ensure no accidental out-of-state vehicle registrations were included.

## Questions:
  The first question the EV Population Data set answered was: **How the distribution of electric range differs between PHEVs and BEVs?**
  By seeing the distribution of electric ranges between PHEVs and BEVs, we would be able to see the effects on demand for both PHEVs and BEVs, allowing charging station businesses to know whcih types of charging stations to install at higher rates.

  The second question the EV Population Data set answered was: **Which Washington counties have the highest concentration of BEVs?**
  By producing a map of BEV concentration in the state of Washington, charging stations will know which counties require more charging stations and to know where demand will be more consistent to ensure enough business to sustain a company.  

## Dataset Manipulations:
The main manipulation applied to the dataset was filtering the state by Washington. Despite the data stating that all vehicles were registered through the Washington DOL, there is still a possibility for the address information to be outside of the state if people recently moved or these vehicles belong to the military for example. However, using Excel transformation, only vehciles with Washington as their listed state were allowed in the new dataset fixing this issue.  

## Analysis and Results:
Analyze and visualize the results of your analysis and describe the implications of your analysis.
Please provide any citations if required as well as supporting visualizations and analysis
generated from Tableau.

## Tableau Packaged Workbook
Save or Export your project as a Tableau packaged workbook file and provide it as part of the
github repository.
This group project is worth 12.5% of your final grade.
