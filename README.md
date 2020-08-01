Suriel Aido teruel.

Class economic_analysis: 
-
  Contains the neccesary method to do an economic analysis based in the study case presented.
  
Methods:
- 

- boiler: return the boiler cost. Have two input params. The first input param receive the vapor production and it value have to be between 5000 and 800000. The second input param receive as value the pressure of the boiler and it value have to be between 10 and 70. If these values are not in their ranges, the system will print a Warning, indicating that the results may not be accurate.
- pump: return the centrifuge pump cost for a caudal between 0.2 and 126 L/s. As input param receive the water caudal.
- steam_turbine: return steam turbine cost for a power between 100 and 20000kW. As input param receive the power of the turbine.
- loan: return annual payment of a loan. As input params receive the investment which will be funded and the annual interest and the number of years to return the loan.
- depreciation: return the annual depreciation of investment. As input params receive the annual percent of depreciation, the capital expenditure, the plant value at the end of its life.
- william_correlation: return the william_correlation. As input params receive (for this particular case), the valor of production of the boiler, the pressure of the boiler, the power of the turbine and the caudal of the pump.
- execute: execute the economic analysis for this study case.
