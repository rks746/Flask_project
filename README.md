# Flask_project
a stock market simulation game with virtual companies, shares and currency 


Stock Market Simulation Game Plan

Objective
To create an engaging stock market simulation where college students pitch their startup ideas, and an audience of "investors" buys and sells shares in these startups. The game will determine the most valuable company and the best investors based on their portfolio value.

 
Game Structure

Phase 1: The Pitchers (Startups)
 Who participates?
• College students with startup ideas.
• Teams pitch their ideas to a panel.
 Selection Process:
• The top 5 best startup ideas are selected.
• We help these teams refine and improve their ideas and present a perfect pitch on event day.
 Company Registration:
• The 5 selected teams become "companies."
• Each company is assigned an initial stock price (either the founders choose or we assign based on how good the idea is).
 
Phase 2: The Investors (Stock Market Game)
 Who participates?
• Anyone interested in investing (should register as teams or individuals beforehand).
 Game Setup:
• Each investor/team gets a fixed amount of virtual cash (e.g., Rs 10,000).
• Investors can buy and sell shares of the 5 startup companies.
• If more people buy a stock, its price increases. (based on calculations, obviously)
• If more people sell a stock, its price decreases. (based on calculations, obviously)
 
Event Day:
• The startup teams present their ideas to the investors (2-minute pitch) (they can share more
information later).
• Investors decide which stocks to buy/sell based on presentations.
• The game runs for a fixed time period (e.g., 2-3 hours).
• Stock prices are updated every 15 minutes.


How Winners Are Decided
 
 Best Investor (Audience Participant) – highest score in the end
 Final Score = (0.7 × Portfolio Value) + (0.3 × Cash Balance)
 (Weighted average taken so that investors do not sell all their share to cash out in the end. This would affect company valuation.)
 
 Best Startup (Pitchers)
 We have multiple options to decide the winning startup:
 Stock Price Method → The startup with the highest stock price at the end wins.
 Company Valuation Method → Based on market cap (total shares × stock price).
 Hybrid Model → Combination of stock price, audience votes, and panel evaluation.

 
Implementation Plan
• We can build a simple website where registered teams/individuals can buy/sell stocks of the 5 companies. The stock price will however not be revealed in real time (share prices updated every 15 minutes).


Ways to keep investors/audience engaged (potential options)

Mystery stock bonuses – every once in a while, a particular company’s share value increases by 20%, thus increasing overall portfolio value for its investors.
Q&A sessions with founders (audience can ask tough questions and the reply and confidence of the founder will reflect in people’s belief in him/her, thus affecting share value.
Founders can announce discounts and offers midway. (E.g. Anybody who buys 15 shares of my company in one trade would get 5 shares for free.
Relevant news and announcements which can potentially affect the company value (positively/negatively). We can categorise them into official announcements, rumours, media reports etc. (E.g. Trump introduces new tariffs on imports).
Live polls where the audience votes on whether a stock should increase or decrease based on a
pitch.
Midway through the event, a brand-new surprise company is launched with no information revealed. Over time, more details emerge, influencing investor decisions. Investors must decide whether to take the risk early or wait for more details.
