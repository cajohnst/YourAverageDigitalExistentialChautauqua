# What's an order???

Is an order intuitive? > Can I describe the different types of orders without describing the base class "order"? - Maybe, but it's better to be explicit. > Let's go!

***What's an Order?***

An order is a request you send to your brokerage instructing the brokerage to buy or sell an asset on an exchange - a stock, bond, currency, future, option, etc.  It is the base unit of securities trading.

In 2021, orders are overwhelmingly placed online with near instantaneous submission confirmations, but the option to request an order over the phone is still available.

The order attributes you will submit to your brokerage will likely serve to answer these questions:

- What is the **name** of the security we are interested in?
- What **type** of security are we looking to buy or sell? I.E stock, bond, future, option, etc.
- What exchange are we looking to trade on? (For most brokerages this is left ambiguous, but as a layer of transparency, some give you the option)
- Are we looking to **buy** or **sell** the above security?
- **How** would we like to buy or sell the security? I.E At the best available market price? At a particular price - should the market move in that direction?
- If we specified we would like to buy or sell at a specific price, what is that price?
- How many "shares" would we like to buy or sell to complete the order? Some brokerages may offer fractional shares which allows you to describe the order amount in dollars. **WARNING** - From personal experience, this is probably where user error is the most prominent.  I can't say that I *haven't* submitted an order for something like 100 shares when I *meant* $100. This could obviously be a HUGE mistake, so always review your order before submitting!
- Would we like for the order to **expire**? If so, when?

**The Two Fundamental Order Types**

*Market*

A market order instructs the brokerage to execute your buy or sell request for the prescribed amount of shares at the best price available.

- What does this give me?
    The order is executed more or less immediately.
- What am I giving up?
    A price guarantee.

*Limit*

A limit order instructs the brokerage to execute your buy or sell request for the prescribed amount of shares *if* the market price is at or better than your prescribed price input.

- What does this give you?
    The order is executed at the price you want or better.
- What are you giving up?
    Certainty that the order may fill - the market price may never touch the price you are willing to pay and you might miss out on a move that you were otherwise predicting. It is also not guaranteed that if the market price *does* touch your desired price, that the entire order may fill. Your opposing buyer/seller may only want a fraction of the shares you are offering.  This scenario is called a partial fill.


To better understand how market prices work, see [What's Bid/Ask Pricing???](./whats_bid_ask_pricing.md)

**Some Examples**

***Example 1:***

I just received my paycheck and am looking to invest a fraction of it for the long term. I like Apple as a company and have a solid *bullish* outlook towards their future trajectory. I like the stock, which is trading at $110 per share currently, but I think it is slightly overvalued at the moment. I am willing to wait to purchase the stock because I believe the stock is worth $100 per share.

I want to purchase up to 1 share of Apple stock and am willing to pay as much as $100 per share for it - and if I can't get a share at this price today, then remove my request - I will re-evaluate the market tomorrow.

Translating this scenario into order language might look like:

*LIMIT BUY 1 SHARE AAPL @ 100.00 GTD for a total of $100.00 + commission.*

*Note - What does GTD mean?*

Good Till Day - A strange colloquialism used by traders instructing the brokerage to cancel an order request once the trading day is completed.  For equity, bond, options and futures markets in the US this translates to 4:30pm Eastern time. The term becomes more ambiguous in 24 hour markets such as in cryptocurrency exchange which have emerged in recent years.

***Example 2:***

I purchased Apple stock approximately 3 years ago and it has appreciated for a handsome gain. The current bid price is $140.00 and the ask price is $141.00. It's important that I sell my shares today. I would like to sell my shares for $141.00 but I am ok with settling for $140.00 for some peace of mind.

Translating this scenario into order language might look like:

*MARKET SELL 1 SHARE AAPL GTC for a total of approximately $140.00 - commission.*

The settlement amount here is an approximation and could go up or down once the order is submitted. In actuality, if the market moves down in the time I send my submission (or due to my submission), I may receive $139.00 - commission.  It is also possible I receive $140.50, or $142.00.  The difference between the settlement approximation and the actual settlement amount is called [slippage](./whats_slippage.md)

*Note - What does GTC mean?*

Good Till Cancelled - Another strange colloquialism used by traders instructing the brokerage to leave the order open until it is either filled or cancelled by the trader. For most brokerages, this is probably the default mode for order submission.  In the context of a market order, this specification is probably trivial.

*Final Thoughts*

Once you have placed an order, it is the job of the brokerage to execute the order as quickly and efficiently and (hopefully) at the best price available on your behalf.  This is why brokerage selection is so vital to your sucess as a trader or investor.  See [How to Select a Brokerage???](./how_to_select_a_brokerage.md) for information on how to make that decision.

