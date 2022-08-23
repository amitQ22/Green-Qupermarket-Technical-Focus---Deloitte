# Team Name: Qustomers
Womanium Quantum Hackathon challenge 2022

# Team Member Details: 

  1. Dinesh Vishnu Kumar C , discord id : Dinesh Vishnu Kumar C#6351, github id:dineshvishnugithub, email: dinesh.sar67@yahoo.com
  2. Kalai Ramea , discord id: Kalai#2645, github id: kramea, email: kalai.ramea@gmail.com
  3. Yongjia He , discord id: Yongjia_He#0696, github id: YongjiaHe, email: yjhe2020@g.ucla.edu
  4. Amit Kumar Singh, discord id: amit singh#2143, github id: amitQ22, email : amitsingharrah@gmail.com
  5. Perminder , discord id: perminder#9674, github id: perminderUPM  email : quantum.technocrat@gmail.com
  
# Name of the Challenge : Green-Qupermarket-Technical-Focus---Deloitte

# Name of the Pitch Presenter: Dinesh Vishnu Kumar Chandrasekaran

# Solution for the challenge:
  Files under /solution directory is submitted for the challenge.
  Files under /AdditionalApproaches is for showing solutions in classical way and battery reset in daily basis and annealer solution for both discharging and charging

# Hack Solution Details :<br>
Step 1: under folder /solution, download and install the needed libraries<br>
Command : pip install -r requirements.txt <br>
<br>
Step 2: we have 2 folders /solution and /additonal_approaches. /solutions had 1 file to be submitted for challenge and /additonal_approaches has 3 solutions, 2 quantum and 1 classical for our analysis <br>
<br>
i)   Quantum hybrid solution in which mall battery is reset on weekly basis - the mall battery is reset every monday<br>
     DeloitteQuperMarketDataRetreival__MallBatteryResetWeeklyBasis.ipynb<br>
     <br>
ii)  Quantum hybrid solution in which mall battery is reset on daily basis - the mall battery is reset every day<br>
     DeloitteQuperMarketDataRetreival_MallBatteryResetDailyBasis.ipynb<br>
     <br>
iii) Quantum solution which doesnt compute the calculations classically<br>
     DeloitteQuperMarketDataRetreival_Quantum.ipynb<br>
     <br>
iv)  Classical solution which is based on Gurobi optimizer<br>
     ClassicalAlgorithm.ipynb<br>
     <br>
<br>
Step 3: Please use the car data sheet from our repository as we have included 2 new columns Discharging Ind and Charging Ind for our better optimisation. <br>
If high volume of data is used or any new data sheet is used, please rename the two new columns as this and execute the file.<br>
<br>
Step 4: under /solutions/pythonFiles folder we find the DeloitteQuperMarketDataRetreival__MallBatteryResetWeeklyBasis.ipynb solution to be optimum with best values.<br>
        So we are submitting this solution to the jury to run and check.<br>
        Command : jupyter notebook DeloitteQuperMarketDataRetreival__MallBatteryResetWeeklyBasis.ipynb<br>
 <br>
Step 5: We have commented the Dwave hardware access token and the get sampler method. Instead we have enabled to use the sampler from the neal library<br>
<br>
Step 6: files under /additional_approaches are only for analysis and are not perfect solutions.<br>
<br>
Step 7: under /solution/DataAnalysis, we have placed the data analysis done on the basis of battery reset done on weekly basis vs daily basis and also the plug power plotting and carbon cost plotting for the week and the day. Please refer to DataAnalysisSheet.xlsx.<br>
This shows which car got charged and discharged in which interval.<br>
<br>
Step 8: under /solution/logs, we have submitted the logs take for on the basis for mall battery weekly reset and daily reset.<br>
Analysis shows that if battery is reset based on weekly basis, then we are able to get better results.<br>
<br>

