# UMA-Price-Identifier-Nickel-USD
# **Summary**

A synthetic token which would be correlated to the price of nickel. Nickel prices will rise due to the ongoing demand for nickel in lithium-ion batteries, but people don't have the ability to partake in rise of this commodity, because exchanges such as the London Metals Exchange have such big capital requirements. This would allow people to hold a position on nickel away from physical bounds. 

# **Motivation**

*Please explain why you want to add this price identifier. What types of synthetics are you intending to create with this?*

A synthetic hedged to the price of nickel would allow people to hedge against the price of Nickel without buying physical nickel. This would democratize the process of buying nickel and make it limitless. I hope to create a synthetic token which would be between USDC and Nickel prices, allowing me to create a long position on Nickel. 

# **Data Specifications**

Although the best data would be found using Bloomberg's Commodity's Index, for most people. The best data sources would be the London Metals Exchange, Business Insider Markets and Kitco Markets. For USDT, the best platforms would be Coinbase, CoinGecko, Binance and other institutional exchanges in crypto.
*If proposing multiple price identifiers, please add markets or other data sources for each.*

---

- Price identifier name: **Nickel**
- Markets & Pairs: **London Metal's Exchange Live Nickel/USD** - *Example: Binance ETH/USDT, Coinbase Pro ETH/USD. This might not apply to all price identifiers*
- Example data providers:  London Metals Exchange Live, and Kitco Metals **Provider to use** - *Cryptowatch, TraderMade, Quandl, the Graph*
- Cost to use: **Dependant on Licensing contract with the London Metals Exchange**
- Real-time data update frequency: **30 minute update* - *60 seconds*
- Historical data update frequency: **Every 30 minutesy** - *5 minutes*

# **Price Feed Implementation**

# **Technical Specifications**

*If proposing multiple price identifiers, please add technical specifications for each.*

---

- Price identifier name: **First Price ID Name** - *ETHUSD*
- Base Currency: **ETH** - *ETH - May not apply if this is not a typical Base/Quote price*
- Quote Currency: **USD** - *USD - May not apply if this is not a typical Base/Quote price*
- Rounding: *Round to 2 decimal places (*
- Estimated current value of price identifier: *15.03*

# **Rationale**

*The section should describe why price identifier design decisions were made, as well as any alternative designs that were considered.*

I decided to use the London Metal's Exchange because the platform allows to get live price updates with the physical assets in US dollars. 

# **Implementation**

Using one of the LME's API's for updated price feeds of the Nickel prices. 

# **Security Considerations**

Pricing Manipulation may occur if someone could tamper with the centralized data from the LME. 
