This project aims to explore the different variables that impact the price of a European call option. The Blach-Scholes model for options pricing is dependent on 3 main factors, volatiltiy, time to expiration and a strike price. 
The code looks to explore the optimal strike price and time to expiration combination to have the greatest expected return.
1. The code itially pulls the historical data from a given ticker and used the standard devaition model to calculate a historical volatility
2. Later the code uses the historical volatiltiy to create simulated paths for the stock. Using the HV it uses the Black Scholes EQ to solve for a price for the option.
3. The code then finds the expecteded return from all the paths using the expected variable formula.
4. The price of the option is then subtracted to find the expected net profit.

   The code above is then repeated for a given range of Strike Prices and Time to Expirations

5. The results are then plots with the Y axis being "Expected Net Profit", X being "Strike Prices", Z being "Days till Excution"
6. The maximum and minimum points are provided showing the most & least profitable combination of Strike Prices and Length of Contract
