MT4Rstrategy
============

# OBJECTIVES

Interfacing R with Metatrader for investment strategy design and management

# INVESTMENT DISCLAIMER
Thereafter, *the Disclosing Party* refers to any authors of any content of this website either directly, or indirectly through weblink. Similarly, *the Receiving Party* refers to any individual accessing the website and any content therein.

The Disclosing Party provides general information only, and nothing contained in the provided material constitutes a recommendation for the purchase or sale of any investment vehicle, nor applying any specific wealth management strategy.
Although the statements of fact in potential reports are obtained from sources that may be considered reliable, the Disclosing Party does not guarantee their accuracy and any such information may be incomplete or condensed. 
Neverthelss, such statements are subject to change on the basis of additional or new research, new facts or developments, and revised opinion(s). 

By receiving these information and material, the Receiving Party acknowledges that the Disclosing Party is not providing financial advices tailored to its financial circumstances, and that said Receiving Party bears the burden of 
investigating the appropriateness of such information and material having regard to its own objectives, needs and financial situation, with support from competent counsel in the matter of money management as legally defined in its jurisdiction, 
prior acting on it.

The Disclosing Party expressly disclaims all liability for the use or interpretation by others of information contained in this website. Decisions based on information contained herein are the sole responsibility of the reader, and in exchange 
for using the information contained in this website *the reader agrees to hold the website's author(s) and its affiliates harmless against any claims for direct, or indirect, damages for decisions made by the reader based 
fully or partially on such information.*

# Risk(s) and Warning(s)
Please carefully review information from United States Commodity Futures Trading Commission (CFTC)  [“COMMISSION ADVISORY BEWARE OF FOREIGN CURRENCY TRADING FRAUDS”](http://www.cftc.gov/opa/enf98/opaforexa15.htm), 
United States Securities and Exchange Commission (SEC) also issued an investor bulletin [“INVESTOR BULLETING: FOREIGN CURRENCY EXCHANGE (FOREX) TRADING FOR INDIVIDUAL INVESTORS“](http://www.sec.gov/news/press/2011/2011-150.htm) 
highlighting some of the most significant risks that Forex transactions may pose for individual investors and the European Securities and Markets Authority (ESMA) issued an investor warning with respect to Forex 
[“INVESTING IN FOREIGN EXCHANGE (FOREX)”](http://www.esma.europa.eu/news/Investing-foreign-exchange-forex?t=326&o=home)

Trading foreign exchange and futures on margin carries a high level of risk, and may not be suitable for all investors. The high degree of leverage can work against you as well as for you. Before deciding to trade in 
foreign exchange, futures or other products, you should carefully consider your financial objectives, level of experience, and risk appetite. The possibility exists that you could sustain a loss of some or all of your 
initial trading account funds and therefore you should not trade money that you cannot afford to lose. You should be aware of all the risks associated with foreign exchange- and futures trading, and seek advice from a 
competent counsel in the matter of a finances if you have any doubt.

The risks described herein are not purported to be exhaustive. *Investment products and strategies are subject to risk, including possible loss of principal amount invested and therefore you should not invest money 
that you cannot afford to lose.* Past performance is not indicative of future results.  



## LICENSE
[ADAPTIVE PUBLIC LICENSE V1.0](http://opensource.org/licenses/alphabetical) as stated in [LICENSE.txt](https://github.com/florentchandelier/MT4Rstrategy/blob/master/License.txt) 
with its supplement file [SUPPFILE.txt](https://github.com/florentchandelier/MT4Rstrategy/blob/master/suppfile.txt).

*Why APL V1.0?* Beside the fact that the initial contributor may make personal choices affecting part of the license terms, **section *3.6* grants independent modules with separate license agreements**. 

Optimistically speaking, this may provide an excellent dynamic for public/private contributions, providing that modularity has been accounted for appropriately (refer to *section 1.7* of APL V1.0) during code design and development.

## CODE LAYOUT and DIRECTORIES

I will use primarily [R](http://www.r-project.org) for implementation as I believe this is a straight-forward yet extremely powerful framework in forms of scripting language for statistics. Along with the code, there should be different **.Rproj**
 files corresponding to **project workspaces** for the excellent [R-Studio IDE](http://www.rstudio.com). **Codes and Scripts validation and Verification was carried on under R-version:3.0.0 (2013.04.03) and RStudio-version:0.97.551.**
