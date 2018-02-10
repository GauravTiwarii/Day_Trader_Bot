						~~~~~**~~~~~DAY TRADER BOT~~~~~**~~~~~


From the previous learning, we can propagate to the part, where we have regex based filteration on our commands (easiest to start with). 

NOTE : I WOULD SUGGEST THIS TO GET THE DETAILS, initially, THEN HOOK UP THE AUTO TRADE PART. SO, for VERSION 0, START BY CREATING BASIC COMMANDS to GET DETAILS FROM ZERODHA, AND filter on it.

Regarding LONG LIVED TOKEN, for version 0, WE CAN START WITH GETTING LONG LIVED TOKEN USING "PAW", then integrate it with in request to slack.



PHASES OF PROJECT : 

PHASE 1 : 

-- BOT PROVIDES BASIC STOCK DETAILS, ON SENDING SPECIFIC COMMANDS. [[WORK UNDER PROGRESS]]


PHASE 2 : 

-- PROVIDE OVERALL TREND OF NIFTY
-- GET RSI FOR PROVIDED STOCK NAMES
-- GET MACD FOR PROVIDED STOCK NAMES
-- GET BOLLINGER BAND VALUES (looking for 3 values, at requested instant) 


PHASE 3 :

-- GET PARAMETER VALUES FOR ALL THE STOCKS IN NIFTY 


PHASE 4 : 

-- FILTER ON STOCKS BASED ON IF THEY MEET THE STRATEGY.

PHASE 5 : 

-- GET THE VALUES OF TARGET AND STOPLOSS FOR STOCK, IF THEY MEET THE STRATEGY.


PHASE 6 :

-- GET THE LIST OF TARGET AND STOPLOSS FOR STOCKS, WHICH ARE MEETING THE STRATEGY, AT MARKET PRICE.


PHASE 7 :

-- PLACE THE ORDER FOR FIST THREE OF THESE STOCKS, (SORTED ON RSI, MACD)



----------------------------------------------------------------------------------------
----------------------------------------------------------------------------------------

DEVELOPER GUIDELINES : -->

IN ORDER TO MAKE THIS PROJECT CONCRETE,

1. DEV SHOULD FOLLOW TEST FIRST APPROACH WITH BDD!!!! <--- TOP PRIORITY
2. DEV SHOULD ENSURE THAT RED/GREEN/[[[[**CLEAN**]]]] IS USED.
3. DEV SHOULD BE PRAGMATIC ABOUT ISSUES FACED, DURING DEVELOPMENT.
4. GET SET STARTED......

NOTE : DEV CAN GATHER ALOT OF HELP FROM PERFORMING LEARNING TESTS ON ZERODHA'S APIs.


----------------------------------------------------------------------------------------
----------------------------------------------------------------------------------------

TECHNOLIGIES USED : -->

1. LAMBDA using Node.JS
2. CucumberJS / Ghenkin for BDD
3. SLACK for BOT
4. ******HOMOSAPIENS BRAIN*********




