# Restaurant-Chatbot
Restaurant Chatbot using Rasa and Zomato Apis
The chatbot provide results for tier-1 and tier-2 cities only, while for tier-3 cities, it replies back with "We do not operate in that area yet".
# Cuisine Preference: 
The bot takes the cuisine preference from the customer. The bot lists out the following six cuisine categories (Chinese, Mexican, Italian, American, South Indian & North Indian) and the customer can select any one out of that.
# Average budget for two people: 
Segment the price range (average budget for two people) into three price categories: lesser than 300, 300 to 700 and more than 700. The bot asks the user to select one of the three price categories.
The bot displays the top 5 restaurants in a sorted order (descending) of the average Zomato user rating (on a scale of 1-5, 5 being the highest). 
The bot also asks the user whether he/she wants the details of the top 10 restaurants on email. If the user replies 'yes', the bot asks for user’s email id and then send it over email. Else, it replies with a 'goodbye' message.
