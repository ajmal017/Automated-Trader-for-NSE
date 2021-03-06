Automated Trader for NSE
=================================


**Automated Trader for NSE** software is for trading the signals provided by **The Portfolio Trader**'s [NSE Trades](http://www.theportfoliotrader.com/nse-trading/). The software is provided **FREE OF COST**.

**The software comes with**:

* Host of simplified features for trading with [Interactive Brokers](http://www.interactiverbrokers.com) via IB Gateway api connectivity
* One click process for downloading, processing, placing and reporting of **The Portfolio Trader**'s [NSE Trades](http://www.theportfoliotrader.com/nse-trading/) (activation license key required)
* Set and forget hands-free feature for performing the one-click process automatically everyday at a designated time [*disabled feature*]

**Requirements**:

* Windows operating systems ( XP or higher), LINUX and OS X/Mac OS via [Mono](http://www.mono-project.com/)
* .NET Environment (usually Win7 onwards the operating systems comes pre-loaded with .NET environment, [Mono](http://www.mono-project.com/) on Linux and MacOS)
* stable Internet connection (minimum speed 500kbps)
* Account with [Interactive Brokers](http://www.interactivebrokers.com) for trading
* [Interactive Brokers Trader Workstation or Gateway](https://www.interactivebrokers.com/en/index.php?f=14099#tws-software)
* Subscription to **The Portfolio Trader**'s [NSE Trades](http://www.theportfoliotrader.com/nse-trading/) (_required only if you wish to activate **Auto Trade** feature_)

**Download**:
Visit [Automated Trader for NSE](http://www.theportfoliotrader.com/downloads/automated-trader-for-nse/) to download this software.

> **Note**:
> * Please use a valid email address while registering to download the software.
> * License key will be generated and emailed to your email address. You will have to input this license key when prompted during the first run.
> * The software is made available with single-computer license i.e. locked to one computer.
> * In case you want to run this software on multiple computers increase the number of license's required during the registration process or contact info@theportfoliotrader.com for assistance.
> * _This application should run fine on LINUX and OS X/Mac OS via [Mono](http://www.mono-project.com/). However, I have not tested this thoroughly. Contact info@theportfoliotrader.com if you want me to perform a thorough testing on LINUX or OS X/Mac OS_

<br>
<br>


<!-- START doctoc generated TOC please keep comment here to allow auto update -->
<!-- DON'T EDIT THIS SECTION, INSTEAD RE-RUN doctoc TO UPDATE -->

Table of Contents
-----------------
[Automated Trader for NSE](#automated-trader-for-nse)
  - [Architecture](#architecture)
  - [Features](#features)
    - [Interactive Brokers (IB) connectivity](#interactive-brokers-ib-connectivity)
    - [Auto Trade](#auto-trade)
  - [How To](#how-to)
    - [Set Up](#set-up)
      - [Install](#install)
      - [First Run](#first-run)
    - [Connect to IB gateway](#connect-to-ib-gateway)
    - [Subscribe to account information](#subscribe-to-account-information)
    - [Close open positions](#close-open-positions)
    - [Place or modify orders](#place-or-modify-orders)
      - [Changing extended ticker attributes](#changing-extended-ticker-attributes)
      - [Changing extended order attributes](#changing-extended-order-attributes)
    - [Cancel orders](#cancel-orders)
    - [Check executions](#check-executions)
    - [Auto Trade: Set Trade Settings](#auto-trade-set-trade-settings)
    - [Auto Trade: Set TPT Web Settings](#auto-trade-set-tpt-web-settings)
    - [Auto Trade: Set Report Settings](#auto-trade-set-report-settings)
    - [Auto Trade:  One-Click Process](#auto-trade--one-click-process)
    - [Auto Trade: Orders & Log Diary](#auto-trade-orders--log-diary)
    - [Auto Trade: Report Format](#auto-trade-report-format)
  - [Support](#support)
  - [License](#license)
  - [Risk Disclosure Statement](#risk-disclosure-statement)

> _Note_: _Table of Contents_  *generated with [DocToc](https://github.com/thlorenz/doctoc)*

<!-- END doctoc generated TOC please keep comment here to allow auto update -->


<br>
<br>


##Architecture
-----------------
The architecture of this software is presented in the figure below:
![Automated Trader for NSE](https://github.com/virusme/Automated-Trader-for-NSE/blob/master/screenshots/AutomatedTrader_Diagram.png)

:arrow_double_up: [Back to Top](#table-of-contents)

<br>
<br>

##Features
----------


### Interactive Brokers (IB) connectivity
* **Connection**
    * Connection status indicator
    * Connect to IB Gateway by setting IP address, log level, port number and client id including Connect and Disconnect buttons
    * Log: Server logs, Error logs, Clear error log button

 ![Connection](https://github.com/virusme/Automated-Trader-for-NSE/blob/master/screenshots/tabs_connection.png)

<br>
    
* **Account** 
    * Account number indicator
    * Last sync time indicator
    * Subscribe, Unsubscribe and Clear Account Summary buttons
    * Summary and Portfolio tabs
    * Close Position by right-click on Portfolio

    ![Account](https://github.com/virusme/Automated-Trader-for-NSE/blob/master/screenshots/tabs_account.png)

<br>

* **Order**
    * Ticker description and Order description (including extra Ticker attributes and Order attributes)
    * What-If, Place Orders, GLOBAL CANCEL, Clear Orders buttons
    * Next Order-ID in-sync with IB Gateway
    * Open Orders and Order Status tab
    * Cancel Order by right-click on Open Orders

    ![Orders](https://github.com/virusme/Automated-Trader-for-NSE/blob/master/screenshots/tab_orders.png)

<br>

* **Executions**
    * Executions request settings
    * Request Executions and Clear Executions button
    * Reports tab

    ![Executions](https://github.com/virusme/Automated-Trader-for-NSE/blob/master/screenshots/tabs_executions.png)

<br>
    
* **Settings**
   * All settings i.e. connection, ticker and order settings saved in an XML file (ibSet.xml)
   * Every time the application loads, it will retrieve settings from the settings XML file

<br>

* **In-Sync**
   *  Always in-sync with IB Gateway i.e. whenever IB Gateway delivers data, all logs, account summary, portfolio changes, order status changes are updated


:arrow_double_up: [Back to Top](#table-of-contents)


<br>
<br>

###Auto Trade
* **Trade Settings**
   * Set paths for downloaded files
   * Manage your trade details such as exchange, position size, margin, etc.

<br>
   
* **The Portfolio Trader Login**
    * Your login details for **The Portfolio Trader**'s [NSE Trades](http://www.theportfoliotrader.com/nse-trading/)
    * Stored locally, in your computer, using strong encryption

<br>

* **Report Settings**
    * Set your to and from email and its mail settings for report delivery
    * Stored locally, in your computer, using strong encryption

<br>
    
* **Process**
    * One-Click processing for downloading, order management, placing orders and report generation

<br>

* **Orders, Log Diary and Log**
	* List of day's orders and log diary of orders
	* Process log to keep you up-to-date on the current process
 
  ![Auto Trader](https://github.com/virusme/Automated-Trader-for-NSE/blob/master/screenshots/tab_autotrade.png)


:arrow_double_up: [Back to Top](#table-of-contents)

<br>
<br>

## How To

### Set Up

#### Install
* You will download a **.zip** from the [download area](#download)
* Extract the **.zip** file to your chosen location, a new folder titled **TPT Automated Trader** will be created. For example, I have extracted the **.zip** to **D:\** drive

![first_open](https://github.com/virusme/Automated-Trader-for-NSE/blob/master/screenshots/firstrun_open.png)

<br>

#### First Run
* Double click on **TradingAutomation.exe**
* Enter license key when prompted

![license_key](https://github.com/virusme/Automated-Trader-for-NSE/blob/master/screenshots/firstrun_key_2.png)

>**Note**:
> * License keys are emailed to your email address when you downloaded the software.
> * It is not mandatory to input the license key. However, **Auto Trade** facility will be only be activated for valid licenses. In case of invalid license key, you will have access to all other facility i.e. Interactive Brokers Gateway interface, but not **Auto Trade**. You will have the option of activating **Auto Trade** using **Activate Auto Trade** button on the **Connection** tab.

:arrow_double_up: [Back to Top](#table-of-contents)


<br>
<br>

### Connect to IB gateway
* Log in to your IB account via IB Gateway or Trader Workstation
* Go to **Connection** tab
* Click **Connect** (usually the default setting provided will work, unless IB TWS/Gateway API settings are different to default setting)

![connect](https://github.com/virusme/Automated-Trader-for-NSE/blob/master/screenshots/2_connect.png)

>**Note**:
> * [Instructions on to how to enable connectivity to IB Gateway or Trader Workstation](https://github.com/virusme/Automated-Trader-for-NSE/wiki/IB-API-Settings) 
> * IB Trader Workstation is a full-featured trading platform, it requires lots of memory and needs restart every 24 hours. Whereas IB Gateway is headless (no user-interface) connectivity to IB servers, it requires minimal memory and does not need restarts that often.
> * To use with Automated Trader for NSE, I recommend IB Gateway because it is light-weight and does not need restarts
>* Server and error logs provide a log of IB server requests and any error reports that IB Server reports or that arise due to connection with IB Server
> ![servererr](https://github.com/virusme/Automated-Trader-for-NSE/blob/master/screenshots/2_servererrlogs.png)


:arrow_double_up: [Back to Top](#table-of-contents) 

<br>
<br>

### Subscribe to account information
* Go to **Account** tab
* Click **Subscribe**

![account](https://github.com/virusme/Automated-Trader-for-NSE/blob/master/screenshots/2_acct_subscribe.png)


:arrow_double_up: [Back to Top](#table-of-contents)

<br>
<br>


### Close open positions
* Go to **Account** --> **Portfolio** tab
* Right-click on the open position that you intend to close
* Click **Close Position**

![closepos](https://github.com/virusme/Automated-Trader-for-NSE/blob/master/screenshots/2_portfolio_closepos.png)


:arrow_double_up: [Back to Top](#table-of-contents)

<br>
<br>


### Place or modify orders
* Go to **Orders** tab
* Click **Place/Modify Order**
* A pop dialog opens up where you can enter your order details and click **Place/Modify Order**

![placeorder](https://github.com/virusme/Automated-Trader-for-NSE/blob/master/screenshots/2_place_orders.png)


:arrow_double_up: [Back to Top](#table-of-contents)

<br>
<br>


#### Changing extended ticker attributes
* Go to **Orders** --> **Place/Modify Order**
* Click **Ext. Ticker Attr.**
* Make changes and click **Apply**

![placeorder_extticker](https://github.com/virusme/Automated-Trader-for-NSE/blob/master/screenshots/2_place_orders_extticker.png)

<br>

#### Changing extended order attributes
* Go to **Orders** --> **Place/Modify Order**
* Click **Ext. Order Attr.**
* Make changes and click **Apply**

![placeorder_extorder](https://github.com/virusme/Automated-Trader-for-NSE/blob/master/screenshots/2_place_orders_extorder.png)


>**Note**:
>* For definition and description of each of the parameters in ticker attributes or order attributes please visit [Interactive Brokers knowledge base](https://ibkb.interactivebrokers.com/)
>* Default settings work fine for day orders
>* Every time **Apply** is clicked, the settings are saved automatically for future use
>* **GLOBAL CANCEL** cancels all open orders in one go.


:arrow_double_up: [Back to Top](#table-of-contents)

<br>
<br>


### Cancel orders
* Go to **Orders** --> **Open Orders** tab
* Right click on the order that you wish to cancel and select **Cancel Order**

![placeorder_cancel](https://github.com/virusme/Automated-Trader-for-NSE/blob/master/screenshots/_placed_orders_cancel.png)


:arrow_double_up: [Back to Top](#table-of-contents)

<br>
<br>


### Check executions
* Go to **Executions** tab
* Click **Request Executions**
* In case, you want to retreive the execution report of a particular order, use the form provided to fill in the details before clicking **Request Executions**

![reqexe](https://github.com/virusme/Automated-Trader-for-NSE/blob/master/screenshots/2_reqexecutions.png)

>**Note**:
>* Interactive Brokers provide execution report for the day (24 hours) and the **Report** table is always in-sync with IB data. Therefore, in most cases you will rarely have to **Request Executions** as they are delivered to this software as and when IB reports it.


:arrow_double_up: [Back to Top](#table-of-contents)

<br>
<br>


### Auto Trade: Set Trade Settings
The data provided in this setting will be used by auto-trade for determining your security type, exchange, position size, etc.

* Go to **Auto Trade** tab
* Click **Trade Settings**
* Make changes as required and click **Apply**
*  Default settings work well
*  Definition of terms:
  * **File Path**: Location or a directory where you want the downloaded files to be saved. If left empty, the default is the folder the application is running in.
  * **Exchange**:  NSE( default). The exchange this auto-trade will be working on
  * **Market Prefix**: NSE_ (default)
  * **Currency**: INR (default). The currency this auto-trade will be utilising
  * **Sec. Type**: STK (default). The security type this auto-trade will be trading
  * **Leverage**: 1.0 (default). The leverage/margin you wish to use.
  * **Allocation**: 100% (default). The percentage of capital you wish to auto-trade with. For example, if you have INR 100K, and set **Allocation** as 60%, then only INR 60K will be used for auto-trade
  * **Position Size**: 10% (default). The percentage of allocated capital per position
  * **Max. Amount**: 2000000 (default). Any high number you wish, this is used to make sure no *crazy* orders are placed on the market

![tpt_trade](https://github.com/virusme/Automated-Trader-for-NSE/blob/master/screenshots/2_at_tradeset.png)

>**Note**:
>* Do not change settings under **Trades Sheet Settings**, **Auto Trade** will not work if you change this setting
>* Every time **Apply** is clicked, the settings are saved for future use


:arrow_double_up: [Back to Top](#table-of-contents)

<br>
<br>


### Auto Trade: Set TPT Web Settings
The login and password provided here will be used to login to **The Portfolio Trader**'s website.

* Go to **Auto Trade** tab
* Click **tPT Web Settings**
* You should enter your login and password that you use to access **The Portfolio Trader**'s [NSE Trades](http://www.theportfoliotrader.com/nse-trading/)
* This data is stored locally on your computer using strong encryption for future use

![tpt_web](https://github.com/virusme/Automated-Trader-for-NSE/blob/master/screenshots/_at_tptset.png)


:arrow_double_up: [Back to Top](#table-of-contents)

<br>
<br>


### Auto Trade: Set Report Settings
The data provided here will be used for generating and saving reports, as well as emailing the report to your chosen email address

* Go to **Auto Trade** tab
* Click **Report Settings**
* Make changes as required and click **Apply**
* Definition of terms:
  * **From-Email Settings**
     * **Email Address**:  An email address that you own from which you want to send email from
     * **Password**: Password to the above email-address
     * **Custom Email Subject**: A tag or an identifier that will be prefixed to the subject of the email for your identification at the other end. You can chose to leave this empty.
  * **Mail Settings**: This setting will let your computer know how to send the email
     * **SMTP**: SMTP address of your from-email address provider. The one shown in the figure below is from **GMAIL**
     * **Port**: Port number settings for your from-email address provider. The one shown in the figure below is from **GMAIL**
   * **To-Email Settings**
      * **To Email Address**: An email address that you may/may not own to which you want the email with report attached to be sent to

![tpt_report](https://github.com/virusme/Automated-Trader-for-NSE/blob/master/screenshots/_at_reportset.png)

>**Note**:
>* To send an email, one needs an email address where the email originates (from-email) and a destination email (to-email)
>* **From-Email** and **To-Email** could be the same email address


:arrow_double_up: [Back to Top](#table-of-contents)


<br>
<br>


### Auto Trade:  One-Click Process
This will download the [NSE Trades](http://www.theportfoliotrader.com/nse-trading/nse-trading-trades/), check account information, process orders, manage orders, generate new orders to be placed, place orders to IB server, prepare a detailed report of this processing and email the report.

* Go to**Auto Trade** tab
* Click **Process**
* And that's it!

![tpt_process](https://github.com/virusme/Automated-Trader-for-NSE/blob/master/screenshots/_at_process.png)

>**Note**:
>* The figure above shows the detailed process log


:arrow_double_up: [Back to Top](#table-of-contents)

<br>
<br>


###Auto Trade: Orders & Log Diary
Details of order management, daily orders and daily log (number of orders, file downloaded, etc.) will displayed here at the end of  [One-Click Process](#auto-trader-one-click-process)

To View details of order management and daily orders:
* Go to **Auto Trade** --> **Orders**

![tpt_orders](https://github.com/virusme/Automated-Trader-for-NSE/blob/master/screenshots/_at_orders.png)

To View details of daily logs:
* Go to **Auto Trade** --> **Log Diary**

![tpt_logdiary](https://github.com/virusme/Automated-Trader-for-NSE/blob/master/screenshots/_at_logdiary.png)


:arrow_double_up: [Back to Top](#table-of-contents)

<br>
<br>


###Auto Trade: Report Format

![tpt_report](https://github.com/virusme/Automated-Trader-for-NSE/blob/master/screenshots/2_report.png)

The report that will generated and emailed would consist of:

*  *Summary*: Summary of your account and placed orders
* *Process Log*: Process log of auto-trade
* *Log Diary*: Daily log of number of buy, sell, open positions and comments
* *Orders*:  Buy, sell that have been placed via auto-trade and open orders 
* *The Portfolio Trader*: The Portfolio Trader's orders for the day
* *Portfolio*: A snapshot of your portfolio at the time of processing
* *API Error Logs*: Error log from the IB server

>**Note**:
>* The reports are saved in the directory where this application resides under **reports** directory
>* Reports are organised in **MMYYYY** folder with **ddMMYYY.xlsx** format, for example report for **19th February 2016** will be under **reports/022016/** and the file name would be **19022016.xlsx**


:arrow_double_up: [Back to Top](#table-of-contents)

<br>
<br>


Support
---------
Contact info@theportfoliotrader.com for assistance or if you have any queries


<br>
<br>


License
----------
<p align="justify">
All the computer programs and software are supplied with the explicit understanding that they are to be used for personal purposes only. It is expressly prohibited to use the software by any organisation, firm, Limited Liability Company or Private Limited company.
</p>
By downloading or using the programs, you acknowledge acceptance of the following DISCLAIMER OF WARRANTY:

<p align="center">
DISCLAIMER OF WARRANTY
</p>
<p align="justify">
ALL THE COMPUTER PROGRAMS AND SOFTWARE ARE PROVIDED "AS IS" WITHOUT WARRANTY OF ANY KIND. WE MAKE NO WARRANTIES, EXPRESS OR IMPLIED, THAT THEY ARE FREE OF ERROR, OR ARE CONSISTENT WITH ANY PARTICULAR STANDARD OF MERCHANTABILITY, OR THAT THEY WILL MEET YOUR REQUIREMENTS FOR ANY PARTICULAR APPLICATION. THEY SHOULD NOT BE RELIED ON FOR SOLVING A PROBLEM WHOSE INCORRECT SOLUTION COULD RESULT IN INJURY TO A PERSON OR LOSS OF PROPERTY. IF YOU DO USE THEM IN SUCH A MANNER, IT IS AT YOUR OWN RISK. THE AUTHOR AND PUBLISHER DISCLAIM ALL LIABILITY FOR DIRECT, INDIRECT, OR CONSEQUENTIAL DAMAGES RESULTING FROM YOUR USE OF THE PROGRAMS.
</p>

<br>

###Interactive Brokers API
C# API is provided by [Interactive Brokers](http://www.interactivebrokers.com). Please refer to [Interactive Brokers](http://www.interactivebrokers.com) for any licensing terms and conditions of their API.

**DISCLAIMER**: Automated Trader for NSE software is not approved by [Interactive Brokers](http://www.interactivebrokers.com) or any of its affiliates. 

<br>

###The Portfolio Trader
Subscription to **The Portfolio Trader**'s [NSE Trades](http://www.theportfoliotrader.com/nse-trading) is provided by [The Portfolio Trader](http://www.theportfoliotrader.com). Please refer to [The Portfolio Trader](http://www.theportfoliotrader.com) for terms and conditions.

<br>

Risk Disclosure Statement
-------------------------------
<p align="justify">
THE RISK OF LOSS IN TRADING SECURITIES AND LEVERAGED INSTRUMENTS CAN BE SUBSTANTIAL. YOU SHOULD THEREFORE CAREFULLY CONSIDER YOUR OBJECTIVES, FINANCIAL SITUATION, NEEDS AND ANY OTHER PERSONAL CIRCUMSTANCES TO DETERMINE WHETHER SUCH TRADING IS SUITABLE FOR YOU.

HIGH LEVERAGE OF LEVERAGE IS OFTEN OBTAINABLE. YOU SHOULD BE AWARE THAT THE USE OF LEVERAGE CAN LEAD TO LARGE LOSSES AS WELL AS GAINS.

THIS BRIEF STATEMENT CANNOT DISCLOSE ALL OF THE RISKS AND OTHER SIGNIFICANT ASPECTS OF SECURITIES AND DERIVATIVES MARKETS. THEREFORE, YOU SHOULD CONSULT YOUR FINANCIAL ADVISOR OR ACCOUNTANT TO DETERMINE WHETHER TRADING IN SECURITES AND DERIVATIVES PRODUCTS IS APPROPRIATE FOR YOU IN LIGHT OF YOUR FINANCIAL CIRCUMSTANCES.
</p>
<br>
:arrow_double_up: [Back to Top](#table-of-contents)

[scroll-to-top]:https://github.com/virusme/Automated-Trader-for-NSE/blob/master/screenshots/scroll-top-icon-25.png