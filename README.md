Suriel Aido teruel.

File economic_analysis.py: 
-
  Contains the class economic_analysis that has the neccesary methods to do an economic analysis based in the study case presented.
  
Methods:
- 

- boiler: return the boiler cost. Have two input params. The first input param receive the vapor production and it value have to be between 5000 and 800000. The second input param receive as value the pressure of the boiler and it value have to be between 10 and 70. If these values are not in their ranges, the system will print a Warning, indicating that the results may not be accurate.
- pump: return the centrifuge pump cost for a caudal between 0.2 and 126 L/s. As input param receive the water caudal.
- steam_turbine: return steam turbine cost for a power between 100 and 20000kW. As input param receive the power of the turbine.
- loan: return annual payment of a loan. As input params receive the investment which will be funded and the annual interest and the number of years to return the loan.
- depreciation: return the annual depreciation of investment. As input params receive the annual percent of depreciation, the capital expenditure, the plant value at the end of its life.
- william_correlation: return the william_correlation. As input params receive (for this particular case), the valor of production of the boiler, the pressure of the boiler, the power of the turbine and the caudal of the pump.
- boiler_correlation: return the correlation used in the boiler method. As input params recieive the valor of the production of the boiler and its pressure.
- turbine_correlation: return the correlation used in the steam_turbine method. As input param has the power of the turbine.
- pump_correlation: return the correlation used in the pump method. As input param has the caudal of the pumb.
- payback: return the economic payback of an investment. As input param has a cash flow.
- execute: execute the economic analysis for this study case.
  - At the end of the execute method we can find some important modifications: In the firts place, from the line 252 to line 264 we can find the tranformation of npv in a Data Frame an  its representation. In the second place, from the line 270 to line 279 we can see the graphic representation using matplotlib. Finally, in the line 282 we can find the conversion of the   df data in a xlsx file (with the name "results.xlsx" in the root folder of the proyect).
  
File economic_assesment.py:
-
Contains the original file necesary for this prove.

File study_case_analysis.py:
- 
Import the economic_analysis class to solve the problem of this study case.

File results.xlsx:
-
The excel file that containts the data storaged in df, in the method "execute" of the economic_analysis class.

File README.md
-
The current file that you're reading in this moment.
