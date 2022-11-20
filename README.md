<H1># UNCC-Fintech-Project-1</H1>
<H1> ETF ANALYZER </H1>
<li>The python code is an ETF Analyzation tool which pulls data from API Keys utilizing the Monte’Carlo Simulation but not limited to Monte Carlo initial Simulation data.  Its utilizing drawndown and sharpe ratio using imperical functions to calculate volatility.</li>

<H2><em><strong>STEPS TO OPERATING ETF ANALYZER</strong></em></H2>

<li>How would assets behave during an economic disruption?</li>
<li>What would be the volatility?</li>

<H1> Flow </H1>
<li>User uploads an API KEY to access asset class data for analysis.</li>
 <li>User selects a group of ETFs and Stocks for analysis. </li>
 <li> User imports and uploads .env file </li>
 <li> User pulls API to utilize data. (NOTE) this could be to import tickers.
 <li>This code seeks to pull and evaluate any particular asset class chosen to see what effects the current global financial environments   will have on the selected market. </li>

<H2>PULL TIMEFRAME </H2>
     <li>Pull time frame in order to determine a selected date in order to pull relevant data</li>
    <li> What is the purpose of pulling the specific timeframe
     <li>Are we meaning to include specific outliers, eg. COVID-19, or would you prefer to keep a more average flow of time? 
      
<H2>Pull Daily Return</H2> 
        <li>Daily Returns is the data which is pulled utilizing the API Key. </li>
<H2>PULL PLOT </H2>
     <li>utilizing hvplot </li>
     <li>Note:You may use a specific plot which utilizes tickers </li>
   
<H2>Utilize Empyrical Function</H2>   
<li>Empyrical Sharpe Ratio Function gives you risk adjusted returns</li>

<H2>Utilize hvplot</H2>
<li>hvplot is utilized as a means to show data in a more interactive way. It allows us to physically interact with the data in order for the user analyze the data more efficiently.</li>

<H2>Used dotenv</H2>  
<li>To load the dotenv file so we can use our secrete keys for the APIs</li>

<H2>import alpaca_trade_api as trade api</H2>
<li>The purpose of the trade api is to load the ticker information and put them into a dataframe</li>

  <H3><em><strong>Questions:</strong></em></H3>
<ol>

  <li>What were some of the challenges that were faced? How were they resolved? </li>
  <li>We are looking for the possible outcomes of data? </li>
   <li>What were the pre-pandemic vs post pandemic stock figures 2019 - 2021? </li>
         <li>How did the selected stocks perform, specifically during the pandemic? </li> 
      <li> Which Sector/Market had the lowest/Highest risk?</li>
</ol>
<H3><em><strong>Contributors:</strong></em></H3>


  <li>Cesar Sandiford</li>
  <li>Duke Boger</li>
  <li>A'Brea Penn</li>
  <li>James Bennett</li>
  <li>Steven Jordan</li>



<H3><em><strong>Instructor:</strong></em></H3>
-Venu Thamodharan
<H3><em><strong>Teacher Assistant</strong></em></H3>
-Matt Stoffer

<H4>References:
  <li> https://pypi.org/ Used to pull empyrical data </li>
<li> (DRAWDOWNS Section)(https://www.quantrocket.com/codeload/quant-finance-lectures/quant_finance_lectures/Lecture33-Portfolio-Analysis-with-pyfolio.ipynb.html) </li>
  
