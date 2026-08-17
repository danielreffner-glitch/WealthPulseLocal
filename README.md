# WealthPulseLocal
A fully local wealth tracker with advanced projection, drawdown, and tax modeling features.

I created this tool to help me track investment balances and returns across several brokerages. I wanted to create an annual ledger system that would quickly let me see annualized returns across all my accounts, total returns, historical inflation data, and personal savings rates so I can track progress over years.

It requires manual input of beginning/ending balances and contributions and does not connect to the cloud at all. The data lives locally in a JSON file. It also has a fairly sophisticated modeling tool that will allow you to forecast accumulation and drawdown phases. 

I made this tool to help me see on track portfolio trends across several brokerages and forecast for retirement savings. It is not designed to be a comprehensive net worth tracker.

I would love to hear your feedback on how this tool could be more intuitive and helpful. This was vibe coded using Gemini and Claude. I am not a coder and do not claim to be. This was just a fun little project I did to make something useful for me and am putting it on here in case its useful for anyone else. Would also love any feedback you have on how to make it more intuitive and helpful!

**A Few Tips**

1. Import and save your data with the buttons at the top right of the screen. I've include a test data.json for you to load to see an idea of how the tool works.
2. I have made an effort to convert everything into real dollars, adjusting for inflation. For example, the Goal Progress Card shows your expected ending balance in todays dollars not nominal dollars.
3. The app draws data from your annual ledgers to populate the portfolio composition graphs. Switch between Growth and Tax views to see how your combined portfolio has changed over time.
4. Toggle the Plan Drawdown toggle in the top right of the Parameters card to simulate the drawdown of your portfolio. Very helpful for assessing risk. The drawdown simulations takes into account the tax composition of your latest annual ledger to simulate tax drag.
5. Effective Tax and Capital Gains Tax rate are consistent in both the Parameters and Real Spendable Power Card. Changing a value in one card will automatically update the value in the other card.
6. Hover over the information bubbles in the Parameters Card to see other helpful information about how the model uses your input values to simulate the model.
