# Stock-Analysis
Stock Analysis Description

    I sincerely apologize to viewers because the file size is too large to upload to GitHub (I tried compressing it but it didn't work). Therefore, I have uploaded the pbix file to Google Drive via this link:
https://drive.google.com/drive/folders/1D4mKRx9OoUyOIGVbto0g38IHALfOcftg
    I hope users have the best experience with this dashboard!

I.    DESCRIPTION:
    This project was created and developed during my first journey of self-studying Power BI and this is also my FIRST PROJECT. In this project I used historical data of stock tickers of companies on both NASDAQ and NYSE exchanges and this dataset of stock tickers was recorded from 1970 - 2022. From there I decided to turn this raw dataset into a simple simulation of a regular stock trading dashboard.
    In the report, I have reproduced the basic information and indicators available on the stock market platform of the stock code such as closing price, highest/lowest price of the day, highest/lowest price in 52 weeks, total trading volume and percentage change compared to the previous day. Accompanying that is the core industry in which the stock code does business.
    For each exchange, I have designed basic but extremely important common charts that any exchange has:
- Price and volume chart.
- SMA (Simple Moving Average) chart.
- Candlestick chart.
    This project illustrates how I approached my experience learning Power BI (a powerful data analytics and visualization tool) where I was able to integrate real-world financial metrics with an actionable scenario relevant to the industry.

II.    DATA:
  <img width="3825" height="2067" alt="Screenshot 2026-02-15 153206" src="https://github.com/user-attachments/assets/d9c98c42-31d0-4d3e-9f99-453fa876b414" />
The dataset provided in the Stock Market dataset includes daily trading information ranging from 1970 to 2022, with data sourced from NASDAQ and the New York Stock Exchange, with about 1,564 (NASDAQ) and 1,145 listed companies (NYSE), respectively. It includes key fields such as Date, Open, High, Low, Close, Adjusted Close, Volume, Stock Codes and Sector.

III.    MODEL
<img width="1888" height="1014" alt="Screenshot 2026-02-15 230101" src="https://github.com/user-attachments/assets/55735156-395e-491d-9d80-1a51158ae416" />
The project model is defined using a basic multi-fact star schema. The historical trading data is split into two fact tables for NASDAQ and NYSE with each table storing stock price and trading volume data for each day. The two fact tables are related to a dimension table named Date and a table with stock information such as stock codes, sector and industry code.

IV.    NASDAQ Page - Price and Volume Chart
<img width="1919" height="1029" alt="Screenshot 2026-02-16 001334" src="https://github.com/user-attachments/assets/d897c205-1e58-499f-886c-f913daf54977" />
This chart provides a brief overview of the fundamental information of a stock. It displays:
-Close price
-% Growth: the percentage increase of the stock compared to the previous day
-52W High: the highest price in the last 52 weeks
-52W Low: the lowest price in the last 52 weeks
-Highest Price: the highest price of the day
-Lowest Price: the lowest price of the day
-Total Volume: the total trading volume of the day
-Industry (below the stock code): the industry in which the stock operates

v.    NASDAQ Page - SMA Chart
<img width="3838" height="2071" alt="Screenshot 2026-02-16 005911" src="https://github.com/user-attachments/assets/f4d28052-dfc1-4494-b7e9-84a7d6278e3d" />
For this Simple Moving Average (SMA) chart, I've added a customizable moving average line in red - the SMA (Variable Day). That can be adjusted to the user's desired period.

VI.    NASDAQ Page - Candlestick Chart
<img width="3839" height="2074" alt="Screenshot 2026-02-16 011937" src="https://github.com/user-attachments/assets/e931fe76-0c32-460f-8f2e-f1421913be8d" />
This report also integrates a candlestick chart to provide deeper insights into price fluctuations, market trends and short-term trading signals.

VII.    NYSE Page - Price and Volume Chart
<img width="3836" height="2074" alt="Screenshot 2026-02-16 012618" src="https://github.com/user-attachments/assets/c49a653f-6562-4fc7-9de8-7bb444a5d705" />

VIII.    NYSE Page - SMA Chart
<img width="3833" height="2075" alt="Screenshot 2026-02-16 012848" src="https://github.com/user-attachments/assets/5231338a-1804-436a-bca1-a115e3666b1b" />

IX.    NYSE Page - Candlestick Chart
<img width="3836" height="2074" alt="Screenshot 2026-02-16 012941" src="https://github.com/user-attachments/assets/e31175c7-afb0-4645-ab02-9671d9378cea" />
